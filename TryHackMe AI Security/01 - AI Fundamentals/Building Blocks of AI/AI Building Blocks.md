---
tags: [THM, AI-Security, room, fundamentals, concept]
status: In-Progress
module: AI Fundamentals
date: 2026-09-30
Room: AI Building Blocks
---
# AI Building Blocks

## 📝 Professional Summary
Introduces the core components of modern AI: machine learning, deep learning, neural networks and large language models. Explains the lifecycle (data → training → evaluation → deployment → inference) and shows where each stage introduces security risk.

## 🎯 Learning Objectives
* Differentiate AI, ML, DL and LLMs
* Understand the training vs inference lifecycle
* Identify the components of an AI system (data, model, pipeline, API)

## 🧠 Key Concepts
* Machine Learning: models learn patterns from data instead of explicit rules
* Neural networks: layers of weighted nodes; deep learning = many layers
* Transformers and attention: architecture behind LLMs
* Tokens and embeddings: text converted to numbers/vectors
* Training vs inference: learning phase vs answering phase
* Model parameters/weights are the valuable intellectual property

## 🛠️ Tools & Commands Used
* `python` / `pip` - ML environment
* Jupyter Notebook - experimenting with models

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Secure each lifecycle stage separately
* Access control on training data and model files
* Monitor inference endpoints

## 💡 Key Takeaways
* AI is a pipeline, not just a model; attackers can target any stage
* Weights and training data are high-value assets

## 🎓 Exam Focus
* Be able to list the stages of the ML lifecycle
* Explain training vs inference with a threat example for each

## 🔗 Related
* [[AI Security Threats Overview]]
* [[AI Models and Data]]
