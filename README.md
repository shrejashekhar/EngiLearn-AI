

# **EngiMentor AI**

**EngiMentor AI** is an AI-powered instructor system designed to help college students learn technical and engineering subjects more effectively. Built using **Large Language Models (LLMs)** and the **LangChain framework**, the system follows a **multi-agent architecture inspired by CAMEL**, enabling collaborative reasoning and adaptive instruction.

The project tackles a common challenge faced by students: the absence of personalized guidance and structured learning paths when studying complex topics. Instead of relying on generic learning resources, EngiMentor AI dynamically generates a customized syllabus and delivers step-by-step instruction tailored to individual learning goals.

---

## **Problem Statement**

Many college students struggle with:

* Unstructured learning resources
* Lack of personalized mentorship
* Difficulty breaking down complex technical subjects

Traditional learning platforms often provide static content that does not adapt to a learner’s pace or objectives. **EngiMentor AI bridges this gap by acting as a personalized AI instructor**, guiding students through a structured and interactive learning journey.

---

## **Solution Overview**

EngiMentor AI employs a **multi-agent collaboration model** where:

* Two AI agents work together to analyze a student’s learning objectives and design a customized syllabus.
* A dedicated instructor agent then teaches the content in a logical, step-by-step manner based on the generated syllabus.

This approach enables **personalized, adaptive, and self-paced learning**, making complex topics easier to understand and retain.

---

## **Key Features**

### **Collaborative Agent-Based Syllabus Design**

Two role-based AI agents engage in a guided discussion to analyze the learner’s goals and generate a well-structured, goal-aligned syllabus.

### **Adaptive Instructor Agent**

A dedicated instructor agent delivers lessons according to the generated syllabus, adjusting its explanations and pace based on the learner’s needs.

### **Interactive Learning Experience**

Learners can continuously interact with the instructor agent, ask questions, and receive clear explanations supported by natural language reasoning.

---

## **System Architecture**

The system follows a structured multi-agent workflow:

1. **Agent Initialization**
   Multiple AI agents are initialized with predefined roles, responsibilities, and domain knowledge.

2. **Understanding User Input**
   The system processes the user’s topic or learning objective using carefully designed prompts.

3. **Agent Collaboration & Dialogue**
   Two AI agents interact and reason collaboratively to identify key concepts and organize them logically.

4. **Syllabus Generation**
   A Large Language Model generates a comprehensive, structured syllabus based on the agents’ conversation and the learner’s goals.

5. **Instructor Agent Activation**
   Once the syllabus is finalized, an instructor agent guides the learner through the content step by step.

Through this multi-agent collaboration and adaptive teaching mechanism, EngiMentor AI delivers a dynamic and personalized educational experience.

---

## **Tech Stack**

* **Large Language Models (LLMs)**
* **LangChain**
* **Multi-Agent Systems (CAMEL-inspired architecture)**
* **Python**
* **OpenAI API**

---

## **Installation**

Ensure **Python 3.10 or later** is installed.

Create and activate a virtual environment:

```bash
make venv
```

Create a `.env` file in the project root and add your OpenAI API key:

```env
OPENAI_API_KEY=sk-xxxx
```

---

## **Usage**

To start the AI Instructor system, run:

```bash
python src/run.py
```

---



