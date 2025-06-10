# **User Guide – Sentinel Device**

## **Contents**
1. Start Up  
2. Connect Your Polar HRT H7  
3. Ready to Use  
4. Data Transfer  
5. Application  

---

## **1. Start Up**

To start using the device, it needs power. Fortunately, the Sentinel has a built-in battery. You can power it on in two ways:

- Use the **switch** on the side of the ESP32  
- Or connect it to a computer via **USB-C**

Once powered on, an LED light will be **emitted in green, yellow, or red**, indicating that the device is active.

> **Note:**  
> If the device is powered through USB-C, the LED will emit a **red light**, showing that it's powered externally rather than by the internal battery.

✅ **The device is now powered on and ready!**

---

## **2. Connect Your Polar HRT H7**

The next step is to connect your heart rate transmitter (HRT). The **Polar HRT H7** is always in pairing mode.

1. Attach the HRT band securely to your chest  
2. The Sentinel will automatically connect to the HRT – no manual pairing is needed

✅ **The HRT is now connected!**

---

## **3. Ready to Use**

The Sentinel is now fully operational. It will continuously monitor:

- Heart rate  
- Temperature and humidity  
- Dangerous gases  
- Falls or sudden movements  
- Step count

> ⚠️ **Note:**  
> LTE and GPS may take a few minutes to initialize.

---

## **4. Data Transfer**

The Sentinel collects sensor data at different intervals and sends it regularly to our backend system.

- Each user has a dedicated section in the database  
- The API ensures that data is correctly linked to the right user  
- Data is handled securely and stored safely

> It may take a few minutes for all sensors to activate and begin sending data.

---

## **5. Application**

The frontend application visualizes your data:

1. Log in using your credentials  
2. View your current stats on the dashboard  
3. Access additional features:
   - Personal info under the **User** tab  
   - News feed under the **News** tab  
   - Switch between **Light** and **Dark mode**

> ⏳ It might take a few minutes for new data to appear in the app.  
> 🔄 To refresh the data, **close and reopen the application** (refresh button not yet available).
