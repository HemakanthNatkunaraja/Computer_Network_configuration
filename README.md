
# University IT Centre and Department Network Design

## Project Overview

This project involves designing a computer network for the newly built IT Centre and Department building at the University. The buildings will house various facilities including discussion rooms, department offices, lecture halls, laboratories, meeting rooms, and computer labs. The goal is to optimize the use of network IP addresses within the available range of `10.20.0.0/16`.

## Building Specifications

### Dimensions (2-Story Building)
- **Length:** 70 meters
- **Width:** 30 meters
- **Height (each floor):** 4 meters

## Network Design Requirements

You are requested to submit a report with the following details:
- Network diagram (subnets and VLANs – provide IP addresses for each of them)
- Steps on how to configure routers and switches
- WiFi access points configuration details

## Background Information

### IT Centre Block
**Number of Data Points:** 164
- **Director Office:** 2 desktop computers
- **Network Manager Room:** 1 desktop computer
- **Technical Officers Rooms:** 2 rooms, each with 1 computer
- **Staff Office:** 5 computers
- **Meeting Room:** 2 data points (1 for video conferencing, 1 for computer) and WiFi coverage
- **Lobby Area:** WiFi coverage
- **Computer Lab 1:** 60 computers
- **Computer Lab 2:** 60 computers
- **Digital Learning and Media Centre:** 30 computers and 1 printer
- **Printing Room:** 2 printers

### Department Block
**Number of Data Points:** 203
- **Lecture Halls:** 4 halls, each with 1 desktop computer and 1 interactive multimedia projector
- **Staff Rooms:** 14 rooms, each with 1 desktop computer
- **Technical Officers Rooms:** 4 rooms, each with 1 desktop computer
- **Department Meeting Room:** 2 data points (1 for video conferencing, 1 for computer) and WiFi coverage
- **Computer Lab 1:** 50 computers
- **Computer Lab 2:** 50 computers
- **Network Engineering Lab:** 10 computers
- **Microprocessor Lab:** 12 computers
- **Computer Vision and Machine Learning Lab:** 50 computers
- **Department Office:** 2 computers and 1 printer

## Access Restrictions

- Computers in the staff room cannot be accessed from the Network Engineering lab, department office, department meeting room, lecture halls, computer labs, Computer Vision and Machine Learning Lab, Microprocessor Lab, Technical Officers Rooms, and the IT Centre (for security reasons).
- Computers in the department office cannot be accessed from the staff room, Network Engineering lab, department meeting room, lecture halls, computer labs, Computer Vision and Machine Learning Lab, Microprocessor Lab, Technical Officers Rooms, and the IT Centre.

## Requirements
- The printer in the department office can only be accessed by department staff.
- The printer in the IT Centre printing room can only be accessed by IT Centre staff.
- Each network node can only be accessed by the administrator, not others.

## Deadline
The project is due by **4:00 PM on May 15, 2023**.

## Installation and Usage
1. Clone the repository to your local machine.
2. Follow the instructions in the report to configure the network devices.
3. Use the provided network diagram for reference.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- University IT Department for providing the project requirements.
- Firebase and ESP32 documentation for technical references.
