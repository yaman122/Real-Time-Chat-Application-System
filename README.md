# Real-Time-Chat-Application-System
Real-Time Chat Application System seamlessly merges TCP socket programming with interactive GUI. Designed for multiple users on different devices within the same network, it ensures secure and instant connectivity. 

Technical Specifications:
Language: Python
Libraries: Tkinter (for GUI), Socket (for networking)
Development Environment: Any Python-supported IDE (Integrated Development Environment)
Architecture: Client-Server model with multi-threading for concurrency# Real-Time Chat Application

This project implements a real-time chat application using Python and the `socket` library. The chat system supports multiple clients connecting to a central server, where they can exchange messages.

## Server

### Prerequisites
- Python 3.x

### How to Run
1. Open the terminal.
2. Navigate to the server directory.
3. Run the following command:

   ```bash
   python server.py
Usage
The server listens for incoming connections from clients.
Once a client connects, it prompts the user for a username.
The server then broadcasts messages sent by one client to all connected clients.
Client
Prerequisites
Python 3.x
Tkinter library (usually included with Python installations)
How to Run
Open a new terminal.

Navigate to the client directory.

Run the following command:

bash
Copy code
python client.py
Usage
Enter a username when prompted.
Click the "Join" button to connect to the server.
Type a message in the entry box and click "Send" to send messages to the chat.

Notes
The server and client should be run on separate machines or different terminals to simulate a real-world scenario.
Ensure that the server is running before clients attempt to connect.
Disclaimer
This project is intended for educational purposes. Use it responsibly, and ensure proper authorization before connecting to any network. The author is not responsible for any misuse or damage caused by this application.

Note: Replace `server.py`, `client.py`, `server_screenshot.png`, and `client_screenshot.png` with the actual filenames or paths used in your project.

