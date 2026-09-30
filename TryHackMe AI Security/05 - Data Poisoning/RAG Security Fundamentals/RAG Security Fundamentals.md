---
tags: [THM, AI-Security, room, data-poisoning, rag]
status: In-Progress
module: Data Poisoning
date: 2026-09-30
Room: RAG Security Fundamentals
---
# RAG Security Fundamentals

## 📝 Professional Summary
Explains Retrieval-Augmented Generation: documents are embedded, stored in a vector database, retrieved per query and added to the prompt. Each step is attack surface.

## 🎯 Learning Objectives
* Understand the RAG pipeline
* Identify RAG attack surface
* Apply access control to retrieval

## 🧠 Key Concepts
* Pipeline: ingest → chunk → embed → vector DB → retrieve → augment prompt → generate
* Embeddings and similarity search
* Vector/embedding weaknesses (OWASP LLM08)
* Retrieved content is untrusted input

## 🛠️ Tools & Commands Used
* Vector databases, embedding models

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Access control per document
* Validate and sanitise ingested content
* Separate tenants' data

## 💡 Key Takeaways
* RAG brings external data into the trusted prompt
* Retrieval must respect user permissions

## 🎓 Exam Focus
* Describe RAG steps
* Why retrieved data is untrusted

## 🔗 Related
* [[Data Poisoning in RAG Systems]]
* [[Sensitive Information Disclosure]]
