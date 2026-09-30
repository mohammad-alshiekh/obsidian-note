---
tags: [THM, AI-Security, room, data-poisoning, rag, prompt-injection, owasp-llm]
status: In-Progress
module: Data Poisoning
date: 2026-09-30
Room: Data Poisoning in RAG Systems
---
# Data Poisoning in RAG Systems

## 📝 Professional Summary
How attackers insert malicious or misleading content into knowledge bases or training data to manipulate outputs, plant backdoors or deliver indirect prompt injection (OWASP LLM04).

## 🎯 Learning Objectives
* Understand poisoning goals and vectors
* Demonstrate poisoned document retrieval
* Detect and mitigate poisoning

## 🧠 Key Concepts
* Training-time vs retrieval-time poisoning
* Backdoor triggers
* Poisoned documents with hidden instructions
* Ranking manipulation to force retrieval
* Misinformation injection

## 🛠️ Tools & Commands Used
* Document upload features, embedding/search tools

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Source verification and content approval
* Integrity checks and versioning of the knowledge base
* Anomaly detection on ingested data
* Output monitoring

## 💡 Key Takeaways
* A single poisoned document can control answers
* Trust only vetted data sources

## 🎓 Exam Focus
* Explain poisoned RAG document attack
* Difference from training-data poisoning

## 🔗 Related
* [[RAG Security Fundamentals]]
* [[Prompt Injection Notes]]
