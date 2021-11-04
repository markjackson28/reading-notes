
# Class 13

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*What does it mean that web sockets are bidirectional? Why is this useful?*
- A socket that can send and receive data. This can be useful to minimize the amount of sockets.

*Does socket.io use HTTP? Why?*
- Yes, but only as a fallback if the WebSocket connection is not established.

*What happens when a client emits an event?*
- The emit looks for the the listener on the server side.

*What happens when a server emits an event?*
- The server emit looks for the listener on the client side.

*What happens if a client “misses” an event?*
- Probably an error.

*How can we mitigate this?*
- Add ‘Acknowledgements’ to the events.

*Terms*
- Socket: ‘A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to.’ [Ref.](https://docs.oracle.com/javase/tutorial/networking/sockets/definition.html)
- Web Socket: ‘a computer communications protocol, providing full-duplex communication channels over a single TCP connection.’ [Ref.](https://en.wikipedia.org/wiki/WebSocket)
- Socket.io: ‘Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.’ [Ref.](https://socket.io/docs/v4/)
- Client: The machine/person making the request.
- Server: Management center for networks.
- OSI Model: ‘a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.’ [Ref.](https://en.wikipedia.org/wiki/OSI_model) 
- TCP Model: ‘the set of communications protocols used in the Internet and similar computer networks.' [Ref.](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- TCP: ‘Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network.’ [Ref.](https://www.fortinet.com/resources/cyberglossary/tcp-ip)
- UDP: ‘User datagram protocol (UDP) operates on top of the Internet Protocol (IP) to transmit datagrams over a network. UDP does not require the source and destination to establish a three-way handshake before transmission takes place. Additionally, there is no need for an end-to-end connection.’ [Ref.](https://www.imperva.com/learn/ddos/udp-user-datagram-protocol/)
- Packets: small amounts of data put into ‘packets’.

*Which 3 things had you heard about previously and now have better clarity on?*
- Not much.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*
- Socket.io, events, and, the flow of socket.io.

*What are you most excited about trying to implement or see how it works?*
- Socket.io.

*Preparation Material*
- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms and Namespaces](https://socket.io/docs/rooms-and-namespaces/)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/emit-cheatsheet/)
