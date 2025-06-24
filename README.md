# Automated Ticketing System Implementation Project – Sports Arena (USA)

This repository showcases a complete set of documentation and models developed for the setup and deployment of an automated ticketing system within a major sports arena in the United States.

The project provides a comprehensive overview of the business context, functional requirements, process flows, and implementation planning necessary for a successful system integration.

---

## 📦 Project Deliverables

This repository contains the following key artifacts, organized for clarity and easy navigation:

### 1. Organizational Chart

**Description:** A detailed organizational chart representing the arena's key departments, roles, and hierarchical reporting lines. This structure provides essential context for understanding process ownership, accountability, and the internal operational landscape influenced by the new ticketing system.

* **Diagram File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.pdf`
* **Source File:** `01_Organizational_Structure/Organizational_Chart__Sports_Arena.adf` 
* **Tool:** ARIS Express

---

### 2. Core Processes & Supporting Processes (VAD)

**Description:** A high-level overview of the arena's core and supporting business processes, modeled using the **Value Added Chain Diagram (VAD)** notation in ARIS Express. This diagram illustrates the sequential flow of activities that create value for the customer (core processes) and the essential internal operations that enable them (supporting processes).

* **Diagram File:** `02_VAD_Processes/Main_Processes__Sport_Arena.pdf`
* **Source File:** `02_VAD_Processes/Main_Processes__Sport_Arena.adf`

* **Diagram File:** `02_VAD_Processes/Supporting_Processes__Sports_Arena.pdf`
* **Source File:** `02_VAD_Processes/Supporting_Processes__Sports_Arena.adf`

* **Notation:** VAD
* **Tool:** ARIS Express

---

### 3. Business Process Models (BPMN)

**Description:** This section presents a complete BPMN model of the automated ticketing process at the Sports Arena, including interactions with a third-party payment system and a bank. The diagrams provide a visual representation of all key activities involved in online ticket purchases. The main process and all reusable subprocesses are modeled using BPMN 2.0 notation in Bizagi Modeler.

The following five diagrams are provided both as high-resolution `.png` previews for immediate viewing and as `.pdf` files for detailed inspection or printing. All image and document files are located in the `03_BPMN_Processes/` folder.

#### 🔹 Main Process

**Title:** Sports Arena Event Ticketing Process  
![Main Process](03_BPMN_Processes/BPMN__Sports_Arena_Event_Ticketing_System.png)  
*Files:*  
- `BPMN__Sports_Arena_Event_Ticketing_System.png`  
- `Sports Arena Event Ticketing Process.pdf`

#### 🔹 Reusable Sub-Process

**Title:** Initiate Third-Party Payment  
![Subprocess 1](03_BPMN_Processes/BPMN__Initiate%20Third-Party%20Payment.png)  
*Files:*  
- `BPMN__Initiate Third-Party Payment.png`  
- `Initiate Third-Party Payment.pdf`

#### 🔹 Nested Reusable Sub-Processes

**Title:** Process Payment Authorization  
![Subprocess 2](03_BPMN_Processes/BPMN__Process%20Payment%20Authorization.png)  
*Files:*  
- `BPMN__Process Payment Authorization.png`  
- `Process Payment Authorization.pdf`

**Title:** Process Bank Authorization  
![Subprocess 3](03_BPMN_Processes/BPMN__Process%20Bank%20Authorization.png)  
*Files:*  
- `BPMN__Process Bank Authorization.png`  
- `Process Bank Authorization.pdf`

**Title:** Process Bank Response and Finalize Payment  
![Subprocess 4](03_BPMN_Processes/BPMN__Process%20Bank%20Response%20and%20Finalize%20Payment.png)  
*Files:*  
- `BPMN__Process Bank Response and Finalize Payment.png`  
- `Process Bank Response and Finalize Payment.pdf`

* **Source File:** `03_BPMN_Processes/BPMN__Sports_Arena_Event_Ticketing_System.bpm`  
* **Notation:** BPMN 2.0  
* **Tool:** Bizagi Modeler


---

### 4. System Functionality (UML Use Case Diagram)

**Description:** A UML Use Case diagram defining the functional scope of the ticketing system. It identifies key actors (e.g., `Customer`, `3rd Party Payment System`, `Bank`, `Sports Arena Management System`) and their interactions with core functionalities (`Purchase Tickets`, `Process Customer Payment`, `Issue Tickets`, `Cancel Reservation`, `Notify Customer`, etc.).

* **Diagram File:** `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.pdf` 
* **Source Files:**
  - `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.uml`
  - `04_UML_Use_Case/Use_Case__Sports_Arena__Event_Ticket_System.xmi`

* **Notation:** UML
* **Tool:** Modelio

---

### 5. Project Plan

**Description:** A high-level implementation plan outlining the project phases, key tasks, estimated timelines, resource needs, and risks related to deployment of the automated ticketing system.

* **Document File:** `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pdf`
* **Source Files:**
  - `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pod`
  - `05_Project_Plan/Implementation_and_Customization__Automated_Ticket_Sales_System__Sports_Arena.pod.xml`

---

## 🗂 How to Navigate This Repository

* Each deliverable is placed in a dedicated folder (e.g., `01_Organizational_Structure/`).
* Diagrams are available in PDF format for quick access.
* Original source files are included for editing in modeling tools.

---

## 🧰 How to Open Source Files

| File Type | Tool |
|-----------|------|
| `.adf`    | [ARIS Express](https://www.ariscommunity.com/aris-express) |
| `.bpmn`   | [Bizagi Modeler](https://www.bizagi.com/) |
| `.uml`, `.xmi` | [Modelio](https://www.modelio.org/) |
| `.pod`, `.pod.xml` | Compatible project management tools (custom/enterprise) |

---

![BPMN Example](03_BPMN_Processes/Sports%20Arena%20Event%20Ticketing%20Process.png)
