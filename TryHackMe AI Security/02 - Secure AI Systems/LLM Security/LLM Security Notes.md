---
tags: [THM, AI-Security, room, secure-ai, owasp-llm]
status: In-Progress
module: Secure AI Systems
date: 2026-09-30
Room: LLM Security Notes
---
# LLM Security Notes

## 📝 Professional Summary
Focuses on LLM-specific risks in applications: prompt injection, insecure output handling, excessive agency, system prompt leakage and data exposure through plugins and tools.

## 🎯 Learning Objectives
* Understand LLM application architecture
* Identify LLM-specific vulnerabilities
* Apply guardrails and least privilege to agents

## 🧠 Key Concepts
* LLM app = user input + system prompt + retrieved data + tools + output handling
* Improper output handling: model output used unsafely (XSS, SQLi, command injection)
* Excessive agency: too many tools/permissions
* System prompt leakage
* Guardrails / input & output filters

## 🛠️ Tools & Commands Used
* Guardrail frameworks, content filters, LLM proxies

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Treat model output as untrusted input
* Least-privilege tools, human approval for risky actions
* Validate and sanitise input and output
* Monitor and rate limit

## 💡 Key Takeaways
* Never trust model output
* Agents amplify impact of any injection

## 🎓 Exam Focus
* Map each LLM risk to OWASP ID
* Explain excessive agency with example

## 🔗 Related
* [[OWASP Top 10 for LLM]]
* [[Prompt Injection Notes]]
