📚 Agentic AI Study Assistant

Agentic AI Study Assistant is a multi-agent intelligent educational system designed to help students plan, track, and optimize their learning through autonomous study planning, adaptive revision scheduling, quiz-based knowledge gap detection, and performance analytics.

The system leverages Agentic AI, Large Language Models (LLMs), and cognitive learning principles to create a personalized learning assistant that continuously adapts to a student's academic progress.

🚀 Project Vision

The Agentic AI Study Assistant is an intelligent learning system designed to help students study more efficiently through autonomous planning and adaptive learning strategies.

Unlike traditional study planner apps or reactive chatbots, this system actively monitors performance, identifies weaknesses, and dynamically adjusts study plans.

The assistant behaves like an AI academic coach that continuously improves the student's learning strategy.

🎯 Problem Statement

Students often struggle with:

Poor time management

Inefficient revision timing

Lack of structured study planning

Difficulty identifying weak topics

Study anxiety due to unorganized preparation

Existing tools provide static reminders or reactive answers, but they do not autonomously guide learning.

This project introduces a goal-driven AI system that continuously analyzes learning progress and optimizes study plans.

🧠 Core Concept: Agentic AI

Agentic AI systems are capable of autonomous decision-making.

Instead of simply responding to queries, the system:

1️⃣ Understands the student's goal
2️⃣ Plans a learning schedule
3️⃣ Evaluates performance
4️⃣ Detects weak topics
5️⃣ Adjusts the learning strategy automatically

This transforms the system from a tool into an autonomous learning assistant.

✨ Key Features
📅 Autonomous Study Planning

Generates optimized study schedules based on:

available study hours

subject difficulty

exam deadlines

topic priority

🧪 AI-Generated Quizzes

Automatically generates quizzes to evaluate understanding.

Features include:

topic-specific questions

dynamic difficulty

instant evaluation

🔍 Knowledge Gap Detection

The system analyzes quiz results to detect weak areas.

Outputs include:

topic mastery score

weak concept identification

targeted revision recommendations

🔁 Adaptive Revision Scheduling

The system optimizes revision timing using:

Spaced Repetition

Ebbinghaus Forgetting Curve

This ensures students revise topics before forgetting occurs.

📊 Performance Analytics Dashboard

Students receive visual insights into their learning:

study progress tracking

mastery levels

retention patterns

productivity analysis

🗣 Accessibility Support

To ensure inclusive education:

Speech-to-Text input

Text-to-Speech output

Voice interaction support

This allows visually impaired students to use the platform.

🏗 System Architecture
Student Interface
        │
        ▼
Frontend Application
(React / Web Dashboard)
        │
        ▼
Backend API Layer
(FastAPI + PostgreSQL)
        │
        ▼
Agentic AI System
│
├ Planner Agent
├ Quiz Agent
├ Evaluation Agent
├ Revision Agent
└ Scheduler Agent
        │
        ▼
AI Engine
│
├ Large Language Model
├ Retrieval Augmented Generation
└ Vector Database
        │
        ▼
Learning Science Engine
│
├ Spaced Repetition
├ Knowledge Gap Detection
└ Performance Analytics
🤖 Multi-Agent System

The intelligence of the system comes from specialized AI agents.

Agent	Responsibility
Planner Agent	Generates personalized study schedules
Quiz Agent	Creates quizzes to evaluate learning
Evaluation Agent	Analyzes results and detects weak areas
Revision Agent	Updates revision schedules
Scheduler Agent	Coordinates agent workflows

Each agent performs a specific role, enabling autonomous decision-making.

⚙ Technology Stack
Frontend

React

Tailwind CSS

Chart.js

Backend

Python

FastAPI

PostgreSQL

Redis

AI / Machine Learning

LLM APIs

LangChain

Vector Databases (FAISS / Pinecone)

Accessibility

Speech-to-Text APIs

Text-to-Speech APIs

📂 Repository Structure
agentic-ai-study-assistant
│
├ frontend
│  ├ components
│  ├ pages
│  └ dashboard
│
├ backend
│  ├ api
│  ├ database
│  └ services
│
├ agents
│  ├ planner_agent
│  ├ quiz_agent
│  ├ evaluation_agent
│  └ revision_agent
│
├ ai_engine
│  ├ rag_pipeline
│  ├ embeddings
│  └ models
│
├ docs
│  ├ architecture
│  └ diagrams
│
└ README.md

🔄 System Workflow
Student Inputs Study Time
        │
        ▼
Planner Agent
Generate Study Plan
        │
        ▼
Quiz Agent
Generate Quiz
        │
        ▼
Evaluation Agent
Analyze Performance
        │
        ▼
Revision Agent
Update Study Schedule
        │
        ▼
Analytics Dashboard
Display Progress
🧪 Example Scenario

1️⃣ Student enters subjects and available study time
2️⃣ AI generates a personalized schedule
3️⃣ Student studies topics and attempts quizzes
4️⃣ System identifies weak concepts
5️⃣ Revision plan automatically updates
6️⃣ Dashboard shows learning insights

📊 Expected Impact

The system aims to achieve:

30-40% improvement in study efficiency

better revision timing

improved knowledge retention

reduced academic stress

accessible learning support

📅 Development Roadmap
Phase	Task
Phase 1	Research & architecture design
Phase 2	Backend system development
Phase 3	Multi-agent AI implementation
Phase 4	Frontend dashboard
Phase 5	Testing & evaluation
👥 Team

Developed by students from

Nitte Meenakshi Institute of Technology

Team Members

Mohammed Athar

Mohammed Ibrahim

Mohammed Saqhibuddin Khan

Tarun Gowda

Project Guide

Dr. Manoj Kumar M V

🔬 Research Foundations

This project is based on research in:

Agentic AI workflows

Adaptive learning systems

Cognitive memory models

Multi-agent AI architectures

🤝 Contributing

This project is currently under development.

Future contributions may include:

new learning algorithms

improved agent strategies

UI improvements

additional accessibility features

🌍 Future Enhancements

AI exam prediction

Peer learning recommendations

Mobile application

LMS integration

Automated syllabus parsing

⭐ Support

If you find this project interesting, consider starring the repository.

It helps the project gain visibility and encourages further development.
