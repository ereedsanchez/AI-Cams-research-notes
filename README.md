# AI Cams Research Notes
An (un)organized collection of notes for research in AI Cameras with a specific focus on Animal Recognition.. 

### Synopsis
This repository documents a two-year CUNY Research Scholars Program (CRSP) project led by Prof. Edwin Reed-Sanchez that developed AI-powered wildlife monitoring systems in collaboration with Black Rock Forest. Building upon previous work establishing a WiFi mesh network for environmental sensing, the research team—including students Abdon Vizcarrando, Yangel Aguilera, Jorge Grullon, and Nagib Gonzalez—created solar-powered camera trap systems using ESP32-CAM microcontrollers, Wyze cameras, and Raspberry Pi platforms integrated with custom AI models for automated animal classification. The project progressed through multiple phases including electronics fundamentals, 3D design of weatherproof enclosures, hardware assembly, embedded programming, and machine learning integration using tools like Roboflow, YOLOv5/v8, and MegaDetector. The autonomous systems successfully tested at Bronx Community College and in Black Rock Forest. There has been significant progress in forest environments to detect and classify wildlife in real-time, demonstrating practical applications of affordable AI technology in ecological monitoring while providing students hands-on experience in solar power systems, embedded programming, computer vision, and conservation technology.

### Contributors - Student Reseachers
- Abdon Vizcarrando
- Yangel Aguilera
- Jorge Grullon
- Nagib Gonzalez

### Original Proposal
- [Cuny Research Scholars Program (CRSP) Proposal 2024-2025](https://docs.google.com/document/d/1gHF6J3HmxAmjpj4pMCxD14Qhg99zvS1f39z_1naYhxo/edit?usp=sharing)

### Literature Review
- [AI-Forest-Cam-Literature-Review](https://github.com/ereedsanchez/AI-Forest-Cam-Litterature-Review/tree/main) - This initial literature review was conducted by MD, and Abdon Vizcorando

### Reports
- [Black Rock Forest Redden Grant Report](https://docs.google.com/document/d/15IkCpGMCDkm8erarC1mEj0kqz4jUdr_CKkKSLedYVns/edit?usp=sharing) - This project recieved additional funding from the Black Rock Forest Redden Grant in 2023.
  Here is the final report. It adequatly sumarizes project accomplishments.

### Documentation 
- [Forest-Buddy-Server](https://github.com/ereedsanchez/Forest-Buddy-Server) - Forest Buddy, was the first attempt at creating a functional server to intake images and use AI to process images.  This documentation has hardware and software specifications and instructions.  Includes installation of NVDIA, CUDU, Python, Tensorflow, etc..

- [AMB82-ForestBuddy](https://github.com/ereedsanchez/AMB82-ForestBuddy) - Arduino code repository for AMB82-Mini firmware.  The AMB82-Mini is the cameraboard of choice for low-cost, but high quality video for develppment of a complete AI Camera solution.

- [WyzeCam-Forest-Buddy](https://github.com/ereedsanchez/WyzeCam-Forest-Buddy) - WyzeCam is a low-cost wifi camera. For this project we used a hacked firmware to convert the wyzecam to open system to send images to server, as well as provide a RTSP stream.  Original clone from [Defang-Hacks](https://github.com/ereedsanchez/Forest-Buddy-Dafang-Hacks)

### Courses
Summer courses where done in the summers of 2024, and 2025, where student experimented with AI camera solutions.  Below are links to curriculams and final resources.  
- [AI-Critters : STEP Summer 2024 Curriculam](https://github.com/ereedsanchez/AI-Critters-STEP-2024)
- [AI-Critters : STEP Summer 2024 Presentation](https://docs.google.com/presentation/d/1uootLNfX87BtUUzckVs5OC5VaLY_xtEMPsQVox_nhOI/edit?usp=sharing)
- [Science Technology and Ecology](https://github.com/ereedsanchez/Science-Technology-and-Ecology) - Precurser to AI-Camera courses. Based on Arduino sensor kits.
- [Critter Cams](https://github.com/ereedsanchez/CritterCam) - Work in Progress - Documentation of Crittercams used in Black Rock Forest.


### Additional Tools 
- [rtsp-stream-to-youtube](https://github.com/ereedsanchez/wyze-rtsp-stream-to-youtube) Script to stream RTSP video streams to youtube.

### Additional Website
- [Black Rock Forest Wifi Network Site](https://blackrock.treefi.net/)
- [Critter Cam Youtube page](https://www.youtube.com/channel/UCa2ZBux_xDUielNOPe4S9aQ?view_as=subscriber)
