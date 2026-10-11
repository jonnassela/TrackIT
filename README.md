# 📍 TrackIt – Real-Time GPS Tracking System

**TrackIt** is an IoT-based, real-time GPS tracking platform designed to monitor vehicle locations and provide estimated arrival times (ETAs) through an interactive web application.

The project combines GPS technology, ESP32 microcontrollers, cloud communication, and web development to create a practical solution for transportation monitoring and location tracking.

## 🚀 Project Overview

Uncertainty in transportation is a common problem. Passengers often wait for buses without knowing their exact locations or arrival times, while logistics companies face challenges monitoring vehicles and deliveries.

**TrackIt aims to solve these problems by providing real-time location visibility and estimated arrival times.**

Although the initial prototype focuses on public transportation, the system is designed with potential applications in delivery services, taxi operations, school transportation, and logistics.

## ✨ Key Features

- **Real-Time GPS Tracking:** Monitor vehicle locations using GPS coordinates collected from physical tracking hardware.
- **Interactive Map:** Visualize vehicle positions on a map through a web interface.
- **Estimated Arrival Times (ETA):** Provide estimated arrival times for designated stops.
- **IoT Integration:** Utilize ESP32 microcontrollers and GPS modules to collect geographic coordinates.
- **Cloud-Based Communication:** Transmit location data from tracking devices to a server for processing and visualization.
- **Scalable Concept:** Extend the system to support different vehicle types and transportation services.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| ESP32 | IoT microcontroller for GPS tracking |
| GPS Module | Collecting geographic coordinates |
| Arduino IDE | Programming the ESP32 |
| Cloud Server | Receiving and processing location data |
| Google Maps API | Map visualization and traffic-aware ETA functionality |
| Web Technologies | Building the user interface |

## 🏗️ System Architecture

TrackIt follows an IoT-to-cloud architecture, connecting physical tracking devices with a web application.

```text
       GPS Satellites
              |
              v
        GPS Module
              |
              v
        ESP32 Device
              |
              | Network Connection
              v
         Cloud Server
              |
              | Location Processing
              v
        Web Application
              |
              v
    Interactive Google Maps
       + Live Vehicle Locations
       + Estimated Arrival Times
```

### How It Works

1. **Location Collection:** A GPS module receives satellite signals and determines the vehicle's geographic coordinates.
2. **Data Transmission:** The ESP32 reads the GPS data and sends it to the cloud server through a network connection.
3. **Data Processing:** The server receives and processes location information.
4. **Map Visualization:** The web application displays vehicle positions on an interactive map.
5. **ETA Calculation:** Location information and Google Maps services are used to estimate arrival times at designated stops.

## 🎯 Project Objectives

The primary objectives of TrackIt are to:

- Reduce uncertainty associated with public transportation.
- Improve accessibility to real-time vehicle information.
- Demonstrate the integration of IoT hardware and cloud-based systems.
- Provide an intuitive interface for monitoring transportation.
- Explore opportunities for smarter and more efficient mobility solutions.

## 🌍 Potential Applications

TrackIt can be adapted for several use cases:

- **Public Transportation:** Tracking buses and informing passengers about arrival times.
- **Delivery Services:** Monitoring delivery vehicles and estimating delivery times.
- **School Transportation:** Providing visibility into school bus locations.
- **Taxi Services:** Enabling live vehicle monitoring.
- **Logistics:** Tracking fleet movements and improving transportation coordination.

## 🔮 Future Improvements

The following enhancements are proposed for future development:

- **Route Optimization:** Suggest more efficient routes using real-time traffic information.
- **Carbon Emission Monitoring:** Integrate additional sensors to monitor vehicle emissions.
- **Advanced Fleet Management:** Support multiple vehicles, routes, and tracking devices.
- **Notifications:** Inform users about approaching vehicles, delays, and route changes.
- **Mobile Accessibility:** Extend the platform with a dedicated mobile application.

## 🎓 Academic Project

TrackIt was developed as a Computer Science and Technology capstone project at **South East European University (SEEU)**.

The project demonstrates the practical application of concepts from:

- Internet of Things (IoT)
- Web Development
- Cloud Computing
- GPS and Location-Based Services
- Real-Time Data Processing
- Software System Architecture

The project was also presented at a hackathon in May 2026.

## 👩‍💻 Development Team

Developed by **IT Girls**:

- Jona Sela
- Era Emurli
- Drinka

## 📌 Project Status

**Academic Prototype**

TrackIt was developed as a proof of concept demonstrating how IoT devices, cloud services, and web technologies can be integrated into a real-time vehicle tracking solution.

---

**TrackIt — Making transportation more predictable, one location update at a time.**
