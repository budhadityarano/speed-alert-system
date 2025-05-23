# Speed Alert System

A simple C++ console application to monitor vehicle speed, convert between km/h and mph, and trigger an alert if the speed exceeds a user-defined threshold.

## Features
- Convert speed between km/h and mph
- Configurable speed threshold
- Console-based user interaction
- Written in standard C++ (C++17)

## How to Run
1. Clone the repository
2. Compile using: `g++ -std=c++17 -o speed_alert src/speed_alert_system.cpp`
3. Run with: `./speed_alert`

## Example
Enter speed threshold: 100
Is the threshold in km/h or mph? (k/m): k

Enter current speed: 120
Is the speed in km/h or mph? (k/m): k
ALERT: Speed exceeds threshold.
