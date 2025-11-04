# My-First-Automation-Wayfair-Externship-
Built an automated workflow using n8n that runs on a scheduled trigger, executes custom logic via JavaScript, and routes data through conditional paths using an If node. This workflow demonstrates event-based automation, dynamic decision-making, and branching logic — foundational skills for AI agent and cloud automation design.

# 🤖 My First Automation Workflow

**Platform:** n8n  
**Tech Stack:** JavaScript • Conditional Logic • Workflow Automation  
**Status:** Completed (Wayfair Externship – Module 1)

---

## 🧭 Overview
This project demonstrates a foundational automation workflow built in **n8n**, featuring scheduled triggers, inline JavaScript processing, and conditional branching with dynamic data output.  
It serves as the base framework for future **AI-powered and multi-cloud automation projects.**

---

## ⚙️ Workflow Components

### 🕒 1. Schedule Trigger
Initiates the workflow automatically at defined intervals — simulating real-world, event-driven automations such as:
- Daily health checks  
- Data refresh routines  
- Alert system triggers  

### 🧩 2. Code in JavaScript
Executes a custom script to define and manipulate data before evaluation.  
This introduces programmable control inside a visual workflow environment.

### 🔀 3. If Node
Applies conditional logic to determine which execution path to follow:
```text
If condition == true → perform Action A  
Else → perform Action B

### 🧠 4. Edit Fields (True/False Branches)

## 📸 Screenshots
| Workflow Overview | Conditional Output |
|--------------------|-------------------|
| ![Workflow Diagram](images/01_First_Automation_Workflow.png) | ![Output Node](images/02_Conditional_Output_Node.png) |

| True Branch Output | False Branch Output |
|--------------------|--------------------|
| ![True Branch](images/03_True_Branch_Output.png) | ![False Branch](images/04_False_Branch_Output.png) |

