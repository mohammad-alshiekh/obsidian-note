---
tags: [THM, AI-Security, room, secure-ai]
status: In-Progress
module: Secure AI Systems
date: 2026-09-30
Room: Securing AI Systems Notes
---
# Securing AI Systems Notes

## 📝 Professional Summary
Security controls across the whole AI stack: data, training environment, model storage, serving infrastructure and APIs. Applies classic security principles to ML pipelines.

## 🎯 Learning Objectives
* Apply defence-in-depth to AI
* Secure training and serving environments
* Manage access to models and data

## 🧠 Key Concepts
* Least privilege for data scientists and services
* Secrets management for API keys
* Network segmentation of training/inference
* Model access control and API authentication
* Monitoring and anomaly detection
* Secure MLOps/CI-CD

## 🛠️ Tools & Commands Used
* IAM policies, vaults, WAF/API gateway

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Authenticate and rate-limit model APIs
* Encrypt data at rest/in transit
* Audit and log all model access
* Isolate model execution (sandbox/container)

## 💡 Key Takeaways
* Standard security hygiene prevents most AI incidents
* Model APIs are attack surface like any API

## 🎓 Exam Focus
* Name controls per layer: data, model, infra, API

## 🔗 Related
* [[LLM Security Notes]]
* [[AI Forensics]]
