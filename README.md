# Smart Pill Container

A Raspberry Pi-based medication reminder system that provides scheduled medication alerts through an OLED display and uses a custom image-based hand-to-mouth detection approach to monitor medication intake.

## Overview

The Smart Pill Container is designed to assist users in following their medication schedules. The system runs on a Raspberry Pi and uses an OLED display to show the medication name at the scheduled time.

A Raspberry Pi camera is also used to capture image frames for a lightweight hand-to-mouth detection algorithm. The system includes fail-safe handling when the expected intake gesture is not detected.

## Key Features

* Python-based medication scheduling
* Scheduled medication alerts
* OLED display for medication information
* Raspberry Pi camera integration
* Custom image-based hand-to-mouth detection
* Fail-safe handling for unsuccessful detection
* Patient and medication data management
* SQLite-based local data storage

## Technologies Used

* **Python**
* **Raspberry Pi**
* **SH1106 OLED Display**
* **Raspberry Pi Camera**
* **SQLite**
* **HTML**
* **Image Processing**

## System Workflow

1. Medication and patient information are stored in the system.
2. The scheduling system checks upcoming medication times.
3. At the scheduled time, the medication name is displayed on the OLED screen.
4. The Raspberry Pi camera captures image frames.
5. The custom image-based detection logic analyzes the captured frames for a hand-to-mouth gesture.
6. The system determines whether the expected intake gesture has been detected.
7. Fail-safe handling is applied when the detection is unsuccessful.

## Results

The system was evaluated using real-world test cases and achieved:

* **100% medication display accuracy**
* **87.8% intake detection accuracy**
* Fail-safe handling for unsuccessful detection

## Hardware

* Raspberry Pi
* SH1106 OLED Display (128×64)
* Raspberry Pi Camera
* Supporting electronic components

## Project Structure

The repository contains the Python modules for medication scheduling, OLED display control, camera-based detection, database management, and system testing.

## Purpose

The project demonstrates the use of Python, Raspberry Pi hardware integration, scheduling logic, OLED display control, image-based detection, and local database management to develop an assistive medication reminder system.

