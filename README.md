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

**Description:** These diagrams describe the sequence of actions in the automated ticket sales system via the Sports Arena website, including interactions with a third-party payment system and a bank. Designed primarily for business management.

Included:
- A parent process: `Sports Arena Event Ticketing Process`
- A reusable sub-process: `Initiate Third-Party Payment`
- Three nested reusable sub-processes:
  - `Process Payment Authorization`
  - `Process Bank Authorization`
  - `Process Bank Response and Finalize Payment`

* **Source File:** `03_BPMN_Processes/BPMN__Sports_Arena_Event_Ticketing_System.bpm`
* **Diagram Files:**
  - `03_BPMN_Processes/Sports Arena Event Ticketing Process.pdf`
  - `03_BPMN_Processes/Initiate Third-Party Payment.pdf`
  - `03_BPMN_Processes/Process Payment Authorization.pdf`
  - `03_BPMN_Processes/Process Bank Authorization.pdf`
  - `03_BPMN_Processes/Process Bank Response and Finalize Payment.pdf`

* **Notation:** BPMN
* **Tool:** Bizagi

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

## 📸 Preview Example (Optional)

Add a visual preview of a key diagram for instant context:

```markdown
### Preview: Sports Arena Event Ticketing Process (BPMN)

![BPMN Example](03_BPMN_Processes/Sports%20Arena%20Event%20Ticketing%20Process.png)
