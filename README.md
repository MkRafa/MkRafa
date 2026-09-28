# Hi, I'm Mann 👋

**Senior AI Product Manager.** I ship AI-powered enterprise products across healthcare, contact centres and customer experience, taking agentic AI from customer pain point to production.

My product bar for AI: **outputs that can be checked, not just trusted.** Every claim cited, every decision traceable, and a human in the loop when the evidence isn't there.

- 🏥 **Now:** Senior Product Manager at **RagaAI**, an agentic AI platform for healthcare automation. I own the product lifecycle across clinical operations and trial workflows and lead a squad of 30+ across engineering, AI science, QA and customer success.
- 💼 **Before:** 3 years at **Sprinklr** (NYSE: CXM), growing from Product Analyst to Product Manager – Lead, with a team of 13 and a portfolio of 45 enterprise clients including Microsoft and Aramex.
- 🎓 International MBA, **IE Business School** (Madrid) · B.Tech, **IIT Hyderabad**
- 📍 Bengaluru, India · 🗣️ English, Hindi, Marathi
- 🌐 **Portfolio:** [mkrafa.github.io](https://mkrafa.github.io)

---

## 📈 Product impact

**Healthcare AI · RagaAI**
- **$4M saved per clinical trial** with a hybrid pipeline: RPA where no API existed, LLMs for eligibility pre-screening, OCR for unstructured documents
- **Insurance verification cut from 3 days to 4 hours** by chaining OCR → LLM reasoning over payer policy documents
- **Appointment scheduling time cut 40%** with real-time voice and chat agents, at 95%+ data-entry accuracy

**Contact centre & CX AI · Sprinklr**
- **Shipped 14 AI enhancements** (agent assist, smart replies, sentiment-aware routing), driving **25% feature adoption and 96% retention**
- **+23% CSAT and 35% of calls deflected** with Voice AI and IVR automation
- **$800K upsell** closed on-site in Dubai, plus a 30% consumption increase
- **Onboarding time cut 30%** with vertical playbooks; **9,000 new users activated** through an in-app onboarding programme
- **SLA resolution cut by 4.5 hrs (CCaaS) and 3 hrs (Social)** with recommendation engines and auto-response workflows

---

## 🛠️ Hands-on builds

I prototype to pressure-test product ideas before they reach a roadmap. These repos are where I work out what "good" looks like and how to measure it.

### [resume-agent](https://github.com/MkRafa/resume-agent)
**Problem:** candidates can't tell if they fit a role, and AI-written resumes invent things.

**Approach:** grade the candidate against each requirement with cited evidence, then write a tailored resume where every claim traces back to a real fact.

**Results:** 82% agreement with human labels and 0 over-generous verdicts; the fact-checker missed 0 of 12 planted fabrications.

`LangGraph` `LLM evaluation` `Hallucination detection`

### [Coverage Determination Agent](https://github.com/MkRafa/agentic-rag-coverage-determination)
**Problem:** coverage questions ("is procedure C covered for condition D under plan L on date T?") need an answer *and* the policy clause that proves it.

**Approach:** an agent retrieves and cites policy clauses, a verifier re-checks every citation, and a rules-based gate decides whether to answer, escalate to a human, or refuse. The models reason, but they never make the final call.

`Agentic RAG` `MCP` `152-case eval suite`

### [Clinical Trial Pre-Screening](https://github.com/MkRafa/ct-prescreening)
**Problem:** coordinators manually screen patient notes against long inclusion/exclusion criteria.

**Approach:** the LLM judges each criterion with evidence; the final eligibility decision is plain code, so it stays auditable.

`Healthcare AI` `Document extraction`

<details>
<summary><b>More builds</b></summary>

- **ElderEase** (IE Venture Lab): a senior-services marketplace. I led the MVP, ran 40+ customer discovery interviews, validated product-market fit and pitched to investors.
- [**LangGraph Email Support Agent**](https://github.com/MkRafa/AI_LangGraph): classifies support emails, drafts replies, and routes to human approval.
- [**Clinic Appointments**](https://github.com/MkRafa/appointments): the step-by-step booking flow behind my clinic voice-agent experiments.

</details>

---

## 🧭 Career

| When | Where | Role |
|---|---|---|
| Jan 2026 – now | RagaAI | Senior Product Manager |
| Sep 2024 – Dec 2025 | IE Business School, Madrid | International MBA · IE Masters Scholarship |
| Apr 2023 – May 2024 | Sprinklr | Product Manager – Lead |
| Apr 2022 – Mar 2023 | Sprinklr | Senior Product Consultant |
| Jun 2021 – Mar 2022 | Sprinklr | Product Analyst |
| 2020 | Karlsruhe Institute of Technology, Germany | Research intern: startup internationalisation |
| 2017 – 2021 | IIT Hyderabad | B.Tech, Mechanical Engineering · Minor in Economics |

## 🧰 Toolkit

- **Product:** roadmapping · PRDs · solution architecture · customer discovery · QBRs · Figma · JIRA · Asana · SQL · Salesforce
- **AI:** agentic workflows · LLM evaluation & prompt engineering · RAG · MCP servers · conversational AI (ASR / NLP / TTS / STT) · Voice AI & IVR · OCR pipelines · RPA
- **Prototyping:** Claude Code · Codex · Cursor · Lovable · ElevenLabs · Retell AI · LangGraph · Python · AWS

## 🧠 How I work

- **Prioritise by value vs effort**, write the PRD, and define the solution architecture for each use case
- **Prototype before handoff:** I build agent flows in Claude Code and Codex to stress-test LLM edge cases and fallback logic, so AI scientists get a concrete interaction spec and fewer requirements change mid-sprint
- **Use LLMs only where judgment is needed** and keep the rest deterministic, to control latency, cost and auditability
- **Tie AI features to business KPIs** (CSAT, AHT, retention, adoption) and review them with customers

---

## 📫 Reach me

[![Portfolio](https://img.shields.io/badge/Portfolio-mkrafa.github.io-FF5A36?logo=googlechrome&logoColor=white)](https://mkrafa.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mann--khivasara-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/mann-khivasara)
[![Email](https://img.shields.io/badge/Email-mannkhivasara%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:mannkhivasara@gmail.com)

Always happy to talk AI products, Agentic Systems & Workflow Automations.
