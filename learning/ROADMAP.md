## GOAL: AI Solution Specialist / Forward-Deployed Program Manager

### Direction set 2026-11-18 after market research:

- The enterprise bottleneck is deployment, not models: most companies run AI pilots, few reach production. The gap is integration, change management, and governance: exactly my PM skillset.
- German demand is shifting toward "AI system owners who bridge data, AI and compliance". My EU AI Act cert and ISO 42001 exposure are direct differentiators.
- Role family (same job, lower coding bar than FDE): AI Implementation Consultant, Deployment Strategist, AI Transformation Manager, Forward-Deployed PM, Solutions Engineer (AI).
- Germany benchmarks (Nov 2026, SalaryExpert): AI Solutions Architect avg EUR 133k (senior 148k), Solutions Consultant 93k (senior 105k), AI Consultant 87k (senior 108k).
- Work arrangement: employment now, consulting/freelance later.
- I build proofs, not products. The AI Engineer tool stack is for prototyping literacy and credibility with engineers, not a career as a developer.

### Three pillars to get there:

1. **Prototyping literacy**: hands-on core GenAI stack (Phases A-B).
2. **Delivery credibility**: PMI-CPMAI, after the DataCamp AI Engineer track (mid-2027, Phase C).
3. **Domain moat**: regulated industries + industrial engineering roots + German B1 (2027) + governance fluency.

### Current status

- Started Nov 2026
- Budget: 5-10 h/week
- Last updated: 2026-11-20

### Monthly self-review (calendar, 30 min):

- What did I build this month, and can I demo it in 5 minutes?
- Which experiment failed, and what did it teach me?
- Who did I talk to about the target role, and what did I learn about the German market?
- Is the next month's plan still calibrated to goal (or am I drifting into pure course-collecting)?

### Certifications & training baseline (Nov 2026)

| Certification                                           | Provider                | Date     |
| ------------------------------------------------------- | ----------------------- | -------- |
| Fundamentals of Data Governance, Privacy & GDPR         | DataCamp                | Nov 2026 |
| Data Analyst - Power BI                                 | Microsoft Certified     | Dec 2025 |
| Data Associate - SQL (PostgreSQL)                       | DataCamp                | Mar 2026 |
| AWS Cloud Practitioner                                  | AWS                     | Sep 2025 |
| Data Literacy Professional, AI Fundamentals & EU AI Act | DataCamp                | Aug 2025 |
| Emerging Leader & People Management                     | Leading Edge Leadership | Nov 2024 |
| Power Platform Fundamentals                             | Microsoft               | Jan 2024 |
| Professional Scrum Master (PSM-I)                       | Scrum.org               | Sep 2022 |
| Agile PRINCE2 Practitioner                              | Axelos                  | Jun 2019 |
| Green Belt Lean Six Sigma                               | ECAM Rennes             | Jan 2018 |

## Roadmap

### Phase A - AI engineering core stack (Dec 2026 - Feb 2027)

**Goal**: build working proofs with the core GenAI stack, end to end, twice.

- [x] Git & GitHub Foundations (exam pending)
- [ ] n8n Fundamentals (in progress)
- [ ] Python essentials (variables, functions, collections, error handling, files, API calls)
- [ ] AI Principles in Python
- [ ] Working with the OpenAI API
- [ ] LLM App with LangChain
- [ ] AI Applications with Pinecone (embeddings, chunking, RAG)
- [ ] Hugging Face
- [ ] LLMOps
- [ ] MCP (Model Context Protocol)

**Experiments log**

| #   | Goal                                                                                                                                       | What I did | What I learned | Link |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | -------------- | ---- |
| A1  | RAG policy assistant <br>feed a real document set (e.g. a bank procedure manual or the EU AI Act), answer 10 questions with sources cited. |            |                |      |
| A2  | n8n automation (e.g. inbox triage, report drafting, meeting-notes-to-Jira) with an LLM step inside.                                        |            |                |      |
|     |                                                                                                                                            |            |                |      |

### Phase B - Agents, data pipelines, cloud (Mar - May 2027)

**Goal**: agents that do multi-step work, plus the data-pipeline and cloud context to judge feasibility and cost.

- [x] AI Agent Fundamentals (theory: GenAI concepts, frameworks, design patterns) - done on DataCamp
- [ ] Hands-on agent building: wire real function calling / tools, multi-step loop, human-in-the-loop gate (this is the "doing" half the theory course does not cover; lands in Experiment B1)
- [ ] ML literacy at judgment level (~2-3h, within AI Principles in Python): supervised vs unsupervised, when classic ML vs GenAI, baselines and metrics
- [ ] Evaluation basics: eval sets, hallucination/regression checks (the 2026 non-negotiable)
- [ ] Data pipeline thinking: ingestion, cleaning, scheduling (DataOps; ties into CPMAI later)
- [ ] Cloud level-set: AWS AI building blocks (Bedrock, S3, Lambda awareness) - optional cert: AWS AI Practitioner
- [ ] Governance in practice: map EU AI Act duties and ISO 42001-style controls onto a concrete use case

**Experiments log**

| #   | Goal                                                         | What I did | What I learned | Link |
| --- | ------------------------------------------------------------ | ---------- | -------------- | ---- |
| B1  | Agentic use case + eval (scope -> build -> eval -> write-up) |            |                |      |
| B2  | promote A1 artifact to a scheduled, production-like run      |            |                |      |
|     |                                                              |            |                |      |
### Phase C - Delivery credibility & positioning (Jun - Jul 2027)

**Goal**: add the management credential, and go to market.

- [ ] PMI-CPMAI: 30h prep course + 120-question exam (target exam: Jul 2027)
- [ ] 3 case-study write-ups from Experiments A1-B2, each as: problem -> solution -> value -> what I'd do differently
- [ ] 5 conversations with people in the target role (mentoring coffees, German market focus)

### Phase D - Solution specialist practice (from Aug 2027, ongoing)

- Thought leadership: LinkedIn short posts on AI delivery in regulated industries (deploy, don't demo).

Client discovery-to-value-case questions (rehearse monthly):

1. Which process consumes the most expert hours for the least value today?
2. What decision in that process needs which information, from which systems?
3. What happens today when it goes wrong: cost, delay, compliance exposure?
4. Who owns the data, and what would need to be true before an AI touches it?
5. What does "good enough" look like: what would make us stop and not ship?

Use-case qualification (before building anything):

6. Is there a way to measure success before we build?
7. Can it ship with a human-in-the-loop first?
8. What is the smallest proof that would change the sponsor's mind?

Keep the use-case library current; retire stale ideas, add learned ones:

| #   | Domain                    | Problem                             | AI pattern                                                   | Stack sketch                             | Value metric                               |
| --- | ------------------------- | ----------------------------------- | ------------------------------------------------------------ | ---------------------------------------- | ------------------------------------------ |
| 1   | Banking                   | Slow KYC/AML document review        | RAG copilot over client files, human-in-the-loop             | LangChain + Pinecone + n8n               | Review hours per case, error rate          |
| 2   | Banking                   | Front-office agents stuck in POC    | Agentic workflow for client request triage (I piloted this)  | Agents + function calling + eval harness | % requests auto-resolved, time-to-response |
| 3   | Banking/Regulated         | Regulatory change monitoring        | Agent that monitors feeds, maps changes to internal policies | n8n + LLM + structured outputs           | Analyst hours saved, update lead time      |
| 4   | Any                       | Client onboarding paperwork         | LLM classification + extraction pipeline                     | n8n + LLM APIs                           | Onboarding cycle time                      |
| 5   | Mittelstand/manufacturing | Supplier invoice & order processing | Document AI extraction into ERP                              | Power Automate or n8n + LLM              | Cost per invoice, error rate               |
| 6   | Manufacturing             | Unplanned downtime                  | Predictive maintenance scoping                               | Python + cloud ML basics                 | Downtime hours, scrap rate                 |
| 7   | Consulting offer          | AI governance readiness             | ISO 42001 / EU AI Act gap assessment as a billable service   | My certs + CPMAI                         | New revenue line, day rate                 |
## Tools stack

| Layer              | Tool                                         | Phase    |
| ------------------ | -------------------------------------------- | -------- |
| Code & repos       | Python, Git/GitHub, gh CLI, VS Code          | A        |
| LLM APIs           | OpenAI API, Mistral API                      | A        |
| Orchestration      | LangChain                                    | A-B      |
| Open-source models | Hugging Face                                 | A-B      |
| Vector / RAG       | Pinecone (pgvector awareness)                | A-B      |
| Automation         | n8n, Power Automate (lean on existing cert)  | A        |
| Cloud              | AWS (certified CP); optional AI Practitioner | B        |
| BI / data          | SQL (PostgreSQL), Power BI (certified)       | achieved |
| PM / delivery      | JIRA, CPMAI methodology                      | C        |
| Governance         | EU AI Act, PMI-CPMAI                         | B-C      |
## Reflections

- 2026-11-18: Roadmap created. First focus: SQL basics.
- 2026-11-18: Refined after direction-setting with Vibe. North star adopted: AI Solution Specialist / Forward-Deployed PM. Stack-centered phases A-D added with tools, exercises and use-case library. CPMAI scheduled after DataCamp AI Engineer track (mid-2027).
- 2026-11-20: Clean-up, simplification and corrections by Simon: "AI Engineer for Developers" track breakdown. progress update + Python strategy set.
