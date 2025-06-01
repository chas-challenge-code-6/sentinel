# Sentinel <img src="https://github.com/chas-challenge-code-6/sentinel/blob/main/docs/Logo/Sentinel-small.png" width="40">

## Welcome... 👋

... to the Sentinel project. This project aims to be an aid to construction workers, emergency personnel or security guards. Our idea with this product is to be the extra eye that keeps track of your health and help you in critical situations.

## Application 📱  

In order to get a nice experience using your Sentinel device, you can download our amazing application [here](https://expo.dev/accounts/bexgren/projects/mobile-app/builds/9583d1d5-2333-47a6-a1c6-32672a0d3c91).  

## Getting Started❗  

git clone https://github.com/chas-challenge-code-6/sentinel.git  
git submodule update --init --recursive

## Installation/Setup

* Start by connecting the ESP32 to your computer
* Open Device management and make sure to check that the device is recognized as "Serial USB-device (COMX (X = some number between 1-10))
* Open VS Code and open the folder "Sentinel"
* Let PlatformIO run its course to load the necessities
* Go into the Sentinel folder -> Hardware-ESP32
* Select the environment "Sentinel"
* In PlatformIO management, begin by clicking "Build" and make sure no errors occur
* In PlatformIO management, continue by clicking "Upload"

### Error checking

* If the device isn't working properly, try clicking the reset button
* If it still does not work contact or send a message to one of the contributors and we will try and help.

<br>

# **Project Sentinel – Smart Workplace Sensor for High-Risk Professions**

## **Introduction**

In a world where occupational hazards remain a significant problem for many professions, innovative solutions are needed to ensure safer working conditions. Project Sentinel combines smart workplace sensors with advanced data analysis to identify and prevent potential dangers in real time. By integrating smart monitoring and alert systems, we can reduce workplace accidents and improve safety in high-risk professions.

## **Challenge**

Many professions, such as construction workers, firefighters, factory workers, and healthcare personnel, face daily occupational risks that can lead to severe injuries or life-threatening incidents. Exposure to hazardous gases, extreme noise levels, temperature fluctuations, and fall accidents can escalate quickly if risks are not detected in time.

Current safety practices are often reactive—measures are taken only after an accident has occurred. Project Sentinel shifts the focus to a proactive and data-driven safety solution that can identify and address risks before they result in incidents.

## **Solution – Smart Workplace Sensor**

Project Sentinel provides a wearable workplace sensor connected to a platform for advanced data analysis and real-time monitoring. The solution is designed to detect environmental anomalies and alert both the user and the employer to potential hazards.

### **Core Features**

✅ **Real-time Analysis** – Sensors continuously collect and analyze environmental data.  
✅ **Automatic Alerts** – Instant notifications are sent in hazardous situations.  
✅ **Smart Risk Detection** – The system analyzes historical data and identifies potential risk patterns.  
✅ **Integration with Safety Systems** – Compatible with existing workplace safety systems.  
✅ **User-Friendly Mobile App** – A clear and intuitive interface for monitoring and reporting.

## **Technology – Smart Sensors and Data Analysis**

To create a comprehensive safety solution, Project Sentinel integrates multiple advanced sensors and analysis tools:

### **Sensor Hardware**

🔍 **Gas Sensor** – Detects hazardous gases such as carbon monoxide, methane, and ammonia.  
🌡 **Temperature & Humidity Sensor** – Identifies heat stress and hypothermia risks.  
📉 **Accelerometer & Gyroscope** – Detects sudden falls and abnormal movements.  
❤️ **Pulse Sensor** – Monitors heart rate.  
📡 **LTE/4G Communication** – Ensures a stable connection even in areas without reliable Wi-Fi.

### **Data Analysis and Monitoring**

📊 **Data-Driven Safety** – The system analyzes historical data to identify dangerous trends.  
🔔 **Automatic Alarms** – Immediate alerts are triggered when hazardous conditions are detected.  
🔗 **Workplace System Integration** – Seamless connectivity with existing safety systems.

## **System Architecture**

Project Sentinel is built on a robust frontend and backend that work seamlessly together to manage data, analyze risks, and present real-time information to users.

### **Frontend System**

📱 **User-Friendly Interface:**

* Real-time display of workplace environmental data.
* Notifications and alerts for detected risks.
* Interactive dashboard for historical data and trends.
* Adjustable warning levels and sensor sensitivity settings.
* Support for both mobile and desktop applications.

### **Backend System**

☁ **Powerful and Scalable Data Processing:**

* Real-time data collection and processing from sensors.
* Analytical tools to detect and predict risks.
* Alert and notification management for users and supervisors.
* Secure data storage for long-term analysis and compliance with safety regulations.
* API for integration with external safety systems and workplace monitoring platforms.

## **Target Audience**

Project Sentinel is designed for industries where safety is a critical aspect of workplace conditions:

🏗 **Construction and Infrastructure**  
🏭 **Industrial and Manufacturing**  
🚒 **Firefighters and Emergency Services**  
🏥 **Healthcare and Emergency Medicine**  
🚛 **Transportation and Logistics**

## **Business Opportunity – An Investment in Safety**

Project Sentinel is more than a safety product—it is a strategic investment for companies looking to reduce accidents, decrease sick leave, and improve working conditions. By preventing incidents, companies can save both human and financial resources.

### **Benefits for Businesses**  

✅ **Lower Insurance Costs** 📉  
✅ **Reduced Sick Leave** 🤒  
✅ **Improved Compliance with Workplace Safety Regulations** ⚖  
✅ **Enhanced Corporate Reputation and Employer Brand** 🌟

## Documentation

🏗️  [Projectplan](docs/PROJECTPLAN.md)  
♾️  [Flowchart](docs/Flowchart/Flowchart-preview.png)  
🏢  [Architecture](docs/ARCHITECTURE.md)  
❗️  [Doxygen documentation for ESP32](https://chas-challenge-code-6.github.io/hardware-esp32/)

## Related Repositories

Links to the other repositories in this project:

📱 [Mobile-app](https://github.com/chas-challenge-code-6/mobile-app)  
📊 [Backend](https://github.com/chas-challenge-code-6/backend)  
📟 [ESP32](https://github.com/chas-challenge-code-6/hardware-esp32)

## **Summary**

Project Sentinel revolutionizes workplace safety by combining smart sensors and advanced data analysis to create a safer work environment. With real-time monitoring and predictive analytics, we can prevent accidents before they happen—ultimately saving lives.

🔹 **Innovation Meets Safety – Welcome to the Future with Project Sentinel.**

## License

This project is licensed under the MIT License.
