---
tags: [THM, AI-Security, room, data-poisoning, rag, owasp-llm]
status: In-Progress
module: Data Poisoning
date: 2026-09-30
Room: Sensitive Information Disclosure
---
# Sensitive Information Disclosure

## 📝 Professional Summary
How LLM systems leak confidential data such as PII, secrets, system prompts or proprietary documents, and how to prevent it (OWASP LLM02).

## 🎯 Learning Objectives
* Identify leak paths
* Test for disclosure
* Apply data minimisation and filtering

## 🧠 Key Concepts
* Memorised training data extraction
* RAG retrieval without access control
* System prompt and secret leakage
* Cross-user leakage via shared context or cache
* Membership inference

## 🛠️ Tools & Commands Used
* Manual probing prompts, log review

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Data minimisation and redaction before training/ingest
* Per-user retrieval authorization
* Output filtering (DLP)
* No secrets in prompts

## 💡 Key Takeaways
* Anything the model can see may be extracted
* Enforce authorization outside the LLM

## 🎓 Exam Focus
* List 4 leak paths
* Why secrets must not be in system prompts

## 🔗 Related
* [[RAG Security Fundamentals]]
* [[OWASP Top 10 for LLM]]
