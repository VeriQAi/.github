# VeriQAI — Free, Open-Source AI Tools for Educators

VeriQAI provides free, open-source tools for educators. Our mission: eliminate the friction points that prevent educators from realising the full potential of AI-assisted teaching and assessment tools. Every tool runs entirely in your browser — no accounts, no subscriptions, no data leaving your machine.

## 🚀 Our Tools

| Tool | What it solves | Live App |
|---|---|---|
| **GradeBridge** | Eliminates the trade-off between student convenience and Gradescope AI-grading efficiency | [Assignment Maker](https://veriqai.github.io/GradeBridge-Assignment-Maker/) · [Student Submission](https://veriqai.github.io/GradeBridge-Student-Submission/) |
| **MATLAB Grader Problem Generator** | Turns 1–2 hours of MATLAB Grader problem authoring into minutes | [Open App](https://veriqai.github.io/MatlabGraderProblemGenerator/) |

---

## ✅ GradeBridge — Solve the Gradescope Efficiency Gap

**GradeBridge eliminates the costly trade-off between student convenience and grading efficiency in Gradescope.** ([constraints that create this problem](https://github.com/VeriQAi/.github/blob/main/WORKFLOW_MOTIVATION.md))

<div align="center">
<img src="https://raw.githubusercontent.com/VeriQAi/.github/main/gradebridge-workflow.png" alt="GradeBridge Suite Workflow" width="500">
</div>

### 🎯 The Gradescope Problem

**Gradescope's AI-assisted grading saves 40-60% of grading time** — but only works with templated PDFs. This forces educators into a costly trade-off:

- ✅ **Use templates** → Get AI efficiency BUT students struggle with rigid formatting (8+ hours instructor setup)
- ✅ **Skip templates** → Easy submissions BUT lose all AI time savings

**The hidden cost:** Thousands of hours lost every semester to this forced choice.

### The Solution: Get Both Benefits

**GradeBridge eliminates the trade-off** — delivering flexible student submissions that generate perfect Gradescope templates automatically.

#### [Assignment Maker](https://veriqai.github.io/GradeBridge-Assignment-Maker/)
**For Educators** • Create Gradescope-optimized assignments in 15 minutes (not 8 hours)
- Professional LaTeX rendering built-in
- **Exports JSON that students load in Student Submission app**
- **Auto-generates perfect Gradescope PDF templates**
- Zero manual template creation required

#### [Student Submission](https://veriqai.github.io/GradeBridge-Student-Submission/)
**For Students** • Load assignments from Assignment Maker and generate Gradescope-ready PDFs
- **Imports JSON files created by instructors using Assignment Maker**
- Guided interface prevents formatting errors
- **AI usage tracking built-in for academic integrity**
- **PDFs match instructor Gradescope templates perfectly**

### 🔥 The Impact

**Time Savings:**
- **Assignment creation:** 8 hours → 15 minutes (3,100% improvement)
- **Grading efficiency:** Full 40-60% Gradescope AI savings preserved
- **Student submission success:** Near 100% (vs. frequent format failures)

**Quality Improvements:**
- Zero time spent on formatting troubleshooting
- Consistent, professional submissions every time
- Academic integrity through AI usage documentation
- Maximum Gradescope AI efficiency realized

### Quick Start

**Educators:**
1. Visit [Assignment Maker](https://veriqai.github.io/GradeBridge-Assignment-Maker/)
2. Create assignment with LaTeX support (15 minutes vs 8 hours)
3. Export JSON for students + PDF template for Gradescope
4. Upload PDF to Gradescope — all regions auto-configured

**Students:**
1. Get assignment JSON from instructor
2. Visit [Student Submission](https://veriqai.github.io/GradeBridge-Student-Submission/)
3. Load assignment → Complete work → Download Gradescope-ready PDF
4. Submit with confidence — format guaranteed to work

---

## 🛠️ MATLAB Grader Problem Generator

### [Open App →](https://veriqai.github.io/MatlabGraderProblemGenerator/)

**For MATLAB Educators** • Generate complete, assessment-ready MATLAB Grader problems in minutes — not hours.

### 🎯 The Problem

Creating a single MATLAB Grader problem from scratch means writing four distinct artifacts — each with MATLAB Grader's exacting syntax requirements:

| Artifact | What it involves |
|---|---|
| Problem description | Clear, numbered student-facing instructions |
| Reference solution | Complete, commented `.m` solution |
| Learner template | Scaffolded `.m` file with stubs for students |
| Test cases | Assessment code using MATLAB Grader's `assessVariableEqual`, `assessPattern` API |

The test cases alone — with their guard conditions, diagnostics, and R2025b syntax rules — can take an experienced instructor an hour or more per problem. Multiply that across a full problem set and the authoring burden is significant.

### The Solution

Enter a learning objective. Claude proposes calibrated problem options across difficulty levels (Easy / Medium / Hard) for Script or Function problem types. Select the ones you want — all 4 artifacts are generated automatically, one by one, with live review at each step. Download as a named ZIP ready to paste directly into MATLAB Grader.

### 🔥 The Impact

- **Problem authoring:** 1–2 hours per problem → minutes
- **Test case quality:** R2025b-compliant syntax, guard conditions, and verbose diagnostics out of the box
- **Cost:** Generating and fully developing 4 problems costs approximately **$0.05–$0.10** with Claude Sonnet 4.6

### Key Facts

- Bring your own Anthropic API key (get one at [console.anthropic.com](https://console.anthropic.com))
- Model selector: Claude Haiku (fast) · Sonnet (recommended) · Opus (most capable)
- Supports both Script and Function problem types
- No signup · MIT License · Runs entirely in your browser

---

## 🔧 Technical Excellence (All Tools)

**Privacy & Accessibility:**
- 100% client-side processing — your data never leaves your browser
- No accounts or subscriptions required
- Works on any device with a modern browser
- MIT License — free for all educational use

**Built for real courses:**
- GradeBridge tested with courses of 500+ students
- MATLAB Grader Problem Generator generates R2025b-compliant assessment code

---

## 📖 Learn More

- 📖 **[Why Gradescope forces the trade-off & how GradeBridge solves it](https://github.com/VeriQAi/.github/blob/main/WORKFLOW_MOTIVATION.md)**
- 🐛 [Report issues or request features](https://github.com/orgs/VeriQAi/repositories)
- ⭐ Star our repos if they save you time

---

## About VeriQAI

We're educators and technologists who got tired of the artificial trade-offs imposed by educational technology platforms. **GradeBridge** is our flagship solution — proving that you don't have to choose between student experience and instructor efficiency. The **MATLAB Grader Problem Generator** is our latest utility — eliminating the authoring burden that keeps high-quality MATLAB assessments out of reach.

*More educational workflow solutions in development • Follow us to stay updated*

---

**Built by educators, for educators.**
