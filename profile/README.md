# VeriQAi: Free, Open-Source AI Tools for Educators

VeriQAi publishes free, open-source, privacy-first AI tools for educators. Every tool runs entirely in your browser: no accounts, no subscriptions, no student data sent to our servers. The current toolset:

| Tool | What it does | Live App |
|---|---|---|
| **GradeBridge — Lab Pipeline** | Structured engineering assignments (lab reports, mini-projects, homework) with text, image, and AI-graded responses, autograded in Gradescope. | [Assignment Maker](https://veriqai.github.io/GradeBridge-Assignment-Maker/) · [Student Submission](https://veriqai.github.io/GradeBridge-Student-Submission/) |
| **GradeBridge — MQ Pipeline** *(new, May 2026)* | Timed multiple-choice quizzes drawn from a portable SQLite question bank. One-question-at-a-time UX, honor pledge, accommodation variants for SDC students, autograded in Gradescope. | [MQ Assignment Maker](https://veriqai.github.io/GradeBridge-MQ-Assignment-Maker/) · [MQ Student Submission](https://veriqai.github.io/GradeBridge-MQ-Student-Submission/) |
| **MATLAB Grader Problem Generator** | Generates complete MATLAB Grader problems from a single learning objective in minutes. | [Open App](https://veriqai.github.io/MatlabGraderProblemGenerator/) |

---

## GradeBridge

GradeBridge turns your existing course materials into autograded Gradescope assignments. Two complementary pipelines share the same encryption, the same Gradescope-Docker autograder pattern, and the same browser-first design:

**Lab Pipeline** — for lab reports, mini-projects, and homework. Drop a lab manual through the Claude Code prompt to generate a structured assignment file. Open it in the Assignment Maker, fine-tune, export. Students complete the work in the Student Submission App and submit a single ZIP to Gradescope. AI-graded questions are scored automatically; image and text questions go to TAs with a confidential grader document.

**MQ Pipeline** — for timed multiple-choice reading checks and quizzes. Maintain a portable SQLite question bank organized by module, chapter, and topic. The MQ Assignment Maker filters and selects a pool, exports an encrypted timed assignment, and offers one-click accommodation variants (1.25x, 1.5x, 2x) for SDC students. The MQ Student Submission app delivers a timed quiz with one question at a time, an Honor Code pledge requirement, and an encrypted submission ZIP for Gradescope.

Both pipelines:

- **Run entirely in the browser** — no installation, no account, no server.
- **Encrypt with AES-256-GCM** — assignment specs and student submissions are encoded before they leave your machine; tampering is detected.
- **Use Gradescope-Docker autograders** — Python autograders run inside Gradescope's standard Docker environment.
- **Are open-source** — every line of code is on this org page.

📖 **Documentation and worked examples:** [GradeBridge-AI](https://github.com/VeriQAi/GradeBridge-AI) (the parent/landing repo with diagrams, an end-to-end example, and pipeline specs).

---

## MATLAB Grader Problem Generator

A focused tool that takes a single learning objective and produces a complete MATLAB Grader problem in minutes — including reference solution, solution template, assessment tests, and exercise text. [Repo](https://github.com/VeriQAi/MatlabGraderProblemGenerator).

---

## Privacy and Open Source

VeriQAi tools are **privacy-first by design**. Student data, instructor question banks, and assignment content are processed entirely client-side. Nothing is sent to a VeriQAi server (we do not run any). Encrypted artifacts go directly from the student's browser to Gradescope; correct answers stay sealed in the autograder Docker image you control.

All code is MIT-licensed. Forking, adapting, and self-hosting are encouraged.

---

## Maintained by

[Andre Knoesen](https://github.com/aknoesen) — UC Davis, Department of Electrical and Computer Engineering.

Contact: [andre@aknoesen.com](mailto:andre@aknoesen.com)

