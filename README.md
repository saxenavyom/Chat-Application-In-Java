# Chat Application in Java

This is a simple client-server chat application built using Java Swing and Socket programming. The application allows real-time communication between a client and a server, demonstrating fundamental concepts of networking in Java.

## Features

- Real-time chat communication between client and server
- Desktop-based application with a graphical user interface (GUI) using Java Swing
- Uses TCP and UDP socket connections for communication
- Simple and intuitive design for easy chat experience

## Technologies Used

- **Programming Language:** Java
- **Libraries:** Swing for the GUI
- **Networking:** Java Socket programming (TCP/UDP)

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later
- Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or you can use the command line

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saxenavyom/Chat-Application-In-Java.git
   ```
2. Open the project in your preferred IDE or navigate to the project folder using the command line.

### Running the Application

1. **Start the Server:**
   - Run the `Server.java` file to start the server.

2. **Start the Client:**
   - Run the `Client.java` file to connect to the server. You can start multiple clients to test the chat functionality.

## How It Works

- The server listens for incoming connections from clients.
- Clients can connect to the server using a specified IP address and port.
- Once connected, clients can send messages to the server, which are then broadcasted to all connected clients.

## Project Structure

- `Server.java`: Contains the logic for the server-side operations.
- `Client.java`: Contains the logic for the client-side operations.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions or improvements.


## Contact

For any questions or inquiries, reach out to me at vyom.saxena.77@gmail.com.
