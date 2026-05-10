# Client-Server Chat Room System

A multithreaded client-server chat room system developed in C using Operating System concepts such as shared memory, semaphores, pthreads, signals, and file handling.

This project demonstrates inter-process communication and synchronization mechanisms through a real-time chat application.

## Project Overview

The project implements a chat room where multiple clients can communicate through a centralized server.

The server:
- Manages connected users
- Handles synchronization
- Maintains global message tracking
- Stores chat messages in files

The clients:
- Send messages using threads
- Read new messages continuously
- Synchronize communication using semaphores and shared memory

## Features

- Multi-client Chat System
- Client-Server Architecture
- Shared Memory Communication
- Semaphore-Based Synchronization
- Multithreading with Pthreads
- File-Based Message Storage
- Real-Time Message Reading & Writing
- Signal Handling

## Technologies Used

- C Programming
- Linux Operating System
- Shared Memory
- Semaphores
- Pthreads
- Signals
- File I/O

## Project Structure
Client-Server-Chat-System/
│
├── server.c
├── client.c
└── README.md

## Compilation

Compile the server:

gcc server.c -o server -pthread

Compile the client:

gcc client.c -o client -pthread

## Running the Project

Run the server first:

./server

Run clients in separate terminals:

./client

## Operating System Concepts Used

* Inter-Process Communication (IPC)
* Shared Memory
* Process Synchronization
* Semaphores
* Multithreading
* Signal Handling
* Concurrent Programming

## Learning Outcomes

* Understanding synchronization techniques
* Implementing IPC mechanisms
* Managing concurrent client communication
* Working with threads and signals
* Developing real-time systems in Linux

## Author

Azan Shah

## License

This project is developed for educational and academic purposes.
