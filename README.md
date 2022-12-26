# Custom Engine Control

This project try to build a custom engine control as flexible as possible, based on STM32 chip series run on RTOS like ChibiOS/RT or FreeRTOS.

## Overview
- Based on STM32F0/F1 series and H11L1 Schmitt Trigger to monitor engine process in real-time and controlling using IRF5xx FET series.
- Provide Serial TTL to USB port for easy realtime monitoring and more custom settings.
- Reading both TPS and Crank tooth for controlling a pair Injectors and a pair Ignition Coils.
- The design currently in very early stage and not for end user usage.

![images](images/functionality.png?raw=true)

## Crankshaft Position Sensor Alternative

Using Photo Interrupter Sensor and Encoder Wheel with one tooth missing as counter reset.

![images](images/pikup_alt.png?raw=true)