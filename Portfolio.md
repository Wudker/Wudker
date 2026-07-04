# Bartłomiej Dusza – Technical Portfolio

A short portfolio of selected technical projects in **mechatronics**, **electronics** and **embedded systems**.

---

## Selected Projects

---

## 6-DOF Manipulator – Engineering Thesis

<p align="center">
  <img src="img/6dof_manipulator.jpg" alt="6-DOF Manipulator" width="500">
</p>

### Project description

Design and construction of an educational anthropomorphic manipulator with 6 degrees of freedom.  
The scope included the kinematic model, mechanical design, custom control electronics, control software and validation of the complete system.

### My contribution

I developed the kinematic model and design requirements, designed the mechanical parts and control electronics, prepared the software for motion control, and carried out tests of the robot’s accuracy and repeatability.

### Technologies

`3D CAD` `3D printing` `ESP32` `Stepper motor drivers` `PCB design` `C/C++` `Kinematic analysis` `Prototype testing`

### Status

A working prototype of the manipulator was built, with its own control system and remote operation.  
The project was completed as a full engineering thesis combining mechanics, electronics and software.

---

## ESP32 Solar Weather Station

<p align="center">
  <img src="img/esp32_solar_weather_station.jpg" alt="ESP32 Solar Weather Station" width="500">
</p>

### Project description

An autonomous weather station powered by a battery and a photovoltaic panel, designed for outdoor operation.  
The system collects environmental data, sends it wirelessly to a receiver and presents the measurements in a local web interface.

### My contribution

I designed the electronics using commercial modules, developed software for collecting data on the station and displaying it on the receiver.  
I also modeled and built the mechanical structure.

### Technologies

`ESP32` `ESP-NOW` `BME280` `SGP40` `Solar power supply` `Li-Ion` `WebServer` `Low-power operation`

### Status

A working prototype was built.  
It collects environmental data, sends it to the receiver and displays the results on a local web page.

---

## Clickfy – BLE Remote Control

<p align="center">
  <img src="img/clickfy_ble_remote.jpg" alt="Clickfy BLE Remote Control" width="500">
</p>

### Project description

An ESP32-based remote designed as a wireless multimedia controller using Bluetooth Low Energy.  
The device is intended to work as a convenient keychain for controlling basic functions such as play, pause and changing tracks.

### My contribution

I developed the device concept, designed the schematic and PCB layout, selected the main electronic components, and designed the enclosure with miniaturization in mind.

### Technologies

`ESP32` `BLE` `PCB design` `Digital electronics` `Circuit miniaturization` `Portable device design`

### Status

A working prototype has been built.  
Work is currently in progress on more power-efficient firmware.

---

## MC34063 Boost Converter

<p align="center">
  <img src="img/mc34063_boost_converter.jpg" alt="MC34063 Boost Converter" width="500">
</p>

### Project description

An educational prototype project focused on developing a custom step-up converter based on the popular MC34063 integrated circuit.  
The goal was to better understand boost converter operation, component selection and the limitations of classic switching controllers.

### My contribution

I designed and tested converter prototypes, selected passive components and analyzed how circuit parameters affect operation and efficiency.  
I treated the project as a practical exercise in power electronics and as a base for further development.

### Technologies

`MC34063` `Power electronics` `Switching converters` `Prototyping` `Measurements` `Efficiency analysis`

### Status

Working prototypes were built and confirmed the basic concept.  
At the same time, the achieved efficiency turned out to be limited, which became a starting point for further learning and plans to build better circuits using newer controllers.

---

## Electronic Measuring Scale

<p align="center">
  <img src="img/electronic_measuring_scale.jpg" alt="Electronic Measuring Scale" width="500">
</p>

### Project description

An electronic scale for measuring mass with a strain gauge sensor and a measuring circuit that converts small signal changes from the load cell into a result displayed to the user.

### My contribution

I developed the concept of the measuring circuit, selected the elements of the measurement path, prepared the program responsible for reading and converting the result into mass, and carried out basic calibration and stability tests.

### Technologies

`Strain gauge sensor` `Amplifier/ADC` `Microcontroller` `Analog measurements` `Calibration` `Signal filtering` `C/C++` `Prototyping`

### Status

A working prototype was built.

---

## S.M.U. – RLC Component Meter

<p align="center">
  <img src="img/smu_rlc_component_meter.jpg" alt="S.M.U. RLC Component Meter" width="500">
</p>

### Project description

S.M.U. is a custom RLC component meter.  
The idea came from the need to measure coil inductance and to conveniently test basic electronic components.

The operating idea is simple: the user selects the component type, places it in the measurement connector and starts the measurement by pressing a button.

### My contribution

I developed the measurement methods for resistance, capacitance and inductance.

For resistance, I used a voltage divider with reference resistors.  
For capacitance, I used RC time constant measurement.  
For inductance, I used a method based on exciting an LC circuit and analyzing ring-down oscillations.

I also designed the PCB, developed the software responsible for controlling the measurement and calculating the result, and designed and built the enclosure.

### Technologies

`Raspberry Pi Pico` `RLC measurements` `ADC` `Comparator` `LC circuit` `Ring-down method` `RC` `PCB design` `C/C++` `Prototyping`

### Status

A working prototype was built.

---

## Scrapper – Voice Mini AI Assistant

<p align="center">
  <img src="img/scrapper_voice_ai_assistant.jpg" alt="Scrapper Voice Mini AI Assistant" width="500">
</p>

### Project description

A small voice assistant prototype using a Raspberry Pi platform, a MEMS microphone and a speaker for simple voice interactions.  
The device records a voice question, processes it using API services and plays back the generated answer as speech.

### My contribution

I integrated the hardware and software layers of the device, including audio input handling, query processing, communication with external services and voice response synthesis.

I am developing the project as an experimental combination of embedded systems, audio and AI tools.

### Technologies

`Raspberry Pi` `MEMS microphone` `Speaker` `Python` `OpenAI API` `API integration` `Audio` `Speech synthesis`

### Status

A working prototype was built.

---

## Room Automation System Based on RX-2B / TX-2B

<p align="center">
  <img src="img/rx2b_tx2b_room_automation.jpg" alt="Room Automation System Based on RX-2B and TX-2B" width="500">
</p>

### Project description

A developing concept of a simple platform for automating selected room functions, using older RX-2B and TX-2B chips as a multi-channel remote control system.

The goal is to build a simple, low-cost and easy-to-expand solution for controlling basic home devices.

### My contribution

I developed the system concept and I am testing practical uses of the available control channels in simple actuator circuits.

I have already prepared a remote control and a working module for remotely turning off the light in the room, and I am developing the project toward more useful functions and a consistent control platform.

### Technologies

`RX-2B` `TX-2B` `Control electronics` `Remote control` `Prototyping` `Home automation` `Integration of simple actuator circuits`

### Status

The project is under development.  
A basic system with a remote control and a function for remotely switching off the lighting is currently working, and further expansion is planned.

---

## Main Areas of Interest

- Embedded systems
- Mechatronics
- PCB design
- Prototype development
- Power electronics
- Robotics
- Measurement systems
- Low-power devices
- IoT and wireless communication

---

## Technologies and Tools

`C/C++` `Python` `ESP32` `Raspberry Pi` `Raspberry Pi Pico` `BLE` `ESP-NOW` `PCB Design` `3D CAD` `3D Printing` `Sensors` `Power Electronics` `Microcontrollers`

---

## Contact

GitHub: [Wudker](https://github.com/Wudker)
