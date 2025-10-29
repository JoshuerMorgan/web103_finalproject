# Milestone 1

This document should be completed and submitted during **Unit 5** of this course. You **must** check off all completed tasks in this document in order to receive credit for your work.

## Checklist

This unit, be sure to complete all tasks listed below. To complete a task, place an `x` between the brackets.

- [X] Read and understand all required features
  - [X] Understand you **must** implement **all** baseline features and **two** custom features
- [X] In `readme.md`: update app name to your app's name
- [X] In `readme.md`: add all group members' names
- [X] In `readme.md`: complete the **Description and Purpose** section
- [X] In `readme.md`: complete the **Inspiration** section
- [X] In `readme.md`: list a name and description for all features (minimum 6 for full points) you intend to include in your app (in future units, you will check off features as you complete them and add GIFs demonstrating the features)
- [X] In `planning/user_stories.md`: add all user stories (minimum 10 for full points)
- [X] In `planning/user_stories.md`: use 1-3 unique user roles in your user stories
- [X] In this document, complete all thre questions in the **Reflection** section below

## Reflection

### 1. What went well during this unit?

We aligned quickly on scope and value: “ingredients ➜ meal” solves a real problem for busy students. We finalized a clean feature list (6+ items) and tagged two custom features (Veganize + Shopping List). The team agreed on tech choices (React + Express + Postgres), sketched the schema, and set up the repo, environment files, and a simple request/response flow. Collaboration also went smoothly—we split tasks with a short stand-up and used a living README to keep decisions visible.

### 2. What were some challenges your group faced in this unit?

Scoping AI behavior was tricky (prompt design, consistent structure in outputs). We debated how much to store (full recipe vs. prompt + seed) and how to represent pantry/allergens in the schema. We also called out likely friction points: API rate limits/costs, CORS and environment config across client/server, and keeping UX simple while adding power features like timers and nutrition.

### 3. What additional support will you need in upcoming units as you continue to work on your final project?

Guidance on robust prompt patterns (guardrails, structure enforcement), best-practice examples for streaming AI responses, and suggestions for affordable nutrition lookups. We’d also benefit from examples of secure key management on Render, basic observability (logs/metrics), and a rubric for user-testing so we can validate usability before final polish.
