# ai-exam-revision-agent
A prompt-based AI agent designed to help college students plan daily exam revision using a 4-layer prompt architecture.
# AI Exam Revision Agent

## Overview
This project documents my exploration of designing a simple AI agent using prompt engineering.
The agent helps college students plan daily exam revision by converting confusion and stress
into a clear, actionable study plan.

This is a prompt-based system built using ChatGPT, without production-level code.
The focus is on thinking, iteration, and real-world usability.

---

## Problem Statement
During exam preparation, students often feel overwhelmed and unsure about what to study first.
The problem is not lack of effort, but lack of clarity and prioritization.

This AI agent is designed to help students decide:
- What to revise today
- What topics matter most right now
- How to use limited study time effectively

---

## Target Users
- College students preparing for semester exams
- Students studying independently without coaching
- Learners facing anxiety or decision paralysis before exams

---

## Agent Architecture (4-Layer Design)

The agent is designed using a 4-step prompt architecture:

1. **Input Understanding**
   - Interprets what the student is asking
   - Extracts subject, urgency, and weak areas
   - Handles vague or emotional inputs

2. **State Tracker**
   - Simulates short-term memory
   - Remembers subject, exam date, and weak topics
   - Avoids repeated questions

3. **Task Planner**
   - Internally plans how to respond
   - Prioritizes topics based on urgency
   - Decides depth of revision for the day

4. **Output Generator**
   - Produces clear, structured responses
   - Uses simple language and bullet points
   - Ends with a short encouraging line

---

## Prompt Files
All prompts used in this project are stored in the `prompts/` folder.
Each file represents one responsibility of the agent.

---

## Exploration & Iteration
Prompt behavior was improved iteratively by:
- Testing vague and stressed inputs
- Refining instructions step-by-step
- Observing how small changes affected output quality

Exploration notes are available in the `logs/` folder.

---

## Key Learnings
- Good AI agents are built by separating responsibilities
- Prompt iteration is more important than prompt length
- Designing for real users improves output quality

---

## Disclaimer
This project is an academic exploration of prompt engineering.
No production system or automated backend is implemented.
