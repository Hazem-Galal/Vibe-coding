
📘 Vibe Coding Project – README

A project built using Vibe Coding principles — leveraging AI tools and interactive workflows to design, prototype, and ship software with speed and creativity.

🧠 What Is Vibe Coding?

Vibe Coding is a modern development approach where AI tools become collaborative partners in building software. Rather than manually writing each line of code, you shape ideas, guide large language models (LLMs), and craft prompts that direct AI to deliver reliable, working code — rapidly transforming concepts into real applications.

🎯 Project Purpose

This repository houses a software project built through AI-assisted coding workflows with the goals of:

Practicing prompt-guided development

Rapid prototyping real user experiences

Demonstrating mastery of modern AI tools for development

Creating a job-ready portfolio piece

It is designed to reflect what you’d build while progressing through the Vibe Coding Bootcamp.

🚀 Core Principles

This project follows the Vibe Coding philosophy:

Human + AI collaboration — AI writes and refactors code you direct

Prompt engineering first — prompts become the instructions that translate product intent into code

Incremental project builds — each feature ships quickly and evolves over time

Real-world tooling — use tools like Cursor, GitHub Copilot, Claude, Gemini, and ChatGPT effectively as copilots

🛠 Tech & Tooling Overview

Tools referenced in this project’s workflows reflect those emphasized in the bootcamp.

Key AI Tools

GitHub Copilot — AI code completion inside your editor

Cursor / Zed — next-generation AI-assisted IDE workflows

ChatGPT / Claude / Gemini — LLMs for coding, reasoning, and logic execution

Development Stack

Frontend: HTML5, CSS3, JavaScript (ES6+)

Optional Backend: Node.js / Express or serverless API

Deployment: Netlify, Vercel, or similar

Prompt Scripts: Reusable prompt templates in /prompts/

📁 Repository Structure

```
.
├── README.md                      # This file
├── package.json                   # Node.js dependencies & scripts
├── package-lock.json              # Dependency lock file
├── index.js                       # Main Node.js entry point
├── splash.html                    # Interactive splash page with CTA
├── 1.ipynb                        # Jupyter notebook (optional experiments)
├── .env                           # Environment variables
├── prompts/                       # Stored prompt templates and snippets
├── assets/                        # Images, icons, fonts
├── .vibe/                         # AI-centric config and workflow files
└── docs/                          # Supporting docs & reference guides
```

⚡ Running the Project

**Splash Page (Quick Start)**

Open `splash.html` directly in your browser or use VS Code Live Preview for an interactive welcome screen.

**Node.js Backend**

```bash
npm install
npm start
```

This runs the main `index.js` script. Outputs confirmation and timestamp.

**Local Server (for testing HTML files)**

```bash
python -m http.server 8000
```

Then open: `http://localhost:8000`

Navigate to:
- `http://localhost:8000/splash.html` — Interactive splash with CTA
- Or any other HTML files in the project root

🧩 Prompt Engineering

Effective prompts are the cornerstone of Vibe Coding.

Include reusable prompt templates like:

# GPT-Prompt: Create feature skeleton
Given the project context stored in /prompts/context.txt,
generate [feature] using [tool] with best practices.

Include:
• Dependency list
• Example outputs
• Explanation comments


Save these under /prompts/ to standardize workflow and collaboration.

📌 Example Feature Build Workflow

Define intent: e.g., “Build a landing page with user signup”

Craft prompt: Write a prompt specifying task, constraints, and style

AI generates code: Use Copilot, ChatGPT, or Cursor to produce initial code

Iterate: Refine via follow-up prompts until user experience is solid

Test & polish: Validate functionality, responsiveness, accessibility

This mirrors the training emphasis in the bootcamp.

📈 Portfolio Goals

By completing this project you will:

Translate idea → working web app using AI workflows

Write professional prompts that guide reliable code generation

Understand version control with Git + AI tools (e.g., commit message suggestions)

Produce deployable apps that showcase your ability to use AI to ship software

📄 License

Licensed under MIT License. Feel free to fork, remix, and evolve.


