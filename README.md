<p align="center">
  <img src="assets/profile-hero.svg" alt="Ajanee Igharo — Applied AI Engineer. Agents, evaluation, and human oversight." width="100%" />
</p>

<p align="center">
  <strong>Applied AI Engineer building systems for real organizational workflows.</strong><br />
  I build tool-using agents, evaluate their behavior, and make their boundaries explicit.
</p>

<p align="center">
  <a href="https://ajaneeigharo.com/"><strong>Portfolio</strong></a> ·
  <a href="#selected-systems">Selected systems</a> ·
  <a href="https://www.linkedin.com/in/ajaneeigharo/">LinkedIn</a>
</p>

## Selected systems

### [Agentic Analytics Lab](https://github.com/AjaneeI/agentic-analytics-lab)
**Flagship · Python · SQL · ClickHouse · agent evaluation**

**When does routing earn its complexity?** An analytics-agent lab comparing a single-agent baseline with routed execution over synthetic operational data. I built read-only, dataset-scoped tools, semantic metric guards, deterministic evaluation, and route telemetry.

**Evidence:** reproducible experiments, regression tests, and CI/CodeQL workflows. The reviewed oracle-metadata comparison supplies the route; it does **not** establish natural-language routing quality or production performance.

[Architecture](https://github.com/AjaneeI/agentic-analytics-lab/blob/main/ARCHITECTURE.md) · [Evaluation and limitations](https://github.com/AjaneeI/agentic-analytics-lab#evaluation-method) · [CI](https://github.com/AjaneeI/agentic-analytics-lab/actions)

### [HomeOps Agent](https://github.com/AjaneeI/homeops-agent)
**Prototype · Python · Strands · human-in-the-loop controls**

**Where should automation stop and ask a person?** A Good Night Check workflow with explicit tool contracts, allowlisted low-risk actions, human approval requests, and an inspectable audit trail. Uncertain lock states and device failures do not become permission to act.

**Evidence:** deterministic policy tests and Chromium scenario-parity checks. The public demo uses **simulated devices**, not a production smart-home deployment.

[Safety model](https://github.com/AjaneeI/homeops-agent#safety-model) · [Run the demo](https://github.com/AjaneeI/homeops-agent#demo) · [CI](https://github.com/AjaneeI/homeops-agent/actions)

### [Agent Systems Evidence Scout](https://github.com/AjaneeI/agent-systems-evidence-scout)
**Working prototype · Python · smolagents · Hugging Face · Gradio**

**Can a research agent enforce its own evidence boundary?** The model chooses research tools; deterministic Python checks arXiv citations against a per-run verification registry and withholds drafts that fail the evidence contract.

**Evidence:** offline regression tests, a documented live integration run, and a browser-tested interface. Citation verification checks paper identity and sourcing—not whether every research conclusion is true.

[Demo](https://github.com/AjaneeI/agent-systems-evidence-scout#live-demo) · [Failure analysis](https://github.com/AjaneeI/agent-systems-evidence-scout#what-the-live-test-caught) · [CI](https://github.com/AjaneeI/agent-systems-evidence-scout/actions)

## How I engineer

**Measure before adding complexity.** Start with a credible baseline and define success before adding orchestration.

**Put boundaries in code.** Tool permissions, structured contracts, approval gates, and failure handling should be testable outside the model.

**Make failures inspectable.** Record what happened, preserve evidence, and distinguish a convincing demo from a measured result.

**Core tools:** Python · SQL · TypeScript · ClickHouse · GitHub Actions · pytest · Playwright

## About

Alongside my engineering work, I am an **Applied AI Programs & Operations Coordinator** at the **Paul English Applied AI Institute, UMass Boston**, and an **MBA candidate**.

Psychology shaped how I think about behavior, trust, and decisions. Operations taught me to examine the workflow around the technology. Applied AI brings those perspectives into building, testing, and evaluating systems people can use.

Based in **Greater Boston**. Interested in applied AI engineering and AI solutions work involving agents, evaluation, and organizational workflows.

<details>
<summary><strong>More engineering and product work</strong></summary>

**[Midnight Reminder](https://github.com/AjaneeI/midnight-reminder-pi-extension)** · Implemented TypeScript extension with injected clock/storage interfaces, explicit time boundaries, cross-session duplicate prevention, and regression tests.

**[Closing the Loop](https://github.com/AjaneeI/closing-the-loop-patient-portals)** · Earlier product and analytics case study: workflow friction, KPI design, and responsible-AI boundaries. A concept and measurement strategy, not deployed software.

**[Hermes Meeting → Action](https://github.com/AjaneeI/hermes-meeting-action)** · In progress. Structured action schema and evaluation fixtures are defined; the extraction runner and durable integrations remain implementation gates.

</details>

<details>
<summary><strong>Selected publications and presentations</strong></summary>

- [AI-Powered Personal Branding: A Coaching Toolkit for Career Advisors](https://scholarworks.umb.edu/ai_pubs/47/) · UMass Boston ScholarWorks, 2026
- [Spring AI 2026 Workshop and Speaker Series Report](https://scholarworks.umb.edu/ai_pubs/43/) · Co-author, UMass Boston ScholarWorks, 2026
- [AI As An Equalizer: Empowering Underrepresented Students for High-Demand Careers](https://scholarworks.umb.edu/ai_pubs/16/) · UMass Boston ScholarWorks, 2025

</details>

---

<p align="center">
  <strong>Evidence before claims. Systems before hype.</strong><br />
  <a href="https://ajaneeigharo.com/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/ajaneeigharo/">LinkedIn</a> ·
  <a href="https://x.com/AjaneeIgharo">X</a>
</p>
