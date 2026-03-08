## Hackthon AceHack 5.O 

## Mine Sentinel – Intelligent Underground Mining Safety & Monitoring System

The **Mine Sentinel System** is an IoT-based underground safety and monitoring solution designed to enhance miner safety and improve emergency response inside underground mines. Traditional communication systems often fail in underground environments due to the absence of GPS signals, cellular networks, and internet connectivity.

This system uses **sensor-based monitoring, LoRa communication, and relative position tracking** to detect hazardous conditions such as toxic gases, structural instability, and worker distress in real time.

The system enables continuous monitoring of miners, early detection of dangerous conditions, and rapid emergency alerts to improve rescue operations and reduce accident risks.

This solution is especially suitable for **coal mines, underground tunnels, mineral extraction sites, and hazardous industrial environments.**

## 🎬 Mine Sentinel System
![3c2bf6c7-62e9-486f-80cf-c10882f7a5bf](https://github.com/user-attachments/assets/0fc5518c-3d15-4ff9-bbfd-91f85114daa7) 
![1f68274c-5345-40a7-9902-27d6e0380736](https://github.com/user-attachments/assets/840fab59-c48d-4154-986c-41ddb682f762)
![49288800-9da3-47cb-b023-83b5603c4776](https://github.com/user-attachments/assets/014b771c-3d9c-4271-9ce5-d81056a08b73)




## Objectives

* To improve **safety monitoring inside underground mines** using IoT technology.
* To detect **hazardous gases and environmental risks** in real time.
* To monitor **structural instability or abnormal vibrations** inside mines.
* To track the **relative movement of miners where GPS is unavailable.**
* To provide **instant alerts and emergency signals** during dangerous situations.
* To design a **reliable communication system using LoRa** for underground environments.
* To assist rescue teams by providing **last known location and safety status of miners.**

## Key Features
1️⃣ Real-Time Environmental Monitoring

The system continuously monitors environmental parameters such as toxic gases and hazardous conditions using dedicated sensors.

2️⃣ Gas Detection System

Gas sensors detect harmful gases commonly found in mines such as methane and carbon monoxide, helping prevent accidents caused by gas leaks or explosions.

3️⃣ Structural Movement Detection

An IMU sensor monitors vibrations and structural movement inside the mine to detect possible collapse or instability.

4️⃣ Relative Location Tracking

Since GPS does not work underground, the system estimates the miner’s location using step-based movement tracking and path reconstruction.

5️⃣ LoRa-Based Long-Range Communication

The system uses LoRa technology to transmit data from underground workers to the surface monitoring station with low power consumption.

6️⃣ Multi-Level Risk Detection

The system classifies hazards into multiple levels such as:

Safe

Warning

Critical

This helps supervisors quickly identify dangerous situations.

7️⃣ Emergency Alert System

In emergency situations, the system automatically sends alerts to the control station for quick response.

## System Architecture

The Mine Sentinel System consists of three major modules:

Wearable Miner Safety Device

Underground Communication Node

Surface Monitoring Control Station

## Miner Safety Wearable Device

Each miner carries a wearable safety unit that continuously monitors their environment and movement.

## Components

ESP32 / Arduino Microcontroller

Gas Sensors

IMU Sensor (Accelerometer & Gyroscope)

LoRa Module

Emergency Alert Button

Battery Power Supply

## Functions

Detects harmful gases

Monitors miner movement and activity

Detects abnormal vibration or collapse risk

Sends sensor data to the communication node

Sends emergency alerts if danger is detected

## Underground Communication Node

Communication nodes act as relay stations inside the mine to transmit data between miners and the control station.

## Components

ESP32 Microcontroller

LoRa Module

Power Supply

Signal Relay Unit

## Functions

Receives data from wearable miner devices

Forwards information to the surface control panel

Maintains long-range communication inside the mine

## Surface Monitoring Control Station

The control station acts as the central monitoring system where all data is received and analyzed.

## Components

ESP32 Microcontroller

LoRa Receiver

Display Panel / Dashboard

Alarm System

## Functions

Displays real-time miner safety data

Detects gas hazards and structural risks

Shows miner status and alerts

Triggers alarms during emergencies

Provides critical information for rescue teams

## Working of the System

The Mine Sentinel system operates through coordinated communication between the miner wearable device, underground nodes, and the control station.

Step 1 – Environmental Monitoring

The wearable device continuously collects data from gas sensors and IMU sensors.

Step 2 – Data Transmission

The collected sensor data is transmitted through LoRa communication to underground communication nodes.

Step 3 – Data Relay

The communication nodes forward the received information to the surface control station.

Step 4 – Data Analysis

The control station analyzes incoming data and identifies potential hazards.

Step 5 – Alert Generation

If dangerous conditions are detected:

The system generates alerts

The alarm system is activated

The miner’s last known position is identified

## Emergency Handling

When a dangerous condition occurs:

Gas concentration exceeds safe limits

Structural vibration indicates collapse risk

A miner triggers the emergency alert button

The system immediately:

Sends an emergency signal

Displays the alert at the control station

Activates alarms

Helps rescue teams identify the affected miner's location.

## Challenges
## Underground Communication Limitations

Wireless communication in underground mines is difficult due to rock layers and physical barriers.

Power Management

Ensuring long battery life for wearable devices is a major challenge.

Sensor Accuracy

Environmental sensors must maintain accuracy in harsh mining conditions.

Hardware Reliability

Devices must operate reliably under dust, moisture, and high temperature.

## Team Name - Neo-Gen Innovotors
- Mukul
- Deepanshu
- Sahil
- Anuj
