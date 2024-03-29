﻿# Client-Server RSA-3DES

Welcome to the Client-Server RSA-3DES project! This project demonstrates a client-server communication system using the RSA encryption algorithm for key exchange and the 3DES encryption algorithm for secure data transmission. The client and server applications are implemented in Java.

## Getting Started

To use the Client-Server RSA-3DES project, you have the following options:

1. **Using an Integrated Development Environment (IDE):**

   - Open your preferred Java IDE (e.g., Eclipse, IntelliJ IDEA, or NetBeans).
   - Import the cloned project into the IDE.
   - Build the project to ensure all dependencies are resolved.
   - Locate the `Server.java` file in the `src/pkgfinal/project/security` directory and run it as the main program.
   - Similarly, locate the `Client.java` file in the same directory and run it as the main program.

2. **Using Java Development Tools:**

   - Install a Java development tool such as BlueJ or jGRASP.
   - Open the tool and import the cloned project.
   - Locate the `Server.java` file in the `src/pkgfinal/project/security` directory and compile/run it within the tool.
   - Similarly, locate the `Client.java` file in the same directory and compile/run it within the tool.

Choose the option that suits your preference and development environment. Using an IDE or development tools can provide a more convenient and visually interactive way to work with the project compared to the command line. They offer features such as code completion, debugging, and integrated project management.

Please make sure you have Java Development Kit (JDK) installed on your machine. The project source files are located in the `src/pkgfinal//project/security` directory.

## How It Works

The Client-Server RSA-3DES project follows the following steps for secure communication:

1. The server generates RSA key pairs (public and private keys) and sends the public key to the client.
2. The client generates a 3DES session key and encrypts it using the server's public key.
3. The encrypted session key is sent back to the server.
4. The server decrypts the session key using its private RSA key.
5. The client and server can now securely communicate using the 3DES algorithm with the shared session key.
6. The client can send messages to the server, which are encrypted using 3DES and decrypted by the server using the shared session key.
7. Similarly, the server can send messages to the client, which are encrypted using 3DES and decrypted by the client using the shared session key.

## Usage

Once you have successfully compiled and run the server and client applications, you can start sending messages securely between them. The messages will be encrypted using the 3DES algorithm for secure transmission.

To send a message from the client to the server, enter the message in the client's command line interface and press Enter. The message will be encrypted and sent to the server.

To send a message from the server to the client, enter the message in the server's command line interface and press Enter. The message will be encrypted and sent to the client.

The encrypted messages will be decrypted and displayed on the receiving side.

Please note that the server and client applications must be running simultaneously for successful communication.
