---
tags: [THM, AI-Security, room, supply-chain, attack]
status: In-Progress
module: AI Supply Chain Security
date: 2026-09-30
Room: Supply Chain Attack Vectors
---
# Supply Chain Attack Vectors

## 📝 Professional Summary
Catalogue of attacks through the supply chain, especially malicious model files and tampered datasets and packages.

## 🎯 Learning Objectives
* Recognise attack vectors
* Understand malicious serialization
* Assess impact

## 🧠 Key Concepts
* Malicious pickle/model files executing code on load
* Typosquatting and dependency confusion for packages and models
* Backdoored pre-trained models
* Poisoned public datasets
* Compromised CI/CD or model hub accounts

## 🛠️ Tools & Commands Used
* `pickletools`, `python`, model scanners

## 🚶 Walkthrough / Notes
(Write your notes, payloads, and screenshots here)

## 🛡️ Defences & Mitigations
* Never load untrusted pickle files
* Scan models before use
* Pin versions and hashes

## 💡 Key Takeaways
* Loading a model can equal running attacker code
* Public does not mean safe

## 🎓 Exam Focus
* Explain how a pickle payload executes
* Define typosquatting

## 🔗 Related
* [[Securing the AI Supply Chain]]
* [[Payload]]
* [[Checkpoint]]
