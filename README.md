# Realtime-Chat-App

A real-time chat application built with **Spring Boot**, **WebSocket**, **STOMP**, **SockJS**, and **Thymeleaf**.

## Features

- Real-time messaging using WebSocket
- STOMP protocol for broadcasting
- SockJS fallback support
- Simple Bootstrap UI
- Browser-based group chat

## Technologies Used

- Java + Spring Boot
- Spring WebSocket + STOMP
- SockJS
- Thymeleaf
- Bootstrap


## Update your `application.properties` with DB details:

```properties
implementation 'org.springframework.boot:spring-boot-starter-websocket'
implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
implementation 'org.webjars:sockjs-client:1.5.1'
implementation 'org.webjars:stomp-websocket:2.3.3'
```


## Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/Sameer07x19/chatapp.git <br/>
cd chatapp
```

### 2. Run the app

```bash
./gradlew bootRun
```

Then open: [http://localhost:8080](http://localhost:8080)

---

## License

This project is open source and free to use.

