# SOFTWARE REQUIREMENTS SPECIFICATION  
## 2D SWORD & SHIELD FIGHTING GAME  

---

## 1. INTRODUCTION  

### 1.1 Purpose
The purpose of this document is to clearly define the **software requirements** for our project.  
This document serves as a **structured guide** for the development process, helping to ensure that the project meets its intended **goals** and **functionality**.  
It is intended for the **course instructor** who will review the assignment, as well as for the **developers** as a reference during implementation and testing.

### 1.2 Document Conventions
**Bold text indicates important features and terms.**  
Functional requirements are numbered as **FR-x**, and non-functional requirements as **NFR-x**.  
 
*Terminology specific to the game:*  
- **Dash:** A quick horizontal movement for repositioning and spacing.  
- **Attack:** Player strikes in upward, horizontal, or downward directions.  
- **Defend:** Blocking attacks from different directions.  
- **Tutorial:** A short introductory guide that explains core mechanics.   
- **HP (Health Points):** A numerical value representing player vitality.
  
### 1.3 Intended Audience
- **Course Instructor:** To review the assignment and check whether the project meets the defined requirements.  
- **Developers:** To use this document as a reference during the design, implementation, and testing, and to understand system features and implementation requirements.

### 1.4 Project Scope
**In Scope:**  
- 1v1 local multiplayer gameplay with sword and shield combat mechanics.  
- Player actions: movement (right or left), dash (right or left), attacking (upward, horizontal, downward), and defending (upward, horizontal, downward).  
- Game menus: Main Menu, Options, Tutorial, Credits, and Pause Menu.  
- Game results: match end screen with options to rematch or return to the main menu.  
- Audio and resolution settings adjustable in the Options menu.  

**Out of Scope:**  
- AI-controlled opponents.  
- Multiple playable characters.  
- Online multiplayer functionality.
  
 ### 1.5 References
- **Team2_D1_SDP.pdf** – Software Development Plan for the 2D Sword & Shield Fighting Game.
[Team2_D1_SDP.pdf](https://github.com/OguzhanCel/YZM2021-Project/blob/main/Team2_D1_SDP.pdf) 
- **README.md** – Project overview and feature summary.-
[README.md](https://github.com/OguzhanCel/YZM2021-Project/blob/main/README.md)
- **Godot Engine Documentation** – Official documentation for the Godot 4.x engine.  
[https://docs.godotengine.org](https://docs.godotengine.org)  

---

## 2. OVERALL DESCRIPTION  
Provide a high-level view of the product and its context.

1. **Product Perspective:** How does your system fit into the larger ecosystem? Does it integrate with other systems?  
2. **Product Functions:** Summary list of major functions (bullet points)  
3. **User Classes and Characteristics:** Who are your users? (e.g., students, administrators, guests). Describe their technical expertise and needs.  
4. **Operating Environment:** Where will the system run? (web browsers, mobile devices, operating systems)  
5. **Design and Implementation Constraints:** Any limitations or restrictions (e.g., must use specific APIs, budget constraints, regulatory requirements)  
6. **Assumptions and Dependencies:** What are you assuming? What external factors does your project depend on?  

---

## 3. FUNCTIONAL REQUIREMENTS  
This is the core of your SRS. Describe what the system will do.

### 3.1 User Stories (15–25 stories)  
Write user stories in the following format:

> As a [user role]  
> I want to [goal/desire]  
> So that [benefit/value]

**Acceptance Criteria:**  
- Given [context]  
- When [action]  
- Then [expected result]

**Requirements:**  
- Write at least 15–25 user stories covering all major features  
- Each story must have acceptance criteria (2–5 criteria per story)  
- Prioritize stories using MoSCoW method (Must have, Should have, Could have, Won't have)  
- Group stories by feature area or epic  

**Example:**  


### 3.2 Use Cases (Optional but Recommended)  
For complex workflows, provide use case descriptions:

- Use Case ID and Name  
- Actor(s)  
- Preconditions  
- Main Flow (step-by-step)  
- Alternative Flows  
- Postconditions  

Include use case diagrams showing relationships between actors and use cases.  

---

### 3.3 Functional Requirements List  
Organize requirements by feature/module. Number each requirement (e.g., FR-1, FR-2, FR-3).

**Example:**  
- FR-1: The system shall allow users to register using email and password  
- FR-2: The system shall send email verification after registration  
- FR-3: The system shall allow users to reset password via email  

---

## 4. NON-FUNCTIONAL REQUIREMENTS  
Specify quality attributes and constraints.

### 4.1 Performance Requirements  
- Response time expectations (e.g., "Page load time < 2 seconds")  
- Throughput requirements (e.g., "Support 100 concurrent users")  
- Resource usage limits  

### 4.2 Security Requirements  
- Authentication and authorization requirements  
- Data encryption requirements  
- Privacy requirements (e.g., GDPR, KVKK compliance)  
- Password policies  

### 4.3 Usability Requirements  
- User interface standards  
- Accessibility requirements (e.g., WCAG compliance)  
- Learning curve expectations  
- Help and documentation requirements  

### 4.4 Reliability and Availability  
- System uptime requirements (e.g., "99% availability")  
- Fault tolerance requirements  
- Backup and recovery requirements  

### 4.5 Maintainability Requirements  
- Code quality standards  
- Documentation requirements  
- Modularity and extensibility needs  

### 4.6 Compatibility Requirements  
- Browser compatibility (which browsers and versions?)  
- Mobile device compatibility  
- Operating system compatibility  

---

## 5. SYSTEM MODELS (DIAGRAMS)  
Provide visual models to illustrate system behavior and structure.  
You can use draw.io or Mermaid for diagrams.

**Required:**  
1. **Use Case Diagram:** Show actors and their interactions with the system  
2. **User Flow Diagram:** Show how users navigate through key scenarios  

---

## TEAM MEMBERS  

**PROJECT MANAGER and CORE SYSTEMS ENGINEER:**  
Oğuzhan Çelik  

**GAMEPLAY ENGINEER:**  
Yunus Emre Yılmaz  

**MENU and UI ENGINEER:**  
Tuğana Öykü Yıldız  

