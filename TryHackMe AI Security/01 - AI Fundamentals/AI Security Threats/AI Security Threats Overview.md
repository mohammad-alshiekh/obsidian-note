---
tags: [THM, AI-Security, room, fundamentals, owasp-llm]
status: In-Progress
module: AI Fundamentals
date: 2026-09-30
Room: AI Security Threats Overview
---
# AI Security Threats Overview

## 📝 Professional Summary
Maps the main attack categories against AI systems, from attacks on data and models to attacks on the application layer. Gives the vocabulary used across all later modules.

## 🎯 Learning Objectives
* Classify threats by lifecycle stage
* Recognise attacks on confidentiality, integrity and availability of AI
* Map threats to OWASP LLM Top 10 and MITRE ATLAS

## 🧠 Key Concepts
* Evasion (adversarial examples): crafted input causes misclassification at inference
* Data poisoning: corrupt training data to implant bias or backdoors
* Model extraction/theft: replicate a model via repeated queries
* Model inversion & membership inference: leak training data or whether a record was used
* Prompt injection & jailbreaking: manipulate LLM instructions
* Denial of service / unbounded consumption: exhaust compute or tokens
* Supply chain attacks: malicious models, datasets or libraries

## 🛠️ Tools & Commands Used
* MITRE ATLAS - matrix of adversary tactics against AI
* OWASP Top 10 for LLM - risk list

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Input validation and output filtering
* Rate limiting and authentication
* Adversarial testing and red teaming
* Trusted sources for models and data

## 💡 Key Takeaways
* Threats exist at data, model, pipeline and application layers
* Classic CIA triad still applies to AI

## 🎓 Exam Focus
* Match each attack name to its lifecycle stage
* Difference between poisoning (training time) and evasion (inference time)

## 🔗 Related
* [[OWASP Top 10 for LLM]]
* [[AI Threat Modelling]]
