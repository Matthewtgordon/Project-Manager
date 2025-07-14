# AGENTS.md for Codex Integration and Promptable DSL Automation
## Project Configuration
* **Project Name:** Promptable DSL Automation
* **Project Description:** Automate Promptable DSL development using Codex for code generation and Grok for research and testing.
* **Project Rules:**
 + Generate Promptable DSL prompts combining natural language, JSON metadata, and Python code.
 + Output formats: Markdown (.md) for prompts, JSON (.json) for configs, Python (.py) for scripts.
## Promptable DSL Specifications
* **DSL Objective:** Simplify complex tasks using natural language prompts with executable code.
* **DSL Components:**
 + **NTL Prompt:** Natural language description of task or action.
 + **JSON Metadata:** Structured data describing prompt context, parameters, and constraints.
 + **Python Code:** Executable code generated from NTL prompt and JSON metadata.
## Codex Configuration
* **Model:** code-davinci-002
* **Temperature:** 0.7
* **Top P:** 1
* **Frequency Penalty:** 0.5
* **Presence Penalty:** 0.5
## Grok Research Objectives
* **Research Topics:**
 + Promptable DSL development best practices
 + Codex configuration optimization
 + Grok testing and validation strategies
* **Delivery Format:** 10K character chunks in PDF
## Security Constraints
* **Sandboxing:** Execute Codex and Grok in network-disabled, ephemeral cloud sandboxes.
* **Data Retention:** Disable response storage for both Codex and Grok.
* **API Access:** Restrict to least-privilege scope for prompt creation and research data access.
## GitHub Actions Workflows
* **Sync Workflow:** Sync Promptable DSL files across repositories.
* **Test Workflow:** Test Promptable DSL files using Grok and Codex.
* **Deploy Workflow:** Deploy prompts to ChatGPT and Gemini Coder.
