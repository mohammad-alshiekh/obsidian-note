---
tags: [THM, AI-Security, room, prompt-security, defence]
status: In-Progress
module: Prompt Security
date: 2026-09-30
Room: Prompt Defence Notes
---
# Prompt Defence Notes

## 📝 Professional Summary
Layered defensive controls against prompt attacks, combining prompt design, filtering, architecture and monitoring.

## 🎯 Learning Objectives
* Design a layered defence
* Implement input and output guardrails
* Test defences with adversarial prompts

## 🧠 Key Concepts
* Hardened system prompts (necessary, not sufficient)
* Input sanitisation and classifiers
* Output validation and encoding
* Privilege separation and tool allowlists
* Dual-LLM / guard model pattern
* Logging and alerting

## 🛠️ Tools & Commands Used
* Guardrail libraries, moderation APIs

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Defence in depth
* Assume the prompt will be bypassed; limit blast radius
* Regular red-team testing

## 💡 Key Takeaways
* No single defence stops prompt injection
* Limit what the model can do, not only what it can say

## 🎓 Exam Focus
* List 5 layers of prompt defence

## 🔗 Related
* [[Prompt Injection Notes]]
* [[LLM Security Notes]]
