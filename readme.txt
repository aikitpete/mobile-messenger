# mobile-messenger

A BlackBerry messenger application written in Java.

## Overview
This project is a prototype messaging application originally built for BlackBerry devices.
It demonstrates mobile messaging concepts on constrained mobile platforms, including UI interaction, messaging workflows, and device-specific runtime configuration.

The project was developed as an experimental mobile application rather than a production-ready product.

## Running the Application

To start the application in the BlackBerry simulator environment, use the following command:

```
fledge.exe /handheld=8520 /session=8520 /app-param=DisableRegistration /app-param=JvmAlxConfigFile:8520.xml /data-port=0x4d44 /data-port=0x4d4e /pin=0x2100000A /app=Jvm.dll
```

This command launches the simulator for the BlackBerry 8520 device with the appropriate runtime configuration and application parameters.

## Deviations From the Original Design

The implemented prototype differs from the original design in the following ways:

- Instant Messaging (IM) and SMS support were not implemented.
- Voice recognition support is missing.
- Some hardware button functions were modified compared to the initial design.

## Notes

This repository reflects an early mobile development project focused on experimentation and learning within the BlackBerry Java ecosystem. While the platform itself is now obsolete, the project demonstrates early work with:

- Mobile application architecture
- Messaging workflows
- Device-specific runtime configuration
- UI interaction on constrained devices
