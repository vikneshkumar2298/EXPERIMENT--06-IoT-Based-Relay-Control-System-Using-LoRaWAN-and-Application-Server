# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection

<img width="452" height="254" alt="image" src="https://github.com/user-attachments/assets/5c01eeab-9510-4aa9-8351-54c02301c4d9" />


### 2. Network Server – Recent Events

<img width="452" height="252" alt="image" src="https://github.com/user-attachments/assets/4c500e61-5f6e-49da-93ad-42e0825b5cd1" />

<img width="452" height="244" alt="image" src="https://github.com/user-attachments/assets/8138f100-142f-4197-8b60-27c295fafb2d" />


### 3. Dashboard Command Sending

<img width="452" height="229" alt="image" src="https://github.com/user-attachments/assets/4e75bd9f-e99f-4bcb-a8fa-227c632c443e" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  

<img width="452" height="240" alt="image" src="https://github.com/user-attachments/assets/d97b59be-26ad-41c7-b804-0cd4197f6233" />

### Bulb OFF → Relay OFF

<img width="452" height="239" alt="image" src="https://github.com/user-attachments/assets/4467bc2a-0901-482c-9a08-ccfef2d93c25" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
