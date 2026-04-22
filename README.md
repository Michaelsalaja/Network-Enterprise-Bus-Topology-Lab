<p align="center">21.04.2026</p>

# <p align="center">Creating an Enterprise-Style Bus Network Topology with Cisco Packet Tracer</p>

## Introduction

This project focused solely on creating a Bus topology and emulate an enterprise style network topology. Before jumping into creating a bus network topology, it is important to briefly contextualize what a bus topology is and what other types of topologies do we have.

## Bus Topology

A bus topology is a network arrangement where all devices are connected to a single communication line, often called a bus. Data packets travel along this bus, and each device listens to the data passing by. In other words, Bus topology is a single backbone because all devices connect to the main line.

Moreover, we also have Star topology, Ring topology, Mesh topology and we do have two types of Mesh topology, which includes Full mesh and Partial mesh topology. Hybrid network topologies can be created and configured by combining two of more topology types.

## Network Topologies

*  Star Topology: In a network configuration, the communication bus enables devices to be connected in a centralized location.
*  Ring Topology: In network configuration, the communication bus allows devices to be connected on a closed loop and the data travels in one direction. If one node breaks, the entire network fails. To overcome this hurdle, ring topology designers created a ring topology with primary and secondary link data, so that data can be rerouted to either link if one node fails on a link.
*  Mesh Topology: It offers the most basic network connection scheme and the most extensive management scheme. In a network configuration, the communication bus enables devices to be connected to other multiple devices. Each node has direct physical connection to other nodes.

## Lab Objective

This lab project demonstrates the steps involved in creating a bus topology. Upon Completion of this lab, readers will be able to execute three major things.

*  Add devices to the Workspace
*  Assign IP addresses to PCs
*  Test Connectivity

# Lab Equipment

*  Cisco Packet Tracer

## Part A: Adding devices to the Workspace

**Step 1**

*  On my Desktop, I doubled-clicked Cisco packet Tracer Icon to open its window

**Step 2**

*  At the bottom left section, I clicked **Switches** icon  <img width="468" height="33" alt="image" src="https://github.com/user-attachments/assets/c68a26ed-3844-4719-a6aa-55eef30e4a06" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%201.png)
Figure 1: The Workspace


**Step 3**

*  From the middle pane at the bottom, I dragged the PT-Switch icon and dropped it on the grey workspace four times.
   <img width="468" height="34" alt="image" src="https://github.com/user-attachments/assets/1ca3f637-8808-4995-82bb-ac93e9f918c9" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%202.png)
Figure 2


# Step 4

*  At the bottom left section, I clicked **End Devices** icon  <img width="468" height="31" alt="image" src="https://github.com/user-attachments/assets/740fd925-9a0b-47da-909e-4d04772cc8dc" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%203.png)
Figure 3


# Step 5

* From the middle pane at the bottom, I dragged the PC icon and dropped it on the workspace four times.

  <img width="468" height="35" alt="image" src="https://github.com/user-attachments/assets/526e3ba0-2cec-4b4e-972a-5c440a00fb3b" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%204.png)
Figure 4


**Step 6**

*  At the bottom-left section, I clicked the Connections Icon   <img width="468" height="32" alt="image" src="https://github.com/user-attachments/assets/e92c444f-f5dd-4e32-892f-3dcf16339445" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%205.png)
Figure 5


**Step 7**

*  From the middle pane at the bottom, I selected the **“Automatically Choose Connection Type”** icon each time to connect Switch0 to PC0, Switch1 to PC1, Switch2 to PC2, and Switch3 to PC3

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%206.png)
Figure 6


Step 8

*  Again, from the middle pane at the bottom, I selected the **“Automatically Choose Connection Type”** icon and dragged the cable from one Switch to another Switch

  <img width="468" height="33" alt="image" src="https://github.com/user-attachments/assets/91542efc-4466-476d-9b73-c882c07b22e8" />


*  I clicked on “Automatically Choose Connection Type icon each time to execute a connection from Switch0 to Switch1, from Switch1 to Switch2, and from Switch2 to Switch3

  <img width="468" height="33" alt="image" src="https://github.com/user-attachments/assets/d7da518c-360d-474e-a516-bd1cb4f1d01b" />


![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%207.png)
Figure 7


## Part B: Assigning IP addresses PCs

### Step 1

*  In the Cisco Packet Tracer window, I clicked PC0

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%208.png)
Figure 8


## Step 2

In the PC0 window, I performed the following steps

*  I navigated to the Desktop, which already highlighted in the screenshot above.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%209.png)
Figure 9


*    I typed in IPv4 Adress 192.168.0.1 to assign a static address

*    The subnet mask will automatically give you 255.255.255.0. If not, type it in manually

*    Closed the PC0 window

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2010.png)
Figure 10


# Step 3

In the PC1 window, I performed the following steps

*  I navigated to the Desktop, which already highlighted in the screenshot above.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2011.png)
Figure 11


*  I typed in IPv4 Adress 192.168.0.2 to assign a static address

*  The subnet mask will automatically give you 255.255.255.0. If not, type it in manually

*  Closed the PC1 window

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2012.png)
Figure 12


# Step 4

In the PC2 window, I performed the following steps

*  I navigated to the Desktop, which already highlighted in the screenshot above.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2013.png)
Figiure 13


*  I typed in IPv4 Adress 192.168.0.3 to assign a static address

*  The subnet mask will automatically give you 255.255.255.0. If not, type it in manually

*  Closed the PC2 window

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2014.png)
Figure 14


# Step 5

In the PC3 window, I performed the following steps

*  I navigated to the Desktop, which already highlighted in the screenshot above.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2015.png)
Figure 15


Again

*  I typed in IPv4 Adress 192.168.0.4 to assign a static address
*  The subnet mask will automatically give you 255.255.255.0. If not, type it in manually
*  Closed the PC3 window

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2016.png)
Figure 16


Now, all the Domain Namer Servers have been configured for PC0, PC1, PC2, and PC3

## Part C: Testing the Connectivity

### Step 1

*  In the Cisco Packet Tracer window, I clicked PC0
*  Verify that the Desktop tab is selected and click Command Prompt.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2017.png)
Figure 17


*  In the PC0 terminal window, I executed the following command to ping 192.168.0.3 from the terminal

## Ping 192.168.0.3

*  192.168.0.1 successfully pinged 192.168.0.3

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2018.png)
Figure 18


*  Closed the PC0 terminal window

**Step 2**

*  In the Cisco Packet Tracer window, I clicked PC2
*  Verify that the Desktop tab is selected and click Command Prompt.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2019.png)
Figure 19


* In the PC2 terminal window, I executed the following command to ping 192.168.0.1 from the terminal

## Ping 192.168.0.1

* 192.168.0.2 successfully pinged 192.168.0.1

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2020.png)
Figure 20


*  Closed the PC2 terminal window

# Step 3

*  In the Cisco Packet Tracer window, I clicked PC3
*  Verify that the Desktop tab is selected and click Command Prompt.

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2021.png)
Figure 21


*  In the PC3 terminal window, I executed the following command to ping 192.168.0.2 from the terminal

## Ping 192.168.0.2

*  192.168.0.3 successfully pinged 192.168.0.2

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2022.png)
Figure 22


## Part D: Saving File

It is important to save your configuration before closing the Cisco Packet Tracer window to avoid disappointment

### Step 1

*  On the menu bar, I navigated to File, then to Save As

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2023.png)
Figure 23


## Step 2

*  In the Save File dialog box, in the left pane, I navigated to This PC, then Desktop

## Step 3

*  Typed the File Name I wished, then I clicked Save to finalize this simulation phase

![image alt](https://github.com/Michaelsalaja/Network-Enterprise-Bus-Topology-Lab/blob/49acf910a7a1fc050d4b478437efb9e96e657b06/Figure%2024.png)
Figure 24


## Result

This project enabled me to learn the following factors while creating a Bus Network Topology

*  Launched Cisco Packet Tracer and added four different Switches and PCs to my workspace
*  Used the Automatically Choose Connection Type tool to connect each PC with its node to its corresponding Switch and successfully interlink all switches.
*  Assigned IPv4 addresses and subnet masks to PC0, PC1, PC2, and PC3 to have their Domain Name Server configured
*  Tested connectivity between each PCs using the ping command and verified successful connectivity between all connected devices.
*  Saved the topology file as Bus-Topology on my Desktop and exited Cisco Packet Tracer

## Conclusion

This project helped equip me and my readers the knowledge and skills needed to create a bus topology. In my next Cisco Packet Tracer project, I intend to deliberately misconfigure one or more of the configured PCs by purposefully entering and incorrect IP address or subnet mask, or cable connection. I will then, attempt to troubleshoot the connectivity issues using command such as ping. Additionally, I am going to create topologies, such as Star, Ring, Mesh, etc. to design an enterprise style network topology.


