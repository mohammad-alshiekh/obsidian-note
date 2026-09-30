---
tags: [THM, AI-Security, room, secure-ai, threat-modelling]
status: In-Progress
module: Secure AI Systems
date: 2026-09-30
Room: AI Threat Modelling Notes
---
# AI Threat Modelling Notes

## 📝 Professional Summary
Structured method to identify threats before attackers do, adapting STRIDE and using MITRE ATLAS and OWASP resources for AI-specific risks.

## 🎯 Learning Objectives
* Draw data-flow diagrams for AI systems
* Apply STRIDE to AI components
* Prioritise risks and select mitigations

## 🧠 Key Concepts
* Assets: training data, model weights, prompts, embeddings, user data
* Trust boundaries: user ↔ app ↔ model ↔ tools ↔ data stores
* STRIDE: Spoofing, Tampering, Repudiation, Information disclosure, DoS, Elevation of privilege
* MITRE ATLAS tactics and techniques
* Risk = likelihood × impact

## 🛠️ Tools & Commands Used
* Data-flow diagrams, MITRE ATLAS, OWASP resources

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Model threats at design time
* Re-run threat model after each architecture change

## 💡 Key Takeaways
* Identify assets and trust boundaries first
* Threat modelling is proactive, pentesting is reactive

## 🎓 Exam Focus
* Write STRIDE examples for an LLM chatbot
* Define trust boundary

## 🔗 Related
* [[AI Security Threats Overview]]
* [[Securing AI Systems Notes]]
