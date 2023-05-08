# DIH<sup>2</sup> Components

[![License: MIT](https://img.shields.io/github/license/ramp-eu/TTE.project1.svg)](https://opensource.org/licenses/MIT)
<br/>

The DIH<sup>2</sup> project implemented a Technology Transfer Program in which technology providers developed robotics-based solutions to increase the agility of several manufacturing SMEs across Europe. The table below is a summary of the projects carried out in such Technology Transfer Program. For each project, the following information is attached:

* A short text description of each project 
* An introductory video on the overall project concept demonstrated in the manufacturing SME
* Convenient links to the open software components (ROSE-APs) that each of these projects has contributed to the DIH<sup>2</sup> catalog 

## Contents
| Project | Short Description | ROSE-AP Repositories |
|---------|-------------------|----------------------|
| AgilPlas | AGILPLAS aims to improve the production system of a plastic manufacturer, XIMA, thanks to the use of an IIoT (Industrial Internet of Things) platform based on the use of FIWARE and implemented by Bosonit S.L. The main problem to be solved is clogging or adhesion of material to the mould in plastic injection processes​, which leads to manual maintenance tasks, affecting productivity. <br/> [AgilPlas Concept Overview - Short Video](https://youtu.be/feRdeZrMqAI) "AgilPlas video") | [IoT Agent for M-Duino PLCs](https://github.com/ramp-eu/AGILPLAS "AgilPlas ROSE-AP") |
| ARP | The proposed solution aims to achieve high flexibility for automating the processing of flat workpieces. In order to achieve this goal, the system has been designed to manage different parameters of the sanding process, which are not tied to a particular model or brand. Workers will be able to choose the correct combination of parameters for a certain type of material in relation to the desired finish and, based on that, the system will automatically configure itself <br/> [ARP Concept Overview - Short Video](https://www.youtube.com/watch?v=oQqg1zUhGk0 "ARP video") | [Trajectory Generator](https://github.com/visionequipment/arp "ARP ROSE-AP") |
| Cobitt |  COBITT aims to support companies that manufacture multi-layered composite and synthetic-material products, through laminate stacking and forming processes, by catering to a fully automated and agile manufacturing process. More precisely, it facilitates the optimal co-operation of heterogeneous machines and the FIWARE modules for interoperability, with the aim of achieving order completion. <br/> [Cobitt Concept Overview - Short Video](https://youtu.be/y81IoQpFitg "Cobitt Video") | [Web App](https://github.com/iasonasiasonos/COBITT "Cobitt ROSE-AP 1"), [ROS 2 IoT Agent](https://github.com/iasonasiasonos/iot_agent_ros2 "Cobitt ROSE-AP 2") |
| D-Mould | D-Mould is a robotics-based solution that contributes to the continuous production of moulding machines with reduced downtime and a more reliable process resulting in decreased human risk factors and increased production output. <br/> [D-Mould Concept Overview - Short Video](https://www.youtube.com/watch?v=tSLBQltqkDs&list=PL4XG_Puhu_73PWxoMlRevCdisBiIzMerA&index=12 "D-Mould video")| [Multi-robot DCS](https://github.com/proaimslovenia/D-Mould "D-Mould ROSE-AP") |
| FlexMill | The main part of the FlexMill project was the development of an automated tool provision process for machine tools by an autonomous mobile robot. The software for that robot can be found in the section “AMRControl” and is specifically programmed for the Protobot V2 from DALMA Robotics. Furthermore, the industrialization process including 3D modelling, drawing generation and NC code generation for adapter end production was automatized. The respective results, which are described in the ROSE-AP repositories, can also be downloaded for this purpose. <br/> [FlexMill Concept Overview - Short Video](https://youtu.be/eF9owxZlJDo "FlexMill Video") | [Overview](https://github.com/flexmill/Start-here---Overview "FlexMill Overview") + [AMR Control](https://github.com/flexmill/AMRControl "FlexMill ROSE-AP 1"), [CAD/CAM Automatization](https://github.com/flexmill/CAD_CAM_Automatization "FlexMill ROSE-AP 2"), [Machining Centre Server](https://github.com/flexmill/fiware_connector_machiningcentre_tools "FlexMill ROSE-AP 3"), [Broker Console](https://github.com/flexmill/Fiware-databroker-console "FlexMill Tool") |
| Gridiron | There is a need to automate and optimize production processes in the manufacture of biosensors and auxiliary electronic materials to reduce costs and false negatives in diagnostic tests. In this regard, there is a growing trend in investment in solutions that detect production failures in increasingly robotic biosensor manufacturing environments. GRIDIRON project deals with these issues and aims to detect and prevent potential errors in circuitry, electrodes and vials used in testing. <br/> [Gridiron Concept Overview - Short Video](https://youtu.be/zHcOnmqqBDI "Gridiron Video") | [AI Backend + Microscope and Pipette Robot Servers](https://github.com/AIRInstitute/Gridiron "Gridiron ROSE-AP") |
| Innowest | The Innowest project addresses the manufacturing process of metal structures and parts manufacture and assembly of products made of metal components. The problem solved is the robotization of the process of polishing and welding parts used in various products such as those intended for the food industry, the automotive industry, construction or furniture, etc. <br/> [Innowest Concept Overview - Short Video](https://youtu.be/2My_izk_lbk "Innowest Video") | [Multi-process data broker](https://github.com/manioanadrian/Inno-West "Innowest ROSE-AP") |
| Mediscara | Mediscara aims to support small and medium sized medical equipment manufacturers in two major application scenarios: (1) agile production and quick modification of parts, and (2) traceability and documentation, which receives more emphasis as the new EU medical device regulations are getting closer to taking effect. Two separate robotic cells have been developed by the tech provider for the abovementioned challenges. One laser cutting workshop cell for agile part modification and an electrical checkpoint for automated quality inspection, labelling, marking and production tracking tasks. <br/>[Mediscara Concept Overview - Short Video](https://youtu.be/Wt1h4Fgvj_w "Mediscara Video") | [Manager App](https://github.com/ppuska/mediscara.manager "Mediscara ROSE-AP 1"), [Master Control Unit](https://github.com/ppuska/mediscara.mcu  "Mediscara ROSE-AP 2"), [PDF Generator](https://github.com/ppuska/pdf-generator "Mediscara ROSE-AP 3") |
| Oscar | Oscar is an IoT application for enabling communication between an interactive Graphical User Interface (GUI) and a robotic arm assisting the operator during the assembly process. Main modules of Oscar are: (1) CSV Parser, a component in charge of loading the data of the components and processing steps on Fiware. (2) ROS Services for Fiware-UI-Robot, a component enabling communication from UI to the robotic arm. (3) ROS Services for Kinect-Fiware, a component enabling communication from the camera to Fiware. (4) HoloLens UI application, the interactive Graphical User Interface <br/> [Oscar Concept Overview - Short Video](https://youtu.be/tXE_EHbNEZw "Oscar Video") | [Interactive GUI for Automated Assembly](https://github.com/flexsight/Oscar "Oscar ROSE-AP") |
| PoRoLog | Modern warehouses require for modern logistics solutions. PoRoLog aspires to provide a robotics-based solution that can contribute to automate and/or improve day-to-day workload, so that the warehouse improves its efficiency, optimizes storage capacity, and decrease physical work. Specifically, PoRoLog proposes a new reconfigurable and scalable robotic system for pallet and box transfers in existing logistics warehouses and a new open source software for supervision of groups of robots named NOOS-Open. <br/> [PoRoLog Concept Overview - Short Video](https://youtu.be/GgNx3iWzDys "Porolog Video") | [Noos-Open](https://github.com/ortelio/Noos-Open "PoRoLog ROSE-AP") |
| Prebots | Prebots eases the creation of robot program definitions that can be instantiated for different robot vendors and offers a management system to work with them. The project contributes an IoT application for defining, building, and managing the aforementioned robot programs. <br/> [Prebots Concept Overview - Short Video](https://youtu.be/zZpKVAsg1Oo "Prebots Video") | [Model Builder + Program Manager](https://github.com/canonical-robots/prebot-rose-ap "Prebots ROSE-AP") |
| RAM ASP | RAM ASP is a 3D printing project that aims to automate, consolidate and make more reliable 3D Printing. The 3D printers composing the system are supposed to be organized in an orderly and regular physical scheme. To obtain the maximum degree of automation, the system should be equipped with a robotic arm. This arm will execute manual operations such as load and unloads of 3D printing plates and control vision of 3D printing. <br/> [RAM ASP Concept Overview - Short Video](https://youtu.be/MtSpIaUOF58 "RAM ASP Video") | [3D Printers Central Control Unit + Printer Agents](https://github.com/3DPRN/RAMASP "RAM ASP ROSE-AP") |
| Robo4Toys | MOMAMS provides a system for (1) logging manufacturing systems, (2) calculating OEE values, (3) OEE visualisation and (4) sending alerts for operators about failures or upcoming tasks. The system is capable of handling manufacturing systems that match the criteria of the Job-shop scheduling problem and is capable of constantly updating the objects in the FIWARE's Orion context broker. <br/> [Robo4Toys Concept Overview - Short Video](https://youtu.be/9f6x-ukbuko "Robo4Toys") | [MOMAMS (Manufacturing Oee + Mes Alert Management System](https://github.com/aviharos/momams "Robo4Toys ROSE-AP") |
| Robosonic | Robosonic offers an automation solution based on a standardized machine platform named MicBotX that is equipped with a 6-axis industrial robot. In addition, two software applications, so-called Rose APs, were integrated to (1) support the integration process between order types and externally controlled robot program exchanges and (2) enable users to obtain information about current orders and work sequences as easily as possible.  <br/> [Robosonic Concept Overview - Short Video](https://youtu.be/uNfq77xNcns "Robosonic Video") | [Robot Program Handler](https://github.com/dih2-rowa/programhandler "Robosonic ROSE-AP 1"), [Information Server](https://github.com/dih2-rowa/informationserver "Robosonic ROSE-AP 2"), [Production Simulator](https://github.com/dih2-rowa/productionSimulation "Robosonic ROSE-AP 3")
| Romantig | Romantig contributes a microservice for automatic OEE, and related metrics, calculation. The service works creating the appropiete table views in a CrateDB database, where information about the context of the target process are stored by the FIWARE's Orion context broker through a QuantumLeap subscription. <br/>  [Romantig Concept Overview - Short Video](https://youtu.be/oAzB8p1Csv4 "Romantig Video") | [OEE Calculator](https://github.com/claret-srl/ROMANTIG/tree/master "Romantig ROSE-AP")

## License

[MIT](LICENSE) © <TTE>
