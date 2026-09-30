---
tags: [THM, AI-Security, room, supply-chain, owasp-llm]
status: In-Progress
module: AI Supply Chain Security
date: 2026-09-30
Room: Understanding AI Supply Chains
---
# Understanding AI Supply Chains

## 📝 Professional Summary
Maps the components of an AI supply chain and explains why each external dependency is a trust decision (OWASP LLM03).

## 🎯 Learning Objectives
* List supply chain components
* Identify trust boundaries
* Understand transitive risk

## 🧠 Key Concepts
* Components: pre-trained models, datasets, ML libraries, plugins, containers, cloud services
* Model hubs and registries
* Transitive dependencies
* Fine-tuned models inheriting hidden behaviour

## 🛠️ Tools & Commands Used
* `pip list`, dependency graphs

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Inventory every dependency
* Use trusted registries

## 💡 Key Takeaways
* You inherit the security of everything you import
* Models are code-like artifacts

## 🎓 Exam Focus
* Draw an AI supply chain and mark trust points

## 🔗 Related
* [[Supply Chain Attack Vectors]]
* [[AI Models and Data]]
