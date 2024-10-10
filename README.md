# Pocket Weather Station - Your Weather Assistant on the Go

### By Aarav G

## Introduction
The Pocket Weather Station is a compact and portable device that provides real-time temperature and humidity information. Built using an Arduino Nano, DHT11 sensor, and OLED display, this project is perfect for keeping track of the weather wherever you are. With an inbuilt rechargeable battery, it fits right in your pocket, giving you weather updates on the go!

## Features
- Real-time temperature and humidity display
- Portable and pocket-sized
- Rechargeable 160mAh LiPo battery
- OLED display for clear weather information

## Components
### Required:
- **Arduino Nano** with Cable
- **DHT11 Temperature Sensor Module**
- **0.96" OLED Display**
- **TP4056 Battery Charging Module**
- **160mAh LiPo Battery**
- **Slide Switch**
  
### Optional Tools:
- **Soldering Iron**
- **Jumper Wires**
- **Hot Glue Gun**
- **3D Printer** (for enclosure)

## Steps

### 1. Gather Components
Before starting, ensure you have all the necessary components and tools to complete the project. You can find the components from suppliers like Quartz Components.

### 2. Stacking Components
Plan the layout of the components to keep the device as slim as possible. Spread out the components to minimize thickness while ensuring they fit neatly inside the enclosure.

### 3. Schematic
Draft a simple schematic that connects the battery to the charging module, the charging module to the Arduino Nano, and the sensor/display to the Nano. Refer to the attached schematic image for guidance.

### 4. Soldering
Solder the components according to the schematic. Keep wire lengths minimal to reduce clutter and avoid short circuits.

### 5. After Soldering
After soldering, check that the wiring is tidy and all connections are secure. You’ll need a suitable enclosure for your project next.

### 6. Making the Enclosure
Design and 3D print the enclosure using Tinkercad, or order a 3D print from a service like IAmRapid. The enclosure should have cutouts for the display, ports, and switch.

### 7. Placing Circuit in Enclosure
Place the assembled circuit inside the 3D-printed enclosure, ensuring all ports and switches align with their cutouts. Use hot glue to secure the components inside the case.

### 8. Adding the Switch
Install the slide switch into the enclosure. Connect it between the VCC of the Arduino Nano and the positive terminal of the battery charging module.

### 9. Closing the Enclosure
Close the enclosure with screws, ensuring a snug fit. Consider adding a logo or custom design on the lid for a personalized touch.

### 10. Coding
Upload the Arduino code to the Nano to drive the display and sensor. The code for the Pocket Weather Station is attached below. Feel free to modify it to suit your needs.
