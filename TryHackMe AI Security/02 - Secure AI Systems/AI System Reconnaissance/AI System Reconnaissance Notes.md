---
tags: [THM, AI-Security, room, secure-ai, recon]
status: In-Progress
module: Secure AI Systems
date: 2026-09-30
Room: AI System Reconnaissance Notes
---
# AI System Reconnaissance Notes

## 📝 Professional Summary
Enumeration of an AI target: discovering the model, its guardrails, connected tools, data sources and exposed endpoints, to plan realistic attacks or assess exposure.

## 🎯 Learning Objectives
* Fingerprint the underlying model
* Discover tools, plugins and APIs
* Probe guardrail behaviour and system prompt

## 🧠 Key Concepts
* Model fingerprinting via behaviour, error messages and headers
* Enumerating available tools/functions and data sources
* Probing for system prompt and policy boundaries
* API endpoint discovery and documentation
* Passive vs active recon

## 🛠️ Tools & Commands Used
* `curl`, Burp Suite, browser dev tools
* `nmap` for exposed services

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Minimise information in errors and banners
* Restrict API documentation exposure
* Monitor probing patterns

## 💡 Key Takeaways
* Recon quality determines attack quality
* Verbose errors leak architecture

## 🎓 Exam Focus
* List 3 recon techniques against an LLM chatbot

## 🔗 Related
* [[Prompt Injection Notes]]
* [[AI Threat Modelling Notes]]
