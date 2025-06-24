# Automated Ticketing System Implementation Project - Sports Arena (USA)

This repository showcases a complete set of documentation and models developed for the setup and deployment of an automated ticketing system within a major sports arena in the United States.

The project aims to provide a comprehensive overview of the business context, functional requirements, process flows, and implementation planning necessary for a successful system integration.

## Project Deliverables

This repository contains the following key artifacts, organized for clarity and easy navigation:


### 1. Organizational Chart

**Description:** A detailed organizational chart representing the arena's key departments, roles, and hierarchical reporting lines. This structure provides essential context for understanding process ownership, accountability, and the internal operational landscape influenced by the new ticketing system.

* **Diagram File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.pdf`
* **Source File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.adf` 
* **Tool:** ARIS Express


### 2. Core Processes; Supporting Processes (VAD)

**Description:** A high-level overview of the arena's core and supporting business processes, modeled using the **Value Added Chain Diagram (VAD)** notation in ARIS Express. This diagram illustrates the sequential flow of activities that create value for the customer (core processes) and the essential internal operations that enable them (supporting processes), providing a holistic view of the arena's core value chain and how its key activities are interconnected.

* **Diagram File:** `02_VAD_Processes/Main_Processes__Sport_Arena.pdf`
* **Source File:** `02_VAD_Processes/Main_Processes__Sport_Arena.adf`

* **Diagram File:** `02_VAD_Processes/Supporting_Processes__Sports_Arena.pdf`
* **Source File:** `02_VAD_Processes/Supporting_Processes__Sports_Arena.adf`

* **Notation:** VAD
* **Tool:** ARIS Express


### 3. Business Process Models (BPMN)

**Description:** This diagram describes the sequence of actions of the automated ticket sales system via the Sports Arena website, in interaction with a third-party payment system and a bank. The diagram is intended for business management of the Sports Arena.

This file contains a diagram of a parent process called "Sports Arena Event Ticketing Process". It also contains diagrams of a reusable sub-process called "Initiate Third-Party Payment" , which is part of the parent process. It also contains diagrams of three reusable sub-processes that are part of the above-mentioned "Initiate Third-Party Payment" sub-process: "Process Payment Authorization", "Process Bank Authorization', "Process Bank Response and Finalize Payment".

* **Source File** `03_BPMN_Processes/BPMN__Sports_Arena_Event_Ticketing_System.bpm`
* **Diagram File:** `03_BPMN_Processes/Sports Arena Event Ticketing Process.pdf`
* **Diagram File:** `03_BPMN_Processes/Initiate Third-Party Payment.pdf`
* **Diagram File:** `03_BPMN_Processes/Process Payment Authorization.pdf`
* **Diagram File:** `03_BPMN_Processes/Process Bank Authorization.pdf`
* **Diagram File:** `03_BPMN_Processes/Process Bank Response and Finalize Payment.pdf`

* **Notation** BPMN
* **Tool:** Bizagi


### 4. System Functionality (UML Use Case Diagram)

* **Description:** A comprehensive UML Use Case diagram defining the functional scope of the automated ticketing system. It identifies key actors (e.g., `Customer`, `3rd Party Payment System`, `Bank`, `Sports Arena Management System`) and their interactions with core system functionalities (`Purchase Tickets`, `Process Customer Payment`, `Issue Tickets`, `Cancel Reservation`, `Notify Customer of Purchase`, `Notify Customer of Payment Failure`).
* **Diagram File:** `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.pdf` 
* **Source File:** `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.uml`
* **Source File:** `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.xmi`
* **Notation:** UML
* **Tool:** Modelio


### 5. Project Plan


**Description:** A high-level project plan outlining the critical phases, key tasks, estimated timelines, required resources, and identified risks associated with the successful configuration, integration, and deployment of the new automated ticketing system within the arena's operational environment. This plan provides a roadmap for bringing the system into production.

* **Document File:** `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pdf`
* **Source File:** `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pod`
* **Source File:** `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pod.xml`

---

### How to Navigate This Repository

* Each deliverable is placed in its dedicated folder (e.g., `01_Organizational_Structure/`).
* Diagrams are available in common image/PDF formats for easy viewing.
* **Original source files are provided for detailed analysis, modification, or import into respective modeling tools.**

---
