# Requirement Analysis
A project helps define and organize requirements for a booking system, building a clear plan for software development.

## What is Requirement Analysis?

**Requirement Analysis** is the process of gathering, analyzing, validating, and documenting what a software system must do and the conditions it must meet. It ensures that developers build the right product that meets user and business needs.

Requirement Analysis plays a crucial role in the **Software Development Lifecycle (SDLC)** because it sets the foundation for all subsequent stages of development.

#### **1. Defines Project Scope**
It helps identify what the system should accomplish, who will use it, and what problems it aims to solve. Clear scope prevents confusion and scope creep later in development.

#### **2. Improves Communication**
By documenting requirements, all stakeholders, including clients, developers, and testers, share a common understanding of project goals and expectations.

#### **3. Reduces Development Errors**
Thorough analysis minimizes misunderstandings, rework, and feature misalignment, saving both time and resources.

#### **4. Ensures Better Quality**
Well-defined and validated requirements lead to a product that meets user needs, performs efficiently, and aligns with business objectives.

#### **5. Supports Testing and Validation**
Test cases are built around the documented requirements, ensuring each function can be verified against its intended purpose.

## Why is Requirement Analysis Important?

Requirement Analysis is a critical phase in the **Software Development Lifecycle (SDLC)** because it ensures that the software being built aligns with user needs, business goals, and technical feasibility. Without it, projects risk failure due to unclear objectives or misaligned expectations.

### **1. Prevents Miscommunication and Scope Creep**
Clear and well-documented requirements create a shared understanding between developers, clients, and stakeholders.  
This minimizes confusion, reduces rework, and prevents the project scope from expanding beyond what was originally planned.

### **2. Saves Time and Resources**
By identifying issues, constraints, and missing information early in the development process, teams can avoid costly redesigns and delays later on.  
Good requirement analysis streamlines development, improves estimation accuracy, and ensures efficient resource allocation.

### **3. Ensures Product Quality and User Satisfaction**
Thoroughly analyzed and validated requirements lead to software that truly meets user expectations and business objectives.  
When the team clearly understands *what* to build and *why*, the result is a more reliable, usable, and high-quality product.

### **4. Supports Better Testing and Validation**
Requirements provide the basis for creating test cases and acceptance criteria.  
This makes it easier to verify that each feature works as intended and that the final product fulfills its intended purpose.

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that help transform stakeholder needs into clear and actionable requirements.  
Below are the **five key activities** involved in this process:

- ### **1. Requirement Gathering**
  - This is the initial step where information about the project and user expectations is collected.
  - It involves identifying stakeholders and using tools such as surveys, interviews, and questionnaires.
  - The goal is to collect raw data about what the system should achieve.

- ### **2. Requirement Elicitation**
  - Elicitation focuses on understanding and refining the gathered information.
  - It includes direct discussions, brainstorming sessions, and observation of user workflows.
  - The main objective is to uncover hidden needs, clarify assumptions, and resolve conflicts among stakeholders.

- ### **3. Requirement Documentation**
  - All requirements are recorded in a structured and organized format, such as a Software Requirement Specification (SRS) document.
  - Documentation ensures clarity and serves as a reference point for designers, developers, and testers.
  - It includes both **functional** and **non-functional** requirements.

- ### **4. Requirement Analysis and Modeling**
  - This activity involves analyzing, prioritizing, and modeling requirements to ensure they are feasible, consistent, and aligned with project goals.
  - Techniques like **use case diagrams**, **data flow diagrams (DFDs)**, and **entity-relationship diagrams (ERDs)** are often used.
  - The outcome is a clear representation of how the system will function and interact with users or other systems.

- ### **5. Requirement Validation**
  - Validation confirms that the documented requirements accurately reflect stakeholder needs.
  - It involves reviews, walkthroughs, and prototype testing to verify correctness and completeness.
  - The aim is to ensure that the final software will meet user expectations and business objectives.

## Types of Requirements

### Functional Requirements

Functional requirements define what the system should do — the specific features, operations, and behaviors the application must support.

#### Examples for a Hotel Booking Management System:

- **Search Functionality**: Users should be able to search for available rooms by location, date, and number of guests.

- **Booking Management**: The system should allow users to select a room, book it, and make payments securely.

- **Host Management**: Hotel managers should be able to update room availability, pricing, and details.

- **Notifications**: The system should send booking confirmations and cancellation messages to users and hotel managers.

- **User Profile Management**: Users should be able to view and manage their bookings and personal details.

### Non-Functional Requirements

Non-functional requirements define how the system performs its functions — focusing on performance, security, reliability, and usability.

#### Examples for a Hotel Booking Management System:

- **Performance**: The system should load search results in under 500 milliseconds.

- **Scalability**: It should handle thousands of concurrent users during peak times.

- **Security**: All user credentials and payment details must be encrypted and securely stored.

- **Availability**: The system should maintain 99.9% uptime to ensure continuous booking access.

- **Data Consistency**: The system must prevent double-booking of the same room.

## Use Case Diagrams

Use Case Diagrams are visual representations that illustrate the interaction between users (actors) and system functionalities (use cases). They help identify the key processes in a system and show how different roles interact with those processes.

### Benefits of Use Case Diagrams:

- **Clarity**: They simplify complex system interactions, making it easy to understand how the system works at a glance.

- **Communication**: They provide a common language between technical and non-technical stakeholders.

- **Scope Definition**: They help define system boundaries and ensure that all user interactions are captured.

- **Requirement Validation**: They serve as a reference to verify if all functional requirements are addressed.

### Use Case Diagram
[Diagram](https://iili.io/K4ue9Uu.png)

### Actors in the Booking System

**Guest**: Searches, books, makes payment and manages bookings.

**Host**: Manages bookings, availability, and pricing.

**Management Company**: Review host properties, mediates conflicts, and ensures data integrity.
