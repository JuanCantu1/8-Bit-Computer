## 8-Bit Computer Project

### Introduction
Welcome to the 8-Bit Computer project! Within this repository lies the culmination of my expertise in computer architecture, digital logic design, and assembly language programming. Here, you'll find everything you need to construct a fully-functional 8-bit computer system from the ground up, including meticulously crafted source code, detailed schematics, and comprehensive documentation. This project not only showcases my proficiency in these domains but also serves as a testament to my dedication to excellence and innovation in the realm of computing.

### Clock Design
The clock is an indispensable component of the computer architecture. In this project, we have meticulously designed a versatile clock with the capability to operate in two distinct modes: Monostable and Astable.

#### Monostable Mode
In the Monostable mode, the clock cycle is manually triggered using a tactile button. With each press of the button, a clock cycle is initiated, synchronizing the system's activities seamlessly.

#### Astable Mode
Contrastingly, the Astable mode offers dynamic frequency control. By employing a potentiometer, the frequency of the clock signal can be precisely adjusted, allowing for flexible timing configurations tailored to specific computational needs.

### Schematic
Below is the schematic representation of the clock circuit:

![Clock Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/10094d70-567d-48a3-8356-e28ac095a6e1)

### Circuit Implementation
Below is the schematic built physically on a breadboard.

![Clock Circuit](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/808fbfc7-c85b-4a38-92df-f665965b8575)

### Registers Design
Registers play a crucial role in the functionality of a computer system, serving as storage units for data manipulation. In our 8-bit computer architecture, we have designed three essential registers: Register A, Register B, and the Instruction Register.

#### A Register Schematic
Here is the A Register schematic. This design ensures precise data storage and retrieval:

![A Register Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/c142b729-2b9e-4630-9a39-60845ee87669)

#### B Register Schematic
Here is the B Register schematic, designed to complement the functionality of the A Register:

![B Register Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/de4839b6-c20b-4750-891c-9199600d56e0)

#### Instruction Register Schematic
Here is the Instruction Register schematic. This is a critical component responsible for storing program instructions. We will not be using this until later:

![Instruction Register Schematic](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/320efa9c-d1ce-4989-9e10-b2eb31fa04df)

### Bus Design
Communication between registers is facilitated by the bus, a vital component that enables data transfer within the system.

#### Bus Design
Here is an illustration of the bus and how it will operate:

![Bus](https://github.com/JuanCantu1/8-Bit-Computer-/assets/109363196/0e4f028a-9382-48e1-acb3-326a6006ea80)

### 8-Bit Registers Circuit Implementation
Here is a demonstration of the computer so far. This demonstration shows us that the computer is functioning as needed:

![8 bit registers](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/2ba1e1ef-169e-4903-a4e8-6c9d3ffb5f56)

### Arithmetic Logic Unit Design
The Arithmetic Logic Unit (ALU) stands as a cornerstone in computer architecture, performing essential arithmetic and logical operations crucial for computational tasks. In our 8-bit computer system, the ALU plays a pivotal role in executing arithmetic operations on Registers A and B. Specifically, it facilitates addition and subtraction operations on these registers, empowering the system with computational capabilities.

#### ALU Schematic
Here is the ALU schematic. This is a critical component responsible for ensuring seamless arithmetic and logical operations within the system:

![ALU Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/c4485f40-ada9-43e9-b64b-74be8a38ae13)

### ALU Implementation
Here is a demonstration of the ALU, showcasing its functionality and reliability in executing arithmetic operations on Registers A and B:

![ALU Demonstration](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/0d08a7b2-3e6f-4b53-afb8-b84a3ba482fe)

### RAM Design
RAM, Random Access Memory, is a fundamental component of a computer system, responsible for temporary data storage and retrieval. In our 8-bit computer project, we have designed two essential components: the Memory Address Register (MAR) and the RAM module, both crucial for efficient data handling.

#### MAR Schematic
The MAR, or Memory Address Register, serves as a critical component responsible for facilitating memory address management within the system. Explore the schematic below:

![MAR Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/cd83211a-450b-4ddb-b0c8-0af53b6fee38)

### RAM Module Schematic
The RAM module forms the backbone of our system's memory infrastructure, providing fast and efficient data storage capabilities. View the Schematic below:

![RAM Module Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/d8439fca-9d91-4470-ab09-fff7ef7d6428)

### RAM Implementation
Here is a physical implementation of the RAM module on the breadboard, showcasing its integration into our project:

![RAM Implementation](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/9900f0a7-4a22-4da3-8dad-d137fdda826b)

### Program Counter Design
The Program Counter (PC) is a vital component of any computer system, responsible for keeping track of the memory address of the next instruction to be executed.

#### PC Schematic
The Schematic is shown below:

![PC Schematic](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/5384e9a1-3b24-4d55-be34-0303c068475b)

### PC Implementation
The PC being implemented in our project is shown below:

![PC Implementation](https://github.com/JuanCantu1/8-Bit-Computer/assets/109363196/e8028d8e-09ce-4115-aad7-9be6598a1bed)
