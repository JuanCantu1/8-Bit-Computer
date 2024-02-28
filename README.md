## 8-Bit Computer Project

### Introduction: Welcome to the 8-Bit Computer project! Within this repository lies the culmination of my expertise in computer architecture, digital logic design, and assembly language programming. Here, you'll find everything you need to construct a fully-functional 8-bit computer system from the ground up, including meticulously crafted source code, detailed schematics, and comprehensive documentation. This project not only showcases my proficiency in these domains but also serves as a testament to my dedication to excellence and innovation in the realm of computing.

### Clock Design:
The clock is an indispensable component of the computer architecture. In this project, we have meticulously designed a versatile clock with the capability to operate in two distinct modes: Monostable and Astable.

#### Monostable Mode:
In the Monostable mode, the clock cycle is manually triggered using a tactile button. With each press of the button, a clock cycle is initiated, synchronizing the system's activities seamlessly.

#### Astable Mode:
Contrastingly, the Astable mode offers dynamic frequency control. By employing a potentiometer, the frequency of the clock signal can be precisely adjusted, allowing for flexible timing configurations tailored to specific computational needs.

### Schematic:
Below is the schematic representation of the clock circuit:

![Clock Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/10094d70-567d-48a3-8356-e28ac095a6e1)

### Circuit Implementation:
Below is the schematic built physically on a breadboard.

![Clock Circuit](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/808fbfc7-c85b-4a38-92df-f665965b8575)

### Registers Design:
Registers play a crucial role in the functionality of a computer system, serving as storage units for data manipulation. In our 8-bit computer architecture, we have designed three essential registers: Register A, Register B, and the Instruction Register.

#### A Register Schematic:
Here is the A Register schematic. This design ensures precise data storage and retrieval:

![A Register Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/c142b729-2b9e-4630-9a39-60845ee87669)

#### B Register Schematic:
Here is the B Register schematic, designed to complement the functionality of the A Register:

![B Register Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/cd594bbe-aeb6-4327-a6ad-81137fd53a42)

#### Instruction Register Schematic:
Here is the Instruction Register schematic. This is a critical component responsible for storing program instructions. We will not be using this until later:

![Instruction Register Schematic ](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/320efa9c-d1ce-4989-9e10-b2eb31fa04df)

### Bus Design:
Communication between registers is facilitated by the bus, a vital component that enables data transfer within the system.

#### Bus Design:
Here is an illustration of the bus and how it will operate:

![Bus](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/0e4f028a-9382-48e1-acb3-326a6006ea80)


### 8-Bit Registers Circuit Implementation:
Here is a demonstration of the computer so far. This demonstration shows us that the computer is functioning as needed:

![8 bit registers](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/abc81db9-34c9-42e9-b01b-fef3d7bc36a0)


### Arithmetic Logic Unit Design:
The Arithmetic Logic Unit (ALU) stands as a cornerstone in computer architecture, performing essential arithmetic and logical operations crucial for computational tasks. In our 8-bit computer system, the ALU plays a pivotal role in executing arithmetic operations on Registers A and B. Specifically, it facilitates addition and subtraction operations on these registers, empowering the system with computational capabilities.

#### ALU Schematic:
Here is the ALU schematic. This is a critical component responsible for ensuring seamless arithmetic and logical operations within the system:

![ALU Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/c4485f40-ada9-43e9-b64b-74be8a38ae13)

### ALU Implementation:
Here is a demonstration of the ALU, showcasing its functionality and reliability in executing arithmetic operations on Registers A and B:

![ALU Demonstration](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/0d08a7b2-3e6f-4b53-afb8-b84a3ba482fe)




### RAM Design:
RAM, Random Acesss Memory, is... For this module we designed two differet components, the MAR, (Memory Address Register) and the RAM module. The MAR is... The RAM Module is...

#### MAR Schematic:
Here is the MAR schematic. This is a critical component responsible for...:

![MAR Schematic ](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/cd83211a-450b-4ddb-b0c8-0af53b6fee38)


### RAM Module Schematic:
Here is a schematic of the RAM module:

![RAM Module Schematic ](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/d8439fca-9d91-4470-ab09-fff7ef7d6428)


### RAM Implementation:
Here is the RAM being implemented on the breadboard for our project:

![RAM](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/9900f0a7-4a22-4da3-8dad-d137fdda826b)

