# Model 01   Bank Solutions (CFA) - 
<br><br>
<hr>
<span style="color:red"><BIG><B>✨ GROUP A ✨</B></BIG></span>
<hr>

###  <span style="color:red">i</span>. Which one of the following is not the characteristic of computer?
- a) <span style="color:green">Diligence ✅</span> 
- b) Versatile
- c) Intelligence
- d) Reliable

###  <span style="color:red">ii</span>. Which one of the following is the utility software?
- a) Skype
- b) <span style="color:green">Windows Defender ✅</span>
- c) Ms-Paint
- d) Adobe Photoshop

###  <span style="color:red">iii</span>. Which one of the following is not the type of operating system?
- a) Hierarchical
- b) <span style="color:green">Network ✅</span>
- c) Batch
- d) Multiprogramming

###  <span style="color:red">iv</span>. Which one of the following is not the attribute of information?
- a) Accuracy
- b) <span style="color:green">Redundancy ✅</span>
- c) Relevancy
- d) Timeliness

###  <span style="color:red">v</span>. Which one of the following does not belong to the OSI reference model?
- a) <span style="color:green">Network Administrator ✅</span>
- b) Internet Protocol (IP)
- c) Data Link Layer
- d) Data Presentation

###  <span style="color:red">vi</span>. Who invented WWW?
- a) Sundar Pichai
- b) <span style="color:green">Tim Berners-Lee ✅</span>
- c) Bill Gates
- d) Steve Jobs

###  <span style="color:red">vii</span>. Which one of the following is cryptocurrency?
- a) Payment Gateway
- b) PayPal
- c) Dollar
- d) <span style="color:green">Bitcoin ✅</span>

###  <span style="color:red">viii</span>. Which one of the following belongs to LMS?
- a) E-commerce
- b) E-governance
- c) E-banking
- d) <span style="color:green">E-learning ✅</span>

###  <span style="color:red">ix</span>. Which one of the following is the characteristic of DOS?
- a) 32-bit operating system
- b) <span style="color:green">16-bit operating system ✅</span>
- c) Server operating system
- d) WIMP

###  <span style="color:red">x</span>. Which one of the following is not the graphical file format?
- a) PNG
- b) BMP
- c) TIFF
- d) <span style="color:green">PPT ✅</span>


<br><br>
<hr>
<span style="color:red"><BIG><B>✨ GROUP B ✨</B></BIG></span>
<hr>

### 2. What do you mean by computer architecture? Describe the functional components of computer architecture with a block diagram.  

Computer architecture refers to the design and organization of a computer system, including its hardware components, how they interact, and how they execute instructions. It defines the structure, functionality, and performance of a computer, covering aspects like the processor, memory, input/output (I/O) devices, and data transfer mechanisms.  

## Functional Components of Computer Architecture

A computer system consists of several functional components that work together to execute tasks. The main components are:  

### i. Input Unit  
- Accepts data and instructions from external sources (e.g., keyboard, mouse).  
- Converts the input into a format the computer can process.  

### ii. Central Processing Unit (CPU)  
The **CPU** is the brain of the computer, responsible for processing and executing instructions. It comprises three main subunits:  
- **Control Unit (CU)**: Directs the flow of data and manages instruction execution.  
- **Arithmetic Logic Unit (ALU)**: Performs mathematical and logical operations.  
- **Registers**: Small, high-speed storage locations inside the CPU for temporary data storage.  

### iii. Memory Unit  
Stores data and instructions temporarily or permanently. There are two types:  
- **Primary Memory (RAM, ROM)**: Used for temporary storage while executing programs.  
- **Secondary Memory (HDD, SSD)**: Stores data permanently.  

### iv. Output Unit  
- Converts processed data into a human-readable format.  
- Examples: Monitor, printer, speaker.  

### v. Bus System  
The **bus system** transfers data between different components of the computer. It consists of:  
- **Data Bus**: Transfers actual data.  
- **Address Bus**: Carries the address of the data.  
- **Control Bus**: Transfers control signals for synchronization.  

## Block Diagram of Computer Architecture  

![image](assets/computer%20fig.jpg)
<br><br>
<hr>

### 3. Define operating system. Explain the type of operating system with their examples.
An operating system (OS) is a curical piece of software that manages the computer's hardware and software resources and provide common services to coputer program. It act as an intermediary between user and computer hardware, ensuring that application can function efficently and effectively.

# Types of Operating Systems  

## i. Network Operating System (NOS)  
- Manages network resources, allowing multiple devices to communicate and share files.  
- Ensures network security, remote access, and centralized management.  
- **Example:** Windows Server, Novell NetWare  

## ii. Mobile Operating System  
- Developed specifically for smartphones, tablets, and wearable devices.  
- Provides an interface optimized for touch and mobile applications.  
- **Example:** Android, iOS, HarmonyOS  

## iii. Embedded Operating System  
- A lightweight OS used in dedicated hardware systems.  
- Designed for specific tasks, like controlling home appliances, medical devices, and automotive systems.  
- **Example:** FreeRTOS, Windows Embedded, VxWorks  

## iv. Batch Operating System  
- In a Batch OS, similar jobs are grouped together and executed without user interaction.  
- The OS processes jobs in batches, reducing manual intervention.  
- **Example:** IBM OS/360, Windows Batch Processing  

### 4. Define DBMS. Explain the different database models with their pros and cons.
A Database Management System (DBMS) is software that is used to store, retrieve, manage, and manipulate data efficiently. It provides a structured way to organize and handle large amounts of data while ensuring security, consistency, and integrity.

## Examples of DBMS:
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server
- MongoDB

# Types of Database Models
A database model defines how data is structured, stored, and accessed in a database. There are several types of database models, each with its own advantages and disadvantages.

## i. Hierarchical Database Model  
- Data is organized in a tree-like structure with a parent-child relationship.  
- Each parent node can have multiple child nodes, but a child can have only one parent.  
- **Example:** IBM Information Management System (IMS)  

### ✅ Merits:  
- Fast data retrieval due to hierarchical structure  
- Ensures data integrity through parent-child relationships  
- Suitable for applications with a well-defined structure (e.g., organizational charts)  

### ❌ Demerits:  
- Difficult to modify the structure (changing relationships requires significant rework)  
- Redundant data due to one-parent rule  
- Not suitable for complex relationships  

---  

## ii. Network Database Model  
- Similar to the hierarchical model but allows many-to-many relationships.  
- Uses pointers (links) to connect multiple records.  
- **Example:** Integrated Data Store (IDS)  

### ✅ Merits:  
- Flexible relationships compared to hierarchical databases  
- Efficient for complex data relationships  
- Faster access due to multiple paths  

### ❌ Demerits:  
- Complex design and implementation  
- Hard to maintain due to the use of multiple pointers  
- Requires specialized knowledge for querying  

---  

## iii. Relational Database Model (RDBMS)  
- Data is stored in tables (relations) consisting of rows and columns.  
- Uses keys (Primary Key, Foreign Key) to establish relationships.  
- **Examples:** MySQL, PostgreSQL, Oracle, SQL Server  

### ✅ Merits:  
- Simple and widely used model  
- Supports SQL for efficient querying  
- Eliminates redundancy through normalization  
- Ensures data integrity and security  

### ❌ Demerits:  
- Can be slow for complex queries on large datasets  
- Schema (table structure) must be predefined  
- Not ideal for unstructured or hierarchical data  

---  

## iv. Object-Oriented Database Model (OODBMS)  
- Stores data in the form of objects (like in OOP languages such as Java, C++).  
- Objects include both data (attributes) and behavior (methods).  
- **Examples:** db4o, ObjectDB  

### ✅ Merits:  
- Supports complex data types (images, multimedia)  
- Well-suited for OOP-based applications  
- Reduces the mismatch between programming objects and database structures  

### ❌ Demerits:  
- Not as popular as RDBMS  
- Learning curve is steep for relational database users  
- Slower querying compared to relational models  

---  

## v. Document-Oriented Database Model (NoSQL)  
- Data is stored as documents in JSON, BSON, or XML formats.  
- Flexible structure, allowing schema-less data storage.  
- **Examples:** MongoDB, CouchDB  

### ✅ Merits:  
- Handles unstructured data efficiently  
- Scalable and fast for large datasets  
- Ideal for Big Data, IoT, and real-time applications  

### ❌ Demerits:  
- No strict relationships like RDBMS  
- Complex queries can be difficult to manage  
- Less support for standard query languages like SQL  
