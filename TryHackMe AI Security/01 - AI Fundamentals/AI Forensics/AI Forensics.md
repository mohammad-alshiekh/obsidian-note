---
tags: [THM, AI-Security, room, fundamentals, forensics]
status: In-Progress
module: AI Fundamentals
date: 2026-09-30
Room: AI Forensics
---
# AI Forensics

## 📝 Professional Summary
Introduces investigation of incidents involving AI: what evidence exists, how to collect it and how to reconstruct what a model was asked and did.

## 🎯 Learning Objectives
* Identify AI evidence sources
* Reconstruct an incident timeline
* Preserve integrity of evidence

## 🧠 Key Concepts
* Evidence sources: prompt/response logs, API logs, model versions, training data, vector DB content, tool call history
* Provenance and model versioning
* Hashing artifacts to prove integrity
* Timeline analysis of prompts and tool invocations

## 🛠️ Tools & Commands Used
* `sha256sum`, `jq`, `grep` - log analysis
* Log platforms / SIEM

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Log prompts, outputs and tool calls with retention policy
* Version and hash models and datasets
* Protect logs (they may contain sensitive data)

## 💡 Key Takeaways
* Without logging there is no AI forensics
* Hash first, analyse later

## 🎓 Exam Focus
* List 4 artifacts an investigator collects from an LLM app
* Why hashing matters

## 🔗 Related
* [[Securing AI Systems Notes]]
* [[AI Fundamentals MOC]]
