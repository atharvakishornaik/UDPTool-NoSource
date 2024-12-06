# UDP Tool
The UDP Tool is a lightweight application for testing and debugging
UDP-based communication. It allows users to send and receive
messages over the UDP protocol. Designed with simplicity in mind,
this tool is ideal for developers and network engineers who need to
test or debug UDP communication in real-time.

## Features
- Send Messages: Send UDP messages to a specific IP and port. Ports are set between 49152 and 65535.
- Receive Messages: Listen for incoming UDP messages on a
specified local port.
- Broadcast Support: Send UDP messages to all devices on the same
network.
- Dynamic Port Update: Change the local port dynamically without
restarting the application.
- Real-Time Logging: View sent and received messages, along with
metadata like sender/receiver IP and port.
- Customizable Ports: Specify both local and remote ports for precise
communication contro

## How to Use
### 1. Setup
 - Download the application and ensure all required dependencies
are installed on your system.
 - Launch the `UDPTool.exe`.
### 2. Configuring Ports
 - In the "Lokaler Port" field, specify the local port for sending and
listening.
 - In the "Remote Port" field, specify the destination port for sending
messages.
### 3. Sending Messages
 - Enter the target IP address in the "Remote IP" field.
 - Type your message in the "Sendedaten" field.
 - Click the "An Remote IP senden" button to send the message.
### 4. Receiving Messages
 - Ensure the "Lokaler Port" field is correctly set to the port you want
to listen on.
 - Incoming messages will automatically appear in the log display.
### 5. Broadcasting
 - Click the "Broadcasten" button to send the message to all devices
on the network.
 - Ensure your local network allows broadcasting

## Known Issues
1. Port Binding Errors:
 - Ensure the local port is not already in use by another application.
 - The application will notify you if binding fails.
2. Broadcast Limitations:
 - Broadcasting may be restricted by your network configuration or
firewall settings.
3. Firewall Blocking:
 - Ensure the application is allowed through the system firewall.

## Example Use Case
### Testing Two Instances on the Same Machine
1. Open two instances of UDPTool.exe
2. Configure:
    - Instance 1:
        - Local Port: 50050
        - Remote Port: 50051
        - Remote IP: 127.0.0.1
    - Instance 2:
        - Local Port: 50051
        - Remote Port: 50050
        - Remote IP: 127.0.0.1
3. Send a message from Instance 1 to Instance 2 and verify that the
message is received.
4. Send a response from Instance 2 to Instance 1 and cross verify.

## Contact
For questions or support, reach out to:
- Email: naik.atharva113@gmail.com