# Automated Ticketing System Implementation Project - Sports Arena (USA)

This repository showcases a complete set of documentation and models developed for the setup and deployment of an automated ticketing system within a major sports arena in the United States.

The project aims to provide a comprehensive overview of the business context, functional requirements, process flows, and implementation planning necessary for a successful system integration.

## Project Deliverables

This repository contains the following key artifacts, organized for clarity and easy navigation:

### 1. Organizational Structure

**Description:** A detailed organizational chart representing the arena's key departments, roles, and hierarchical reporting lines. This structure provides essential context for understanding process ownership, accountability, and the internal operational landscape influenced by the new ticketing system.

* **Diagram File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.pdf`
* **Source File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.adf` 
* **Tool:** ARIS Express


### 2. Core Processes; Supporting Processes (VAD)

**Description:** A high-level overview of the arena's core and supporting business processes, modeled using the **Value Added Chain Diagram (VAD)** notation in ARIS Express. This diagram illustrates the sequential flow of activities that create value for the customer (core processes) and the essential internal operations that enable them (supporting processes), providing a holistic view of the arena's core value chain and how its key activities are interconnected.

* **Diagram File (Example):** `02_VAD_Processes/Main_Processes__Sport_Arena.pdf`
* **Source File (Example):** `02_VAD_Processes/Main_Processes__Sport_Arena.adf` (or `.xml`)
* **Tool:** ARIS Express
* **Notation:** VAD

* **Diagram File (Exemple):** 03_VAD_Processes/Supporting_Processes_Sports_Arena.pdf
* **Source File (Example):** 03_VAD_Processes/Supporting_Processes__Sports_Arena.adf
* **Tool:** ARIS Express
* **Notation:** VAD


### 2. Business Process Models (BPMN)

**Description:** This diagram describes the sequence of actions of the automated ticket sales system via the Sports Arena website, in interaction with a third-party payment system and a bank. The diagram is intended for business management of the Sports Arena.

This file contains a diagram of a parent process called "Sports Arena Event Ticketing Process". It also contains diagrams of a reusable sub-process called "Initiate Third-Party Payment" , which is part of the parent process. It also contains diagrams of three reusable sub-processes that are part of the above-mentioned "Initiate Third-Party Payment" sub-process: "Process Payment Authorization", "Process Bank Authorization', "Process Bank Response and Finalize Payment".

* **Source File (Example):** `04_BPMN_Processes/Event Ticketing/Ticket_Purchase_Process.bpmn` (or `.xml` if exported from ARIS/Modelio)
* **Diagram File (Example):** `04_BPMN_Processes/Main_Processes/Ticket_Purchase_Process.pdf` (e.g., your `Sports_Arena_TSS_8.pdf`)
* **Tool:** Bizagi (or ARIS Express, specify what you used for BPMN)

### 3. System Functionality (UML Use Case Diagram)

* **Diagram File:** `03_UML_Use_Case/Use_Case_Diagram_Ticketing_System.png` (e.g., your `2025-06-18_20-22-48.png`)
* **Source File:** `03_UML_Use_Case/Use_Case_Diagram_Ticketing_System.xmi` (or `.uml` or Modelio's specific project file extension)
* **Tool:** Modelio
* **Description:** A comprehensive UML Use Case diagram defining the functional scope of the automated ticketing system. It identifies key actors (e.g., `Customer`, `Payment System`, `Bank`, `Sports Arena Management System`) and their interactions with core system functionalities (`Purchase Tickets`, `Process Customer Payment`, `Issue Tickets`, `Cancel Reservation`, `Notify Customer of Purchase`, `Notify Customer of Payment Failure`).

### 4. Project Plan

* **Document File (Example):** `04_Project_Plan/Project_Implementation_Plan_Overview.pdf` (Replace with your actual project plan file name, could be `.docx`, `.xlsx`, `.pdf`)
* **Source File (Optional):** `04_Project_Plan/Project_Implementation_Plan_Overview.mpp` (if from MS Project or similar)
* **Description:** A high-level project plan outlining the critical phases, key tasks, estimated timelines, required resources, and identified risks associated with the successful configuration, integration, and deployment of the new automated ticketing system within the arena's operational environment. This plan provides a roadmap for bringing the system into production.

---

### How to Navigate This Repository

* Each deliverable is placed in its dedicated folder (e.g., `01_Organizational_Structure/`).
* Diagrams are available in common image/PDF formats for easy viewing.
* **Original source files are provided for detailed analysis, modification, or import into respective modeling tools.**

---
