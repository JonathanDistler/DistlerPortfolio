---
layout: default
title: Cornell Hyperloop
---

# Cornell Hyperloop

### Systems Subteam Member – Cornell Hyperloop

As a member of the Systems Subteam on **Cornell Hyperloop**, I contribute to the development of innovative solutions for the team’s structural and integration needs, including the design of the **battery pack enclosure**, **electrical harness routing**, and **microelectronic mounting systems**. I actively participate in **weekly team meetings**, engaging in technical discussions and contributing to decisions on **best design practices**. My responsibilities also include performing **hand calculations** to analyze **heat transfer** into the battery packs and **developing and modeling the stress and strain** behavior of structural components to ensure safety, reliability, and performance. I was also responsible for machining and fabricating different parts for the team, using rapid prototyping strategies like 3D-printing, laser cutting, and milling.

## Battery Pack Enclosure
Below are pictures of our final battery pack enclosure system. This system was designed to be easily accessible, such that our Electrical subteam members could easily modularize different pattery packs within a matter of minutes. It was also able to be opened to an angle up to ~75-degrees, allowing easy access to all battery pack modules. Furthermore, the acrylic and 20-20 structure supported the mass of the battery management system (BMS) on top, even when opened to its maximum angle. 

<img src="https://github.com/user-attachments/assets/456c7be4-d639-48b7-8e6b-06cc4b262aaf" alt="Battery Pack Enclosure Render 1" width="300"/>
<img src="https://github.com/user-attachments/assets/61e9484d-5221-40ed-9128-811ed3628478" alt="Battery Pack Enclosure Render 2" width="300"/>
<img src="https://github.com/user-attachments/assets/898779d9-0073-4124-b687-bf97f456f5d2" alt="Battery Pack Enclosure Render 3" width="300"/>


## Battery Pack Enclosure FEA
Below are renders of the Finite Element Analysis (FEA) via the Ansys software. The renders show the stress on the acrylic given the loading of the BMS and the battery packs. As seen below, there aren't any regions of incredibly high stress. Although, there is a buildup of stress near the holes, considering the idea of stress concentrations (build-up of stress near discontinuities) the result is intuitive. 

<img src="https://github.com/user-attachments/assets/2624b9de-79e1-4690-bc71-8d9e7c8fcf28" alt="Battery_Pack_Ansys Top view" width="300"/>
<img src="https://github.com/user-attachments/assets/b9520702-5dbf-4a28-b741-c204db4bae9f" alt="Battery Pack Ansys Isometric View" width="300"/>


## Electrical Harness (Front, Isometric, Side)
Below are renders of our electrical harness CAD. The harness safely and concisely carries the wiring for different systems alongside the chassis to keep important wires independent from eachother (to avoid confusion), as well as to avoid electromagnetic effects from having high-current wires closeby to one another. The electrical harness screws in directly to the chassis allowing quick and reliable implementation. The snap-fit open also holds the wiring tightly, while allowing servicing. 

<img src="https://github.com/user-attachments/assets/366c7cbb-7987-4516-a59f-2293e20f82cd" alt="Harness Front" height="250"/>
<img src="https://github.com/user-attachments/assets/fd2b0485-cbe4-4de7-85a1-7dbbe87e61a1" alt="Harness Isometric" height="250"/>
<img src="https://github.com/user-attachments/assets/c41a23d1-d9cb-46f2-8ed5-09b502c40cd1" alt="Harness Side" height="250"/>


## Microelectronic Holders
Below are renders of our microelectronic holders. The microelectronics are mainly used to determine IMU data, which is then fed back into the system in a closed-loop manner (with the output influencing future inputs). The microelectronic holders were desigend to be adhered to the top of the aeroshell (making sure to keep a low-profile) and were allowed to feed their wires through holes back into the body of the aeroshell to safely relay position, velocity, and acceleration data to the pertinent systems throughout our pod. 

<img src="https://github.com/user-attachments/assets/0e9c1f08-9985-414b-bca7-53d99d36c884" alt="MicroElectronics Holder Orthographic" width="300"/>
<img src="https://github.com/user-attachments/assets/b166fa72-f969-4748-964a-ee9704818e9d" alt="MicroElectronics Holder Side" width="300"/>

