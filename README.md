# NammaShield

**Multilingual AI Cyber-Safety for Every Indian**

Omnikon Hackathon 2026 | Problem Statement: Omni_CyberTech_1 — Regional-Language Phishing Detection
Institution: Sri Ramakrishna Institute of Technology

## Problem
Phishing in India increasingly targets non-technical users through regional and mixed-language text (e.g. Tanglish, Hinglish) — a segment underserved by existing English-first detection tools. Detection alone isn't protection: users also need to understand why a message is risky and what to do next.

## Solution
NammaShield analyses suspicious text, screenshots, or URLs; scores risk 0–100 with visible evidence; and returns localized safety guidance.

**DETECT** → Understand multilingual and mixed-language threats
**EXPLAIN** → Show the evidence behind the risk score
**PROTECT** → Recommend the safer next action, localized to the user's preferred language

## Key Features
1. Multilingual Threat Detection
2. Mixed-Language Intelligence (Tamil+English, Hindi+English, etc.)
3. Screenshot Scanner (OCR)
4. URL Intelligence
5. Explainable Risk Score (0–100)
6. Localized Safety Guidance
7. Scam Pattern Intelligence

## Tech Stack
| Layer | Choice |
|---|---|
| Frontend | React + Vite + Tailwind CSS |
| Backend | Python + FastAPI |
| NLP / AI | Pretrained multilingual model(s) + lightweight classification |
| OCR | Tesseract OCR |
| URL Analysis | Python URL parsing + suspicious-pattern indicators |
| Database | SQLite |

## Status
Round 1 submission — proposal and architecture stage. Full documentation in `/docs`.
