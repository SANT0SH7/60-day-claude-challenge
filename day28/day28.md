# Day 28 — Hospital Admission Readiness Simulator

> **60 Day Claude Challenge** | Healthcare Operations with Claude

## 🏥 Project Overview

A browser-based interactive simulation of real hospital admission workflows. Built using Claude to generate a complete single-file HTML application that teaches healthcare operations through hands-on decision-making.

Users experience the full admission process — from provider setup to final admission decision — and learn how administrative, insurance, and clinical factors all impact patient admission outcomes.

---

## ⚙️ Features

- **Provider & Physician Setup** — Configure hospital provider and attending physician details
- **Diagnosis & Admission Type Selection** — Choose from multiple clinical scenarios
- **Prior Authorization Engine** — Simulate PA approvals, pending requests, and appeals
- **Real-Time Readiness Scoring** — Live admission readiness score updated as workflows progress
- **Risk Reduction Workflows** — Resolve documentation, insurance, bed availability, and clinical risks
- **Governance Snapshot** — Full operational review before final admission decision
- **Final Admission Decision** — Approve, delay, or flag admission based on completed steps

---

## 💡 Key Learnings

1. **Prior Authorization is a bottleneck** — A medically ready patient can still face admission delays due to PA status alone.
2. **Documentation gaps = administrative risk** — Incomplete records directly lower admission readiness scores.
3. **Multi-stakeholder coordination** — Providers, insurers, utilization review teams, nursing, and admin must all be aligned.
4. **Claude can simulate complex workflows** — A single prompt generated a complete, functional healthcare simulation app.
5. **Interactive learning > passive reading** — Going through the admission steps yourself builds deeper operational understanding.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| App Type | Single-file HTML application |
| Styling | Tailwind CSS (CDN) |
| Logic | Vanilla JavaScript |
| AI Generator | Claude (Anthropic) |

---

## 📂 Files

```
Day28/
├── day28.md                          # This file
├── hospital_admission_simulator.html  # Generated HTML application
└── screenshots/                      # Simulator workflow screenshots
    ├── readiness_score.png
    ├── prior_auth_scenario.png
    └── final_decision.png
```

---

## 🚀 How to Run

1. Download `hospital_admission_simulator.html`
2. Open in any modern browser (Chrome / Firefox / Edge)
3. No installation or dependencies required
4. Enter provider details and follow the admission workflow

---

## 📸 Screenshots

<!-- Add your simulator screenshots here -->

---

## 🔗 Challenge Info

- **Challenge:** 60 Day Claude Challenge
- **Day:** 28 / 60
- **Category:** Healthcare Operations
- **Difficulty:** Intermediate
- **Time:** ~60 minutes
- **Deliverable:** GitHub commit URL

---

*Built with ❤️ using Claude by Anthropic — #60DayClaudeChallenge*
