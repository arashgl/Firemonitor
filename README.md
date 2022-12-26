# Firemonitor

Welcome to Firemonitor, an IoT-based solution for monitoring and protecting buildings from fires. With Firemonitor, building owners and managers can stay informed about the state of their fire alarm systems, receive real-time alerts in case of any issues, and take timely action to ensure the safety and functionality of their buildings.

## Features

* Real-time monitoring of the fire alarm system and related building systems
* Immediate alerts in case of any issues or potential fires
* Integration with smart devices and building systems for seamless monitoring and control
* User-friendly interface for accessing and interpreting data and receiving alerts


## Technical Overview

This project utilizes the following technologies:

* Node.js and the Express.js framework: Node.js is a popular runtime environment for building scalable, high-performance web applications, and Express.js is a fast, minimalist framework for building web servers and APIs on top of Node.js. We chose these technologies for their speed, efficiency, and ability to handle large amounts of data.
* Socket.IO: Socket.IO is a library for real-time, bidirectional communication between web clients and servers. It allows us to create real-time alerts and a real-time chat application for operators within the system.
* Microservices: To ensure the reliability and scalability of the system, we have implemented a microservice architecture, with separate services handling different aspects of the system. This includes a service to receive and hold messages from the IoT devices until they can be consumed by the server.

## Key Features

Some of the key features of this project include:

* Real-time alerts: Using Socket.IO, we are able to provide real-time alerts to building owners and managers in case of any issues or potential fires.
* Real-time chat: Operators can use the real-time chat application to communicate with each other and coordinate their efforts to resolve any issues.
* Scalable architecture: The microservice architecture allows us to easily scale the system to handle large amounts of data and traffic.
* Reliable message handling: The message-handling microservice ensures that all messages from the IoT devices are received and processed, even if the main server is experiencing high levels of traffic or other issues.
