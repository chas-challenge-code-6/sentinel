# ARCHITECTURE


## Components

### MQ2 Gas sensor
> Used to detect dangoures gas in the vicinity.

### DHT 11 sensor
> Used to read temperature and humidity

### Polar HRT H7 EKG sensor
> Used to read the users current heart rate

### ADXL345 Accelerometer
> Used to detect fall and movment of the user

### Lilygo ESP 32 S3 SIM7670
> Main hardware to collect data and process the data, with built in LTE/GPS compatability for use to send notifications to nearby users.

## Structure / Examples

### If waring to user

Steps are read from the ADXL345. If it detects over 10 000 steps -> Send a notice to the user via the application. 

Psuedo code:
```cpp
steps = 0

// ESP32 checks the following:
if steps > 10 000:
  send data to esp32

if esp32.revicedData
  send data to database

// Data is sent to user
```



### In normal conditions

Steps comes from the sensor. The ESP32 recives the data every 10:th second (for example) -> The queue is cleared in order to free up memory -> data is sent to database -> data is shown in the mobile app

```cpp
steps = 0
time = 0

if time > 10:th second:
  send data to esp32


if esp32.revicedData
  send data to database
  clear data from queue to save memory

// data is sent to the mobile app. No notis is sent to the user but the user can see the current steps in the application 
```


### Hot day and many steps

The temperature sensor reads the current temperature in the current enviorment. Steps is calculated. If it's 25 C and steps is over 5000 -> Data is sent to the ESP32 -> Data is sent to the database -> Data is shown in the app and a notis is sent to the user like "Take a break, it's currently hot outside and you have worked hard! Take a brake and drink some water"

```cpp
steps = 0
temp = 25 C

if temp >= 25 && steps = 5000
  send data to ESP32
  clear memory for the ESP32

Om esp32.recivedData
  send data to database

// data is sent to the mobile app, a warning notis is sent to the user to take a break.
```




