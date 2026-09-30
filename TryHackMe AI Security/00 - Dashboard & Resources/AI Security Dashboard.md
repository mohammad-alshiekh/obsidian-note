---
tags: [THM, AI-Security, dashboard]
date: 2026-09-30
---
# 🛡️ TryHackMe AI Security Dashboard

## 🗺️ Modules
1. [[AI Fundamentals MOC]]
2. [[Secure AI Systems MOC]]
3. [[Prompt Security MOC]]
4. [[AI Supply Chain MOC]]
5. [[Data Poisoning MOC]]
6. [[AI Security Glossary]] | [[OWASP Top 10 for LLM]]

## 📊 All Rooms (Dataview)
```dataview
TABLE module, status, date
FROM #THM AND #room
SORT module ASC
```

## 🚧 In Progress
```dataview
LIST
FROM #THM
WHERE status = "In-Progress"
```

## ✅ Completed
```dataview
LIST
FROM #THM
WHERE status = "Done"
```

## 🏷️ Tag Classification System
| Tag | Meaning |
|---|---|
| `THM` | Everything from TryHackMe |
| `AI-Security` | Whole course |
| `room` / `challenge` / `concept` / `tool` / `MOC` | Note type |
| `fundamentals`, `secure-ai`, `prompt-security`, `supply-chain`, `data-poisoning` | Module |
| `prompt-injection`, `jailbreak`, `rag`, `owasp-llm`, `threat-modelling`, `forensics` | Topic |

## 🔄 Status values
`Not-Started` → `In-Progress` → `Done` → `Revised` (mark Revised after exam revision)

## 📅 Exam Revision Checklist
- [ ] Reviewed every Key Takeaways section
- [ ] Memorised OWASP Top 10 for LLM
- [ ] Practised all payloads in challenges
- [ ] Reviewed glossary
