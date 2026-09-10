## 6-DOF Manipulator – Engineering Thesis

<p align="center">
  <img src="img/Ramie.png" alt="6-DOF Manipulator" width="500">
</p>

### Project description

Design and construction of an anthropomorphic robotic manipulator with six degrees of freedom.

The project included development of the kinematic model, mechanical structure, custom control electronics, embedded software and validation of the complete prototype.

I developed the forward and inverse kinematics, mechanical design requirements, control electronics and motion-control software. The finished prototype was also tested in terms of repeatability, positioning accuracy and motion quality.

### Technologies

`ESP32` `C/C++` `Forward kinematics` `Inverse kinematics` `Stepper motors` `DRV8825` `PCB design` `CAD` `3D printing` `Prototype testing`

### Status 🟢 Completed prototype

---

## Hot_dog – Quadruped Robot

<p align="center">
  <img src="img/Hot_dog.jpg" alt="Hot_dog Quadruped Robot" width="500">
</p>

### Project description

A quadruped robotic platform currently being developed as part of my master's thesis.

The project focuses on the design of a lightweight walking robot with independently controlled legs and a custom parallel leg mechanism.

Current development includes mechanical design, inverse kinematics, servo control and validation of individual leg prototypes before integration into a complete four-legged platform.

The software calculates the required joint positions from Cartesian target coordinates and controls the servos responsible for reproducing the calculated leg trajectory.

### Technologies

`ESP32` `C/C++` `Inverse kinematics` `Servo control` `Robotics` `Parallel mechanisms` `CAD` `3D printing` `Mechanical prototyping`

### Status 🟡 Active development

A functional leg prototype and the first full-body mechanical prototype have been developed.
Current work focuses on multi-leg coordination, gait generation and further mechanical refinement.

---

## Solarbank – Solar Power Bank

<p align="center">
  <img src="img/Solarbank.png" alt="Solarbank PCB" width="500">
</p>

### Project description

A solar-powered power bank combining photovoltaic energy harvesting, battery charging, power conversion and embedded control on a custom PCB.

The system is designed around an STM32 microcontroller that supervises the power-management process, including photovoltaic input monitoring, battery state estimation and control of charging parameters.

The project also includes dedicated power-conversion stages for solar input and regulated USB output.

One of the main development goals is implementation of microcontroller-assisted MPPT control in order to improve the utilization of the connected photovoltaic panel.

### Technologies

`STM32U031` `C/C++` `STM32CubeMX` `Power electronics` `MPPT` `Li-Ion battery` `Battery management` `DC/DC converters` `KiCad` `Custom PCB`

### Status 🟡 Active development

The schematic and PCB layout have been developed and refined through several design iterations.
Firmware development and hardware validation are currently in progress.

---

## Clickfy – BLE Multimedia Remote

<p align="center">
  <img src="img/Clickfy.png" alt="Clickfy BLE Multimedia Remote" width="500">
</p>

### Project description

A compact keychain-sized multimedia remote based on the ESP32-C3 and Bluetooth Low Energy HID.

The device provides dedicated controls for basic media functions such as play/pause, next track and previous track.

I designed the custom PCB, selected the electronic components and developed the firmware responsible for BLE communication, battery monitoring and low-power operation.

A major development goal has been reducing wake-up and reconnection time while maintaining low power consumption.

### Technologies

`ESP32-C3` `C/C++` `ESP-IDF` `Bluetooth Low Energy` `BLE HID` `Li-Po battery` `ADC battery monitoring` `PCB design` `Low-power operation`

### Status 🟡 Working prototype / firmware development

A complete working prototype has been built.
Current development focuses on power optimization and reducing BLE reconnection time.

---

## S.M.U. – RLC Component Meter

<p align="center">
  <img src="img/smu.jpg" alt="S.M.U. RLC Component Meter" width="500">
</p>

### Project description

S.M.U. is a custom electronic meter designed for measuring resistance, capacitance and inductance.

Different measurement methods are used depending on the selected component type.

Resistance is determined using voltage-divider measurements with reference resistors.

Capacitance is measured using the RC time constant.

Inductance is measured by exciting an LC circuit and analyzing its oscillation frequency.

I developed the measurement algorithms, designed the PCB, prepared the firmware and designed the enclosure of the device.

### Technologies

`Raspberry Pi Pico` `C/C++` `ADC` `Comparator` `RC measurements` `LC resonance` `Analog electronics` `PCB design` `Measurements` `3D printing`

### Status 🟢 Completed prototype

---

## SmartRoom – MQTT Room Automation System

<p align="center">
  <img src="img/SmartRoom.jpg" alt="SmartRoom Automation System" width="500">
</p>

### Project description

A modular room automation system based on network-connected embedded controllers.

The system is designed around ESP32 devices communicating through MQTT with a local broker.

The first implemented module controls addressable LED strips installed in different parts of the room. Individual lighting zones can be controlled independently, including brightness, color and lighting effects.

The firmware also includes automatic Wi-Fi and MQTT reconnection and publishes device availability information.

The project is designed as a foundation for future integration with environmental sensors, additional actuators and the EVA voice-assistant system.

### Technologies

`ESP32` `C++` `MQTT` `Wi-Fi` `PlatformIO` `Addressable LEDs` `IoT` `Home automation` `CAD` `3D printing`

### Status 🟡 Active development

The first lighting controller is functional and communicates with a local MQTT broker.
Further SmartRoom modules are planned.

---

## ESP32 Solar Weather Station

<p align="center">
  <img src="img/stacja.jpg" alt="ESP32 Solar Weather Station" width="500">
</p>

### Project description

An autonomous environmental monitoring station powered by a battery and photovoltaic panel.

The station collects environmental measurements and sends them wirelessly to a receiver, where the results can be presented through a local web interface.

The project combines sensor integration, wireless communication and low-power operation.

I designed the electronics using commercial modules and developed the software responsible for collecting, transmitting and displaying measurement data.

### Technologies

`ESP32` `ESP-NOW` `BME280` `Environmental sensors` `Solar power supply` `Li-Ion` `WebServer` `Low-power operation`

### Status 🟢 Completed prototype

---

# Additional Projects

The projects below were smaller prototypes, experiments or earlier engineering exercises that contributed to the development of my practical electronics and mechatronics skills.

---

## MC34063 Boost Converter

<p align="center">
  <img src="img/Przetwornica.jpg" alt="MC34063 Boost Converter" width="450">
</p>

Educational prototype of a custom boost converter based on the MC34063 integrated circuit.

The project focused on understanding switching converter operation, component selection, efficiency and the practical limitations of older power-converter architectures.

`MC34063` `Power electronics` `Switching converters` `Measurements` `Prototyping`

**Status:** 🟢 Completed prototype

---

## Electronic Measuring Scale

<p align="center">
  <img src="img/waga.jpg" alt="Electronic Measuring Scale" width="450">
</p>

Electronic scale based on a strain-gauge load cell and measurement electronics.

The project included signal acquisition, conversion of sensor readings into mass values, basic calibration and stability testing.

`Strain gauge` `ADC` `Analog measurements` `Calibration` `Signal filtering` `C/C++`

**Status:** 🟢 Completed prototype

---

## Scrapper – Voice Mini AI Assistant

<p align="center">
  <img src="img/Scrapper.png" alt="Scrapper Voice Mini AI Assistant" width="450">
</p>

A small Raspberry Pi based voice-assistant prototype integrating a MEMS microphone, audio output and external API services.

The system records a spoken query, processes it using external services and plays back a synthesized voice response.

`Raspberry Pi` `Python` `MEMS microphone` `Audio` `API integration` `Speech synthesis`

**Status:** 🟢 Completed prototype

---

## Room Automation Prototype Based on RX-2B / TX-2B

<p align="center">
  <img src="img/RXTX.jpg" alt="RX-2B TX-2B Room Automation Prototype" width="450">
</p>

An experimental room-automation prototype using RX-2B and TX-2B remote-control integrated circuits.

The project investigated whether inexpensive radio-control chips could be reused as a simple multi-channel home-automation platform.

A working remote-control unit and lighting actuator were built, but the project eventually demonstrated the practical advantages of Wi-Fi based microcontrollers such as the ESP32.

`RX-2B` `TX-2B` `Control electronics` `Remote control` `Prototyping` `Home automation`

**Status:** 🟢 Experimental prototype completed

---

# Projects Currently in Development

### Modular Laboratory Station

A modular electronics laboratory platform intended to combine several useful bench instruments in a common mechanical format.

The first module is an adjustable laboratory power supply. Future planned modules include symmetrical voltage generation and waveform generation.

`Power electronics` `CAD` `3D printing` `Laboratory equipment` `Modular design`

[Open repository](https://github.com/Wudker/Modular_lab_station)

---

### EVA – Everyday Virtual Assistant

A developing voice-assistant platform intended to integrate voice interaction, local embedded devices and the SmartRoom ecosystem.

The planned architecture uses Raspberry Pi computers for audio processing and higher-level logic, with MQTT used for communication with room devices.

`Raspberry Pi` `Python` `MQTT` `Voice interaction` `IoT` `AI integration`

[Open repository](https://github.com/Wudker/EVA)

---

### Modular Cabinet System

A modular storage and furniture concept designed in Autodesk Inventor.

The system is based on interchangeable CAD-designed modules that can be combined into different configurations.

`Autodesk Inventor` `CAD` `Mechanical design` `Modular design`

[Open repository](https://github.com/Wudker/Modular_cabinet)

---

# Main Areas of Interest

* Embedded systems
* Robotics
* Mechatronics
* PCB design
* Power electronics
* Prototype development
* Measurement systems
* Low-power devices
* IoT and wireless communication
* CAD and mechanical design
* 3D printing
