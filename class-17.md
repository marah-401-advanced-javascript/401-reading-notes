# TCP servers

### Events Queues

- Events Queues is build around the use of events, the EventEmitter constructor emits events as instances
- it is also a great way to handle async events, functions can be registered as event listeners. 
- multiple services can be connected by various protocols using proprietary APIs. this is done by using a queue.

### Internet Protocol

- Internet Protocol Suite The Internet Protocol Suite is the conceptual model for the protocols used by the internet. 
- It is often referred to as TCP/IP because the IP and TCP were the original protocols in the suite. 
- The Internet Protocol Suite is described using four layers - Link, Internet, Transport, and Application. Web developers often reference the Internet Protocol Suite model when discussing network communication and data exchange.

### TCP "Transmission Control Protocol"

 - is widely used by application layer protocols in the Internet Protocol Suite. TCP creates a two way communication between two hosts and provides reliable, ordered, and error checked byte streams between the applications. 
 - TCP data transfers manage network congestion and use flow control to limit the rate a sender transfers data to guarantee reliable delivery. 
 - Each IP packet between the hosts carries a single TCP Segment. 
 - A TCP segment is made up of header and data sections.

### How does a TCP server work?

- The Internet works by using a protocol called TCP/IP, or Transmission Control Protocol/Internet Protocol. 
- In base terms, TCP/IP allows one computer to talk to another computer via the Internet through compiling packets of data and sending them to right location.
