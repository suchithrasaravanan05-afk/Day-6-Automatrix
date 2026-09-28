# Day 6: Web-Controlled LED

This project connects an ESP32 to WiFi and hosts a simple web page with links to turn the built-in LED on and off.

## Hardware

- ESP32 DevKit v1 with built-in LED on GPIO 2

No additional components are required.

## WiFi Settings

- Network: `Wokwi-GUEST`
- Password: leave blank

## Wokwi Simulation

[Run the simulation](https://wokwi.com/projects/476331638463886337)

## How to use

1. Start the Wokwi simulation.
2. Open the Serial Monitor and wait for the WiFi connection.
3. Copy the IP address printed in the Serial Monitor.
4. Open the address in a browser that can reach the Wokwi simulation.
5. Use the **LED ON** and **LED OFF** links.

The web server listens on port 80. The LED is controlled through the `/ledon` and `/ledoff` routes.
