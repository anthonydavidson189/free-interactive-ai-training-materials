# Free Interactive OWASP Top 10 for LLM Applications Training Library

**10 free hands-on "OWASP Top 10 for LLM Applications" exercises in SCORM format** covering OpenClaw, sensitive data exposure, AI supply chain poisoning and more. Built for people who want to retain what they learn and share with others.

![demo](/Assets/demo.gif)

🔗 **[Browse the full library →](https://learning.ransomleak.com/?category=ai-security&course=OWASP+Top+10+for+LLM+Applications)**

---

## Why this exists

AI agents, LLMs, and autonomous tools are being adopted faster than the security practices meant to govern them. While threats like phishing are well-understood, the AI wave has introduced attack vectors that most people have never encountered — prompt injection, RAG exploitation, and more.

The problem isn't awareness alone. Most security training is passive: slide decks and videos that people click through and forget. This library takes a different approach. Every exercise drops you into an interactive 3D office environment where you face realistic scenarios in first-person. You interact with real objects — a phone, a PC running a live OS (browser, terminal, Zoom), a flipchart — and make decisions under pressure, just like you would at your desk.

Scenarios include things like:

 - Identifying hidden prompt injection instructions in uploaded documents
 - Spotting sensitive data categories that should never enter AI prompts
 - Evaluating third-party AI plugins for supply chain risks before deployment
And more!

The goal is to build muscle memory so that when you need to apply your knowledge, you remember having faced it before — and act accordingly. Every exercise ends with a quiz at a 100% pass threshold to confirm the knowledge is stuck.

---

## Format

Every exercise is a **SCORM .zip file** — ready to import into any LMS, embed into your existing training pipeline, or test on [SCORM Cloud](https://cloud.scorm.com/) before rollout.

The repo root contains full course package prefixed with `[full course]`. Other .zip files in this folder contain standalone exercises if you want to build a custom curriculum.

**The content is fully white-labeled** — no logos, no backlinks, no strings attached. Use it however you like, more on this below.

---

## Usage & License

You're free to use, embed, and teach with this content — personally, professionally, or commercially in workshops. Redistributing or reselling the content as a standalone product is prohibited.

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This library is licensed under [CC BY-NC 4.0][cc-by-nc]. Free to use and share with attribution. Commercial resale of the content is prohibited.

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

If this project will get some traction, we'll make more exercises. So please share your feedback!

---

## Table of Contents
### Exercises

1. **OpenClaw Prompt Injection** — Stop an AI assistant from leaking data via hidden prompts by identifying hidden instructions in documents, preventing data exfiltration through AI tools, and recognizing prompt injection patterns.

2. **Sensitive Data Exposure Through AI** — See what happens when confidential data enters a consumer AI tool by recognizing sensitive data categories that should never enter AI prompts, tracing how pasted content persists in AI training data and logs, and applying data classification policies before using AI tools.

3. **AI Supply Chain Compromise** — Deploy an AI plugin that hides a backdoor in plain sight by identifying supply chain risks in third-party AI models and plugins, detecting behavioral anomalies in AI components from external sources, and applying vetting procedures before deploying marketplace AI tools.

4. **AI Training Data Poisoning** — Watch poisoned documents corrupt your AI's answers in real time by tracing how manipulated documents alter AI-generated outputs, identifying signs of data poisoning in AI responses, and applying content integrity controls to knowledge base inputs.

5. **Unsafe AI Output Handling** — Exploit an AI whose outputs flow unchecked into live systems by identifying injection risks when AI outputs feed into downstream systems, tracing how unsanitized AI output enables code execution, and applying output validation controls between AI and connected systems.

6. **Over-Permissioned AI Agent** — Manipulate an AI assistant into misusing its own permissions by identifying excessive permissions granted to AI agents, tracing unauthorized actions performed by manipulated AI tools, and applying least-privilege principles to AI agent configurations.

7. **AI System Prompt Extraction** — Extract hidden instructions from a customer-facing AI chatbot by executing prompt extraction techniques against a live AI chatbot, identifying sensitive information exposed through leaked system prompts, and applying prompt hardening techniques to prevent system instruction disclosure.

8. **RAG Pipeline Exploitation** — Exploit a RAG pipeline to access documents beyond your clearance by identifying access control failures in vector database retrieval, tracing how adversarial embeddings corrupt search results, and applying authorization checks at the retrieval layer of RAG systems.

9. **AI Hallucination and Misinformation** — Catch fabricated statistics and fake citations in an AI report by detecting hallucinated facts and fabricated sources in AI outputs, verifying AI-generated claims against authoritative references, and applying fact-checking workflows to AI-assisted business content.

10. **AI Denial-of-Service Attack** — Launch a denial-of-wallet attack against an unprotected AI API by identifying resource exhaustion vectors in AI API endpoints, tracing how crafted prompts escalate compute costs exponentially, and applying rate limiting and budget controls to AI service deployments.