# Design Gilbert Cell using CMOS


This repository presents the design  of Gilbert Cell using CMOS implemented using Synopsis Custom Compiler on 28nm CMOS Technology.


##  Table Of Content
   * [Abstract](#Abstract)
   * [Introduction](#Introduction)
   * [Tools Used](#Tools-Used)
   * [Design Explanation](#Design-Explanation)
   * [CMOS Inverter](#CMOS-Inverter)
   * [Gilbert_cell](#Gilbert_Cell)
   * [Simulations](#Simulations)
   * [Netlist](#Netlist)
   * [Acknowledgements](#Acknowledgements)
   * [References](#References)
 





## Abstract
Demand of wireless communication increasing day by day everywhere specially at consumer level. Gilbert Cell is widely used in analog and communication system. Design Gilbert Cell using CMOS implemented using Synopsis Custom Compiler.

## Introduction

Gilbert Cell is one type of cross-coupled differential amplifier whose gain is controlled by a control voltage (Vcontrol). Because of gain control ability it has many applications like voltage multiplier, frequency mixer, AGC amplifier, Amplitude modulator, Double sideband modulator, Squaring circuits, etc.
Its gain varies from negative value to positive value.
In this circuit,
- Vdc= 1.8 V
- frequency = 10 MHz
- Vin = 0.5 V (pulse " Vmax= 1V  , Vmin = 0V ")
- Vcontrol = 1 V (pulse " Vmax= 2V  , Vmin = 0V ")


## Tools Used

- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.


## Design Explanation


- Step 1: Design CMOS inverter cell
- Step 2: Design Gilbert cell
In Gilbert Cell provides opposite voltage using cmos inverter at input voltage and control voltage in M4 and M2 mos


## CMOS Inverter
- CMOS Schematic Diagram
<p align="center">
<img width="495" 
     height="300"
     alt="Screenshot 2022-03-01 111147" src="https://user-images.githubusercontent.com/100601295/156113020-d475f583-df79-4167-9be3-57d5a3f5315e.png" />
  
     
  -Symbol :
  <p align="center">
  <img width="333" alt="Screenshot 2022-03-01 111328" src="https://user-images.githubusercontent.com/100601295/156130539-8fcdddd9-079f-4e2b-a8db-603264b93321.png">

  
## Gilbert Cell
    - Gilbert Cell Schematic Diagram
  <p align="center">
  <img width="512" 
       height="300"
       alt="Screenshot 2022-03-01 104617" src="https://user-images.githubusercontent.com/100601295/156113792-0629c0b9-0012-4df9-9d05-27b543c581ab.png" />
    
 


    
    
##  Netlist
    
 Refer this link for netlist : <a href='Gilbert_cell_netlist.txt'> Netlist </a>
    
    
    
## Simulations
  
![image](https://user-images.githubusercontent.com/100601295/156120541-d8d60b42-3db8-4c4d-90dd-6ed80b9b6618.png)


 




## Author

- Dhanraj Choudhary, Communication System Engineering , L.D. College of Engineering , Ahmedabad-380015

    
    

## Acknowledgements

 - [Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
 - [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
 - [Synopsys India](https://www.synopsys.com/)
 - [Chinmay panda, IIT Hyderabad](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)


    

## References
- [1] Design of Analog CMOS Integrated Circuits.https://www.mheducation.co.in/design-of-analog-cmos-integrated-circuits-9789387067844-india. Accessed 19 Feb. 2022. Page 126-129 
