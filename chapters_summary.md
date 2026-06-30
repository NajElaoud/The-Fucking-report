# Chapters Summary

## Chapter 1 — General Project Context

- **Main objective:** Introduce the academic and industrial context of the graduation project and explain the origin, purpose, and scope of the IOBOX platform.
- **Key topics:** The academic institution ISIMM, the host company Be Wireless Solutions, the company’s IoT activities, the industrial problem addressed, and the project’s goals and development methodology.
- **Important details:** The chapter explains how repeated hardware-specific firmware development created maintenance and reuse challenges, leading to the idea of a modular and configurable platform. It also presents the V-model as the development approach used to structure requirements, design, implementation, and validation.
- **Conclusion:** The chapter establishes the motivation for the project and defines the strategic and technical foundation on which the rest of the work is built.

## Chapter 2 — General Concept and System Components

- **Main objective:** Present the technical environment of the IOBOX platform by describing its architecture, hardware resources, and communication capabilities.
- **Key topics:** The overall concept of the platform, its role as an industrial I/O and data acquisition system, the STM32G474 microcontroller, supporting peripherals, sensors, and communication interfaces such as CAN, LIN, RS485, USB, I2C, and SPI.
- **Important details:** The chapter highlights the modular hardware architecture and details the main components used for analog and digital I/O, signal acquisition, sensor interfacing, and industrial communication. It also emphasizes the choice of the STM32G474 for its processing power and rich peripheral set.
- **Conclusion:** This chapter shows how the platform’s hardware foundation was selected and organized to meet the requirements of flexible industrial deployment and reliable data handling.

## Chapter 3 — Design and Practical Implementation

- **Main objective:** Describe how the IOBOX concept was transformed into a functional embedded firmware architecture through layered design and practical implementation.
- **Key topics:** The four-layer software architecture, BSP drivers, manager modules, filtering functions, Modbus RTU handling, EEPROM storage, and application-level task management.
- **Important details:** The chapter explains how the firmware is structured to separate hardware-specific code from higher-level logic, how feature macros enable selective compilation, and how sensor managers, communication managers, and filtering modules were implemented. It also presents the practical approach used to acquire, process, and store data reliably.
- **Conclusion:** The chapter demonstrates that the platform was not only designed conceptually but also implemented in a modular and scalable way, making it suitable for real industrial use and future extension.
