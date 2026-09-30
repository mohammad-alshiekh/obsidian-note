---
tags: [THM, AI-Security, cheatsheet, owasp-llm]
date: 2026-09-30
---
# OWASP Top 10 for LLM Applications (2025)

| ID | Risk | One-line summary | Key mitigation |
|---|---|---|---|
| LLM01 | Prompt Injection | Inputs alter model behaviour or instructions | Filtering, least privilege, approval for actions |
| LLM02 | Sensitive Information Disclosure | Leak of PII, secrets or proprietary data | Redaction, access control, output filtering |
| LLM03 | Supply Chain | Vulnerable/malicious models, data, libraries | AI-BOM, verify hashes, trusted sources |
| LLM04 | Data and Model Poisoning | Manipulated training or fine-tune data | Data validation, provenance, monitoring |
| LLM05 | Improper Output Handling | Model output used unsafely downstream | Treat output as untrusted, encode/validate |
| LLM06 | Excessive Agency | Too much autonomy/permission for LLM agents | Least privilege, human-in-the-loop |
| LLM07 | System Prompt Leakage | Exposure of hidden instructions/secrets | No secrets in prompts, external controls |
| LLM08 | Vector and Embedding Weaknesses | RAG/vector store attacks and leaks | Access control, sanitise ingested data |
| LLM09 | Misinformation | False or misleading output | Grounding, verification, human review |
| LLM10 | Unbounded Consumption | Resource exhaustion, cost abuse, extraction | Rate limits, quotas, monitoring |

> Verify the current list at owasp.org/www-project-top-10-for-large-language-model-applications before your exam.

## Module mapping
- Prompt Security → LLM01, LLM07
- Supply Chain → LLM03
- Data Poisoning → LLM02, LLM04, LLM08
- Secure AI Systems → LLM05, LLM06, LLM10
