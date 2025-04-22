# **🌡️ Temperature Monitoring**

## **📖 Description**
This project aims to design an embedded system capable of measuring and displaying ambient temperature in real time. Using an **STM32F446RE** microcontroller, an **LM35** temperature sensor, and an **LCD** screen, the project demonstrates a reliable and efficient solution for monitoring temperature variations.

---

## **🎯 Objectives**
- Read ambient temperature using the **LM35** analog sensor.
- Convert analog data to digital using the **STM32F446RE** built-in ADC (Analog-to-Digital Converter).
- Display real-time temperature readings on an **LCD** screen.
  
---

## **⚙️  Hardware Components**
- **Microcontroller** : STM32F4 (STM32F446RE)
- **Temperature Sensor** : LM35
- **Display** : Standard 16x4 LCD
- **Wires and Connectors** : For all necessary connections.

---

## **🖥️ Software Components**
- **IDE** : STM32CubeIDE
- **Libraries**: HAL (Hardware Abstraction Layer) for STM32
- **Language** : C Programming

---

## **📸 Preview**
Here's a preview of the system in action:  

![Aperçu](./capture1.jpg)

![Aperçu](./capture2.jpg)

---

## **🚀  Features**
1. Accurate temperature reading in Celsius.
2. Clear and readable LCD display.
3. Fast response thanks to STM32F446RE performance.

---

## **🔧 Hardware Connections**
- **LM35** :
  - VCC → 3.3V
  - GND → GND
  - OUT → PA0 (ADC_IN0 sur STM32)
- **LCD** (Mode 4 bits) :
  - RS, E, D4-D7 connected to **STM32F4** GPIOs.

---

## **📜 How to Use**
1. Clone this repository:  
   git clone https://github.com/hazemboukouba/Temperature_Monitoring.git

2. Open the project in STM32CubeIDE.
3. Build and flash the firmware to the STM32F446RE.
4. Connect the hardware as shown in the wiring diagram.
5. Power the system and observe the temperature readings on the LCD.
   
---

## 🎉 Author

Hazem BOUKOUBA - Embedded Systems Engineer
📧 Contact : www.linkedin.com/in/boukouba-hazem
