# SecureAIFlow - Safe AI Code Assistant

> The AI coding assistant that keeps your secrets yours.

> Refactor, generate tests, explain code , without leaking credentials, or proprietary source to Public AI (OpenAI, Anthropic, or Google ... ).

![demo](images/vscode-saf.gif)

## Why SecureAIFlow?

AI coding assistants are transformative but in regulated environments,
sending prompts to third-party LLMs raises real questions:

- Does the prompt contain API keys, credentials, or customer PII?
- Is proprietary source code leaving your security perimeter?
- Can you prove to auditors what was sent, by whom, and when?

SecureAIFlow is the **security layer for AI coding**: every prompt is
redacted in real time, every request is logged, and sensitive data is
replaced with deterministic pseudonyms before it reaches any LLM provider
— OpenAI, Anthropic or Google.

Use the AI tools you love. Keep your secrets yours.

## Features
- 💬 **SAF Chat** in the sidebar — multi-turn, context-aware
- ✏️ **Refactor / Explain / Unit Tests / Docs** on any selection
- 🔐 **Real-time redaction** : API keys, credentials, PII, source code (F1 ~0.97)
- 🔄 **Multi-provider** : OpenAI, Claude, Gemini behind one interface
- 👁️ **Native diff viewer** : review every change before Accept/Reject
- 🏢 **Private mode** : route to your own on-prem LLM ( available to on-prem MODE)

## Quick start
1. Install the extension
2. Select code → right-click → SecureAIFlow → Refactor / Add Selection to Chat ...

## Requirements
- VS Code 1.85+
- SecureAIFlow account (free tier available at [secureaiflow.com](https://secureaiflow.com))

## Privacy & compliance
Prompts are processed in-memory on SecureAIFlow infrastructure. No prompt content is stored or used for training. GDPR-ready DPA available. On-premise deployment supported.

→ Full privacy policy ( check footer ): https://secureaiflow.com/

→ DPA: https://secureaiflow.com/legal-dpa

→ Subprocessors: https://secureaiflow.com/legal-subprocessors

## Support
- website: https://secureaiflow.com
- Email: team@secureaiflow-team.com
