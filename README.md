\# ESP32-Sensor-Board



> A custom ESP32-C3 based sensor and embedded systems development board designed in KiCad 9.



!\[ESP32 Sensor Board](images/PCB-3d-front.png)



\---



\## Overview



The \*\*ESP32-Sensor-Board\*\* is a custom embedded systems development board built around the \*\*ESP32-C3\*\* microcontroller.



The board integrates sensing, user-interface, USB connectivity, battery charging, power regulation, and external expansion interfaces into a single compact PCB.



The complete design, from schematic capture through PCB layout and manufacturing outputs, was developed using \*\*KiCad 9\*\*.



\---



\## Key Features



\- ESP32-C3 based processing

\- BME280 environmental sensor

\- On-board sound sensing

\- USB connectivity

\- Li-ion/Li-Po battery charging

\- On-board voltage regulation

\- Power and charging indicators

\- Boot and reset buttons

\- USB RX/TX indicators

\- I2C interface

\- SPI interface

\- GPIO expansion

\- Dedicated test points

\- Custom KiCad symbol and footprint libraries

\- Manufacturing-ready Gerber and drill files

\- Hierarchical schematic design



\---



\## Hardware Overview



| Component / Feature | Description |

|---|---|

| Microcontroller | ESP32-C3 |

| Environmental Sensor | BME280 |

| Sound Sensing | On-board sound sensing circuit |

| USB | USB connectivity |

| Power | USB and rechargeable battery power |

| Charging | Li-ion/Li-Po battery charging |

| Regulation | On-board voltage regulation |

| Communication | I2C / SPI |

| Expansion | GPIO headers |

| Design Tool | KiCad 9 |



\---



\## Schematic



The design uses a hierarchical schematic structure to separate the major functional blocks of the board.



\### Complete Schematic



!\[ESP32 Schematic](images/ESP32-Schematic.png)



\---



\## Sensor Section



The sensor subsystem includes the \*\*BME280 environmental sensor\*\*, providing:



\- Temperature measurement

\- Relative humidity measurement

\- Atmospheric pressure measurement



The board also includes an on-board sound sensing circuit for detecting changes in ambient sound.



!\[Sensor Section](images/Sensor-Section.png)



\---



\## Power Management



The power section handles the board's power input, battery charging, regulation, and power-status indication.



The design supports:



\- USB power input

\- Rechargeable battery operation

\- Battery charging

\- Regulated supply generation

\- Power-status indication



!\[Power Section](images/Power-section-Schematic.png)



\---



\## User Interface



The board includes several user-interface and debugging features:



\- Boot button

\- Reset button

\- Power indicator

\- Charging indicators

\- USB RX/TX indicators

\- Status indicators



!\[User Interface](images/User-interface.png)



\---



\## PCB Design



The PCB was designed in \*\*KiCad 9\*\* with emphasis on compact component placement, practical routing, accessible debugging points, and clear board labeling.



\### PCB Layout



!\[PCB Layout](images/PCB-layout.png)



\### 3D PCB View



!\[3D PCB View](images/PCB-3d-front.png)



\---



\## PCB Design Highlights



\- Compact component placement

\- Dedicated power-management section

\- Short and organized signal routing

\- Clearly labeled interfaces

\- Accessible test points

\- External GPIO expansion

\- Separate functional blocks for easier debugging

\- Designed with manufacturability in mind



\---



\## Interfaces



\### USB



USB connectivity is provided for:



\- Power

\- Programming

\- Serial communication



\### I2C



The I2C interface allows additional sensors and peripherals to be connected to the board.



\### SPI



SPI is available for peripherals requiring higher-speed communication, such as displays, memory devices, and other external modules.



\### GPIO



Additional GPIO pins are exposed through the board headers for external sensors, modules, and experimentation.



\---



\## Manufacturing Files



Manufacturing outputs are provided in the \*\*ESP32\_Gerbers/\*\* directory.



The repository contains the generated \*\*Gerber and drill files\*\* required for PCB fabrication.



DFM-related manufacturing files are also included under \*\*dfm/gerber/\*\*.



\---



\## Repository Structure



&#x20;   ESP32-Sensor-Board/

&#x20;   │

&#x20;   ├── ESP32\_Gerbers/

&#x20;   │   └── Manufacturing Gerber \& drill files

&#x20;   │

&#x20;   ├── Libraries/

&#x20;   │   └── Custom KiCad symbols and footprints

&#x20;   │

&#x20;   ├── dfm/

&#x20;   │   └── gerber/

&#x20;   │       └── DFM / manufacturing files

&#x20;   │

&#x20;   ├── images/

&#x20;   │   ├── ESP32-Schematic.png

&#x20;   │   ├── PCB-3d-front.png

&#x20;   │   ├── PCB-layout.png

&#x20;   │   ├── Power-section-Schematic.png

&#x20;   │   ├── Sensor-Section.png

&#x20;   │   └── User-interface.png

&#x20;   │

&#x20;   ├── KiCad 9 Esp32 Project.kicad\_pro

&#x20;   ├── KiCad 9 Esp32 Project.kicad\_sch

&#x20;   ├── KiCad 9 Esp32 Project.kicad\_pcb

&#x20;   │

&#x20;   ├── esp32-c3-02.kicad\_sch

&#x20;   ├── sensors.kicad\_sch

&#x20;   ├── user\_interface.kicad\_sch

&#x20;   │

&#x20;   ├── .gitignore

&#x20;   └── README.md



\---



\## Design Files



The complete KiCad project files are included in this repository.



The project can be opened and further modified using \*\*KiCad 9\*\*.



Included design files:



\- Project configuration

\- Main hierarchical schematic

\- Individual schematic sheets

\- PCB layout

\- Custom symbol libraries

\- Custom footprint libraries

\- Manufacturing outputs



\---



\## Tools \& Technologies



\- \*\*KiCad 9\*\*

\- \*\*ESP32-C3\*\*

\- PCB Design

\- Schematic Capture

\- Embedded Systems

\- Sensor Interfaces

\- Power Electronics

\- IoT Hardware Design



\---



\## Project Status



\*\*Hardware design completed\*\*



\- \[x] Schematic design

\- \[x] Hierarchical schematic organization

\- \[x] PCB layout

\- \[x] 3D PCB design

\- \[x] Sensor integration

\- \[x] Power-management design

\- \[x] Gerber generation

\- \[x] DFM files

\- \[x] Custom libraries



\---



\## Author



\*\*Ratnakar Sahoo\*\*



Embedded Systems \& PCB Design



\---



\## License



This project is provided for educational and development purposes.



Please refer to the repository contents for the applicable design and manufacturing files.

