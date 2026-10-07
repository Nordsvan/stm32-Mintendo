# Mintendo

### STM32 Multiplayer Gaming System

Mintendo is an embedded multiplayer gaming system developed as part of a university project at Umeå University.

The system consists of two STM32-based gaming devices with touchscreen displays, allowing two players to play games against each other over Wi-Fi. For Wi-fi connection Mintendo used the built in Wi-fi support on the ESP32.

The system supports two games:

* **Pong** — real-time multiplayer gameplay between two devices
* **Tic-Tac-Toe** — turn-based multiplayer gameplay over Wi-Fi

The project combines embedded programming, wireless communication, graphical interfaces and user interaction on dedicated hardware.

---
## Demo

### Pong

[Watch the Pong demo](https://youtu.be/kfqGwe1AtFI)

### Tic-Tac-Toe

[Watch the Tic-Tac-Toe demo](https://youtu.be/WI2XMizz4N4)

---

## Technologies

* STM32
* ESP32
* C/C++
* Wi-Fi
* Touchscreen
* Graphics library
* Embedded systems

---

## Team

Developed as a team of four students at Umeå University.

### My Contribution

My main contributions to the project included:

* Importing the library lvgl as the graphical base for the project.
* Creating touch screen logic and integration.
* Designing the graphical interface.

Through the project, I gained practical experience in embedded development, debugging hardware and software, wireless communication and collaborative software development.

---

## Games

### Pong

A multiplayer implementation of Pong where two STM32/ESP32 devices communicate over Wi-Fi.

Each player controls a paddle using the touchscreen, while game state and player actions are synchronized between the two devices.

### Tic-Tac-Toe

A multiplayer Tic-Tac-Toe implementation running across two connected STM32 devices.

Players interact with the game through the touchscreen, with moves communicated wirelessly between the two devices.

---

## Context

This project was developed as part of an embedded systems course at Umeå University.

The goal was to develop a complete interactive system on resource-constrained hardware, combining hardware, software, networking and user interaction.