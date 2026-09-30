---
tags: [THM, AI-Security, room, fundamentals, concept]
status: In-Progress
module: AI Fundamentals
date: 2026-09-30
Room: AI Models and Data
---
# AI Models and Data

## 📝 Professional Summary
Explains how models are stored, shared and fed with data, and why data quality, provenance and file format choices are security decisions.

## 🎯 Learning Objectives
* Understand datasets and splits (train/validation/test)
* Compare model file formats and their risks
* Recognise bias and data-quality issues

## 🧠 Key Concepts
* Training, validation and test datasets
* Model formats: pickle/PyTorch `.pt/.pth/.bin` (can execute code on load), `safetensors` (weights only), ONNX, GGUF
* Model hubs (e.g. Hugging Face) as public repositories
* Bias, label quality and data drift
* Data provenance: where data came from and who changed it

## 🛠️ Tools & Commands Used
* `sha256sum` - verify file integrity
* `pickletools` / model scanners - inspect pickles

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Prefer safetensors over pickle
* Verify hashes and sources
* Version and sign datasets

## 💡 Key Takeaways
* Loading an untrusted pickle model = arbitrary code execution
* Bad data produces bad and unsafe models

## 🎓 Exam Focus
* Know why safetensors is safer than pickle
* Explain data provenance

## 🔗 Related
* [[Data Poisoning MOC]]
* [[AI Supply Chain MOC]]
