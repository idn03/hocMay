# Hands-On Chatbot Practice and NotebookLM Guides

This website helps learners use AI effectively at work and in their studies. Inspired by the [Next.js documentation](https://nextjs.org/docs), it offers sidebar navigation organized by learning path, a table of contents, and search. Each lesson focuses on a task learners can try right away.

## Hands-On Chatbot Practice

Learners practice skills they can use with ChatGPT and other conversational AI tools. They read a scenario, write a prompt, receive feedback on each grading criterion, and revise their submission. Meeting a lesson’s completion criteria unlocks the next lesson. For each exercise, the author prepares the scenario, a reference prompt, a grading rubric, and the conditions for passing.

**Example exercise**

You need to prepare a formal complaint about land use rights. Write a prompt that asks a chatbot to help you draft the complaint and identify the information you need to provide.

**Reference prompt**

> Before drafting the complaint, ask me what happened, which decision or action I want to challenge, and what outcome I am seeking. Based on my answers, list the documents I should gather and draft the complaint in Vietnamese. Mark any missing details so I can fill them in.

The grader evaluates the learner’s prompt. For this exercise, it checks whether the prompt states the goal, asks the chatbot to gather relevant facts, requests both a draft and a list of supporting information, and explains how to handle missing details. Different prompts can satisfy the same criteria.

## NotebookLM Guides

Learners follow illustrated guides to create a notebook, add source documents, ask questions, and check answers against cited passages. Each guide includes an objective, step-by-step instructions, screenshots, and an expected result. This section consists entirely of tutorials.

## Technology and Grading Workflow

| Component | Technology and purpose |
| --- | --- |
| Frontend | Next.js, shadcn/ui, and Tailwind CSS. TypeScript, Fumadocs, and MDX are proposed for the shared documentation layout and embedded practice forms. |
| Backend and deployment | Next.js Route Handlers run on Cloudflare Workers. API keys are stored in Worker Secrets. |
| Data | PostgreSQL stores exercises, rubric versions, submissions, results, and learner progress. Proposed tools include Drizzle ORM and Drizzle Kit, with Workers connecting to PostgreSQL through Hyperdrive. |
| Authentication | Better Auth is proposed for authentication using the same PostgreSQL database, starting with Google sign-in. |
| Grading | A model API billed by token grades submissions. AI SDK and Zod are proposed for receiving and validating structured results. |

When a learner submits a prompt, the server retrieves the reference prompt and full rubric for that exercise ID and version. It sends them to the model API along with the scenario and the learner’s prompt. For each criterion, the model returns a score, evidence from the submission, and a suggested improvement.

The server validates the result, calculates the total, and updates learner progress. Each submission has a unique ID so repeated clicks can be handled as a single grading request. The server records actual token usage to track grading costs.

## Initial Release

The first release covers a complete practice cycle in which a learner submits a prompt, receives feedback, revises the prompt, and unlocks the next lesson. It also includes one illustrated NotebookLM guide. Generating exercises tailored to a learner’s field is planned for a later release.
