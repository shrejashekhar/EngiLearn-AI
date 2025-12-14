EngiMentor AI is an AI-powered instructor system designed to support college students in learning technical and engineering subjects more effectively. Built using Large Language Models (LLMs) and the LangChain framework, the system follows a multi-agent approach inspired by CAMEL architecture.

The project addresses a common challenge faced by college students: the lack of personalized guidance and structured learning paths when studying complex subjects. Instead of relying on generic resources, EngiMentor AI uses two collaborating AI agents to analyze a student’s learning goals and automatically generate a well-structured syllabus. A dedicated instructor agent then teaches the content step by step based on this syllabus.

By combining collaborative syllabus generation with adaptive instruction, the system provides a personalized, interactive, and self-paced learning experience, helping students understand topics more clearly and study more efficiently.

The EngiMentor AI project explores a modern approach to learning by integrating artificial intelligence into the educational process. Instead of static content delivery, the system employs multiple AI agents that collaboratively analyze a learner’s objectives and generate a structured learning plan.

Two AI agents simulate a discussion to design a customized syllabus based on the user’s intended learning outcomes. After the syllabus is finalized, a separate AI agent takes on the role of an instructor and delivers lessons according to the generated structure.

This approach aims to create a more personalized, adaptive, and interactive learning experience.

Key Features

-Collaborative Agent-Based Syllabus Design
Two role-based AI agents engage in a guided discussion to analyze the user’s learning goals and create a well-structured syllabus.

-Adaptive Teaching Agent
A dedicated instructor agent adjusts its teaching strategy and pace to align with the learner’s needs and preferences.

-Interactive Learning Experience
The system enables continuous interaction between the learner and the instructor agent, supported by natural language understanding and reasoning capabilities.

System Architecture

The overall workflow of the system can be summarized as follows:

1. Agent Initialization
Multiple AI agents are initialized with predefined roles and domain knowledge.

2. Understanding User Input
When the user specifies a topic or learning objective, the system processes this input through carefully designed prompts.

3. Agent Collaboration and Dialogue
Two AI agents interact with each other, exchanging ideas and reasoning collaboratively to outline relevant concepts and organize them logically.

4. Syllabus Creation
Using the conversation history between the two agents, a Large Language Model generates a comprehensive and structured syllabus that aligns with the user’s goals.

5. Instructor Agent Activation
After the syllabus is finalized, an instructor agent takes responsibility for guiding the learner through the content, following the generated syllabus.

Through this multi-agent collaboration and adaptive instruction mechanism, the system delivers a dynamic and personalized educational experience.

Installation

Ensure that Python 3.10 or later is installed.
To set up the virtual environment, run:

make venv


Next, create a .env file in the root directory and add your OpenAI API key:

OPENAI_API_KEY=sk-xxxx

▶ Usage

To start the AI Instructor system, execute:

python src/run.py
