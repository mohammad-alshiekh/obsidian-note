---
tags: [THM, AI-Security, room, fundamentals, prompt-security]
status: In-Progress
module: AI Fundamentals
date: 2026-09-30
Room: Prompt Engineering Basics
---
# Prompt Engineering Basics

## 📝 Professional Summary
Covers how prompts control LLM behaviour and the structure of system, user and assistant messages. Foundation for understanding why prompt injection works.

## 🎯 Learning Objectives
* Understand system vs user prompts
* Use zero-shot, few-shot and chain-of-thought prompting
* See why LLMs cannot separate instructions from data

## 🧠 Key Concepts
* System prompt: hidden developer instructions
* User prompt: person's input
* Zero-shot / few-shot / chain-of-thought
* Roles, delimiters and output formats
* Context window: everything the model sees at once, trusted and untrusted mixed together

## 🛠️ Tools & Commands Used
* Chat playground / LLM chat interface

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Clear delimiters between instructions and data
* Never store secrets in the system prompt

## 💡 Key Takeaways
* Everything in the context window is just text to the model
* Good prompts improve results, but are not a security boundary

## 🎓 Exam Focus
* Define system prompt and context window
* Explain why prompts are not a security control

## 🔗 Related
* [[Prompt Injection Notes]]
* [[Prompt Defence Notes]]
