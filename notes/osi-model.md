# Open Systems Interconnection Model

- 7-layer architecture with each layer having specific functionality to perform.
- Theoretical.
- All these 7 layers work _collaboratively_ to transmit the data from one person to another across the globe.
- Specific protocols and technologies are often _designed_ based on the principles outlined in the OSI model to facilitate efficient data transmission and networking operations.

## How it works

- First data travels down through _7 layers from the sender’s_ end and then climbs back 7 layers on the _receiver’s end_.

## Layers

The OSI model consists of seven abstraction layers arranged in a top-down order:

1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

## Architecture

| Layer No | Layer Name         | Responsibility                                                                 | Information Form (Data Unit)   | Device or Protocol           |
| -------- | ------------------ | ------------------------------------------------------------------------------ | ------------------------------ | ---------------------------- |
| 7        | Application Layer  | Helps in identifying the client and synchronizing communication.               | Message                        | SMTP                         |
| 6        | Presentation Layer | Data from the application layer is extracted and manipulated for transmission. | Message                        | JPEG, MPEG, GIF              |
| 5        | Session Layer      | Establishes connection, maintenance, ensures authentication, and security.     | Message (or encrypted message) | Gateway                      |
| 4        | Transport Layer    | Takes service from Network Layer and provides it to the Application Layer.     | Segment                        | Firewall                     |
| 3        | Network Layer      | Transmission of data between hosts located in different networks.              | Packet                         | Router                       |
| 2        | Data Link Layer    | Node-to-node delivery of message.                                              | Frame                          | Switch, Bridge               |
| 1        | Physical Layer     | Establishing physical connections between devices.                             | Bits                           | Hub, Repeater, Modem, Cables |
