# Smart-Home-Appliance-Monitoring-and-Control
To develop an Android application to control and monitor electrical appliances using interactive buttons.

# EXPERIMENT: SMART HOME APPLIANCE MONITORING AND CONTROL USING ANDROID STUDIO

## 1. AIM
To design and develop an Android application using Android Studio to monitor and control home appliances such as lights, fans and motors through a user-friendly graphical interface with ON/OFF control facilities.

## 2. SOFTWARE REQUIREMENTS
- Android Studio
- Java Programming Language
- XML Layout Editor
- Android Emulator or Android Mobile
- Android SDK
- Raspberry Pi (for hardware integration)
- Wi-Fi Network (for wireless communication)

## 3. THEORY
Android Studio is an Integrated Development Environment (IDE) used to develop Android applications using Java and XML.

A Smart Home Appliance Monitoring and Control System is an embedded application that enables users to monitor and control electrical appliances using an Android mobile application.

The application provides an interface to switch appliances ON or OFF and display their operating status. It can be extended to communicate with a Raspberry Pi through a Wi-Fi network for controlling physical appliances using relay circuits.

The application uses the following Android UI components:

- **TextView:** To display appliance names and operating status.
- **Button:** To control appliances using ON/OFF commands.
- **LinearLayout:** To arrange the appliance control components.
- **Switch/Button Controls:** To enable users to change appliance operating states.
- **Java Event Handling:** To process user commands and update appliance status.

The appliance control logic is based on two states:

- ON – Appliance is switched ON.
- OFF – Appliance is switched OFF.

For hardware implementation, Android sends control commands to Raspberry Pi through Wi-Fi. Raspberry Pi processes the received commands and controls the corresponding relay circuits connected to electrical appliances.

## 4. PROCEDURE
1. Open Android Studio.
2. Select New Project and choose Empty Views Activity.
3. Enter the project name as `SmartHomeControl`.
4. Select Java as the programming language.
5. Design the user interface using the XML Layout Editor.
6. Add TextViews to display appliance names such as Light, Fan and Motor.
7. Add Buttons to control each appliance.
8. Add TextViews to display the ON/OFF status of each appliance.
9. Open MainActivity.java and write the Java program to control appliance states.
10. Use setOnClickListener() to handle button-click events.
11. Initialize the appliance status as OFF.
12. Update the appliance status whenever the corresponding button is clicked.
13. Execute the application using an Android Emulator or physical Android device.
14. Click the ON/OFF buttons and verify the status changes.
15. For hardware integration, establish Wi-Fi communication between the Android application and Raspberry Pi.
16. Send appliance control commands to Raspberry Pi.
17. Use GPIO pins and relay circuits to control the connected appliances.

## 5. ALGORITHM
1. Start the application.
2. Initialize the Android user interface components.
3. Display the list of home appliances.
4. Initialize all appliance states as OFF.
5. Select the appliance to be controlled.
6. Click the corresponding ON/OFF button.
7. Identify the selected appliance.
8. Change the appliance state.
9. Update the displayed appliance status.
10. For hardware integration, send the corresponding command to Raspberry Pi through Wi-Fi.
11. Raspberry Pi receives and processes the command.
12. Activate or deactivate the corresponding relay circuit.
13. Repeat the process for other appliances.
14. Stop.

## 6. EXPECTED OUTPUT

**SMART HOME APPLIANCE MONITORING AND CONTROL SYSTEM**

## 7. APPLICATION FEATURES
- User-friendly graphical interface.
- Monitor the operating status of home appliances.
- Control multiple appliances independently.
- Switch appliances ON and OFF.
- Display real-time status changes within the application.
- Support Wi-Fi-based communication with Raspberry Pi through hardware integration.
- Control electrical appliances using GPIO interfaced relay circuits.
- Provide a foundation for smart home automation.

## 8. RESULT
Thus, the Smart Home Appliance Monitoring and Control Android application was successfully designed and developed using Android Studio with Java and XML. The application allows users to monitor appliance status and control the ON/OFF operations through an interactive graphical interface.

## 9. CONCLUSION
The experiment provides practical knowledge of Android application development, XML-based user interface design, Java event handling, embedded system integration, wireless communication and home automation using Android and Raspberry Pi.
