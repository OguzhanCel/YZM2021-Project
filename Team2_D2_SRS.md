# SOFTWARE REQUIREMENTS SPECIFICATION  
## 2D SWORD & SHIELD FIGHTING GAME  

---

## TABLE OF CONTENTS  
1. [Introduction](#1-introduction)  
2. [Overall Description](#2-overall-description)  
3. [Functional Requirements](#3-functional-requirements)  
   - [3.1 User Stories](#31-user-stories)  
   - [3.2 Use Cases](#32-use-cases-optional-but-recommended)  
   - [3.3 Functional Requirements List](#33-functional-requirements-list)  
4. [Non-Functional Requirements](#4-non-functional-requirements)  
   - [4.1 Performance Requirements](#41-performance-requirements)  
   - [4.2 Security Requirements](#42-security-requirements)  
   - [4.3 Usability Requirements](#43-usability-requirements)  
   - [4.4 Reliability and Availability](#44-reliability-and-availability)  
   - [4.5 Maintainability Requirements](#45-maintainability-requirements)  
   - [4.6 Compatibility Requirements](#46-compatibility-requirements)  
5. [System Models (Diagrams)](#5-system-models-diagrams)
   
---

## 1. INTRODUCTION  
Provide context and scope for your requirements document.

1. **Purpose:** What is the purpose of this SRS document?  
2. **Document Conventions:** Any special notations or terminology used  
3. **Intended Audience:** Who should read this document? (developers, testers, users, project managers)  
4. **Project Scope:** Brief summary of what the system will and won't do  
5. **References:** Any documents, standards, or resources referenced (link to your D1 - SDP)  

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

