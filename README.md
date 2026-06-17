# Bluetooth Based Home Automation System Using LPC2148

Abstract

The Bluetooth Based Home Automation System is an embedded system project designed to control household appliances wirelessly using a smartphone. The system uses the LPC2148 ARM7 microcontroller and a Bluetooth module to receive commands from a mobile device. Based on the received commands, appliances such as LEDs and fans can be turned ON or OFF. An LCD display provides real-time status updates of the connected devices.

Objective

To develop a wireless home automation system that enables users to control electrical appliances remotely using Bluetooth communication and a smartphone.

Introduction

Home automation improves convenience, energy efficiency, and user comfort by enabling remote control of household devices. In this project, Bluetooth technology is used for short-range wireless communication between a smartphone and the LPC2148 microcontroller. The microcontroller processes the received commands and controls the connected appliances accordingly.

Hardware Requirements

* LPC2148 ARM7 Microcontroller
* HC-05/HC-06 Bluetooth Module
* 16x2 LCD Display
* LED
* DC Fan
* Power Supply Circuit
* Connecting Wires

Software Requirements

* Embedded C
* Keil µVision IDE
* Flash Magic
* Proteus (Optional)

Working Principle

1. The smartphone sends commands through Bluetooth.
2. The HC-05 Bluetooth module receives the commands.
3. LPC2148 reads the received data through UART communication.
4. Based on the command:

   * '1' → LED ON
   * '2' → FAN ON
   * '3' → LED OFF
   * '4' → FAN OFF
5. The LCD displays the current status of the appliances.
6. The appliance state is updated immediately.

UART Communication

* Baud Rate: 9600 bps
* Data Bits: 8
* Stop Bits: 1
* Parity: None

Features

* Wireless appliance control
* User-friendly operation
* Real-time LCD status display
* Low power consumption
* Low-cost implementation
* Easy installation and maintenance

Advantages

* Reduces manual effort
* Increases user convenience
* Energy-efficient operation
* Secure short-range communication
* Cost-effective home automation solution

Applications

* Smart Homes
* Offices
* Laboratories
* Industrial Monitoring
* Smart Energy Management Systems

Future Enhancements

* Wi-Fi and IoT integration
* Voice control using Google Assistant
* Mobile application with GUI
* Sensor-based automatic control
* Cloud monitoring and control

Conclusion

The Bluetooth Based Home Automation System successfully demonstrates wireless control of household appliances using the LPC2148 microcontroller and Bluetooth communication. The project provides a simple, reliable, and cost-effective solution for smart home applications while enhancing user convenience and automation.
