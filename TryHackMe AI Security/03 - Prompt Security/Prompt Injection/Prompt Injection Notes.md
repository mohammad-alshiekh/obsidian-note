---
tags: [THM, AI-Security, room, prompt-security, prompt-injection, owasp-llm]
status: In-Progress
module: Prompt Security
date: 2026-09-30
Room: Prompt Injection Notes
---
# Prompt Injection Notes

## 📝 Professional Summary
Prompt injection (OWASP LLM01) manipulates an LLM with crafted input so it ignores intended instructions. Covers direct injection by the user and indirect injection through external content.

## 🎯 Learning Objectives
* Explain why injection works
* Differentiate direct vs indirect
* Craft and test payloads

## 🧠 Key Concepts
* Direct injection: user types override instructions
* Indirect injection: hidden instructions in web pages, documents, emails, RAG content
* Goal types: leak system prompt, bypass policy, misuse tools, exfiltrate data
* Payload patterns: instruction override, role-play, delimiter confusion, encoding/obfuscation
* No clear separation between instructions and data

## 🛠️ Tools & Commands Used
* LLM chat interface, Burp Suite
* Payload lists

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Input/output filtering
* Least privilege for tools
* Separate and mark untrusted content
* Human approval for sensitive actions

## 💡 Key Takeaways
* Prompt injection is the top LLM risk
* Indirect injection needs no direct access to the chatbot

## 🎓 Exam Focus
* Definition + example of direct and indirect injection
* Why it is hard to fully prevent

## 🔗 Related
* [[Jailbreaking Notes]]
* [[Prompt Defence Notes]]
* [[OWASP Top 10 for LLM]]
