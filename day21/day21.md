Day 21 — Privacy Intelligence Dashboard 🔐


60 Day Claude Challenge | Day 21 of 60



What I Built

A fully interactive Privacy Intelligence Dashboard that analyzes your digital footprint based on the apps and services you use daily. Just provide a list of apps — Claude builds a premium cybersecurity-style dashboard that reveals what companies likely know about you.

No private databases. No personal data accessed. Just app names → full risk analysis.


Live Preview


Screenshot / GIF of dashboard here




Features

SectionDescription🔴 Digital Footprint Score0–100 score rating your data exposure level🔐 Privacy Score0–100 score rating your privacy posture🌡️ Exposure HeatmapColor-coded risk grid across all 15 services🏢 Company Exposure RankingRanked list of parent companies by data risk📊 Data Collection MatrixPer-app breakdown of identity, location, biometric, financial data collection likelihood🕸️ Risk RadarChart.js radar chart across 6 risk dimensions🧬 Digital Twin ProfileWhat platforms likely infer about you (all Estimates)💡 WOW Insights5 non-obvious cross-app privacy risks💎 Most Valuable Data AssetsRanked list of your most commercially sensitive data🎛️ Privacy Improvement SimulatorInteractive — remove apps and watch your privacy score improve live📋 Privacy Improvement Plan7 concrete, actionable steps✅ Final VerdictSummary badge and risk statement


My Results (Sample Dataset — 15 Apps)

Apps analyzed: Instagram, Snapchat, TikTok, YouTube, Discord, WhatsApp, iMessage, Spotify, Roblox, PUBG Mobile, Amazon, Meesho, Google Search, Google Pay, Google Photos

Digital Footprint Score : 74 / 100  →  🟠 Significant
Privacy Score           : 28 / 100  →  🔴 Weak
Parent Companies        : 7
Ecosystem Concentration : 71% (Google + Meta dominant)
Tracking Surface        : High — 8+ data categories

Top Company Exposure

RankCompanyAppsScore1GoogleSearch, Pay, Photos, YouTube952MetaInstagram, WhatsApp883ByteDanceTikTok854AmazonAmazon725Snap Inc.Snapchat65

WOW Insights Discovered


📍 Location triangulation — Google Search + Pay + Photos + Instagram + Snapchat can build a near-continuous location timeline without GPS access
🧠 Facial indexing — Instagram, Snapchat, Google Photos may each hold biometric facial data
💸 Spending estimation — Amazon + Meesho + Google Pay signals income bracket and spending velocity to advertisers
🎮 Gaming identity linkage — PUBG Mobile + Roblox device IDs can be cross-referenced with social accounts
🌐 7 ad auctions — you are likely bid on thousands of times daily across 7 company networks



Tech Stack


Claude — AI analysis, risk scoring, insight generation
HTML / CSS — Single-file interactive dashboard
Chart.js — Risk radar visualization
Vanilla JS — Privacy Improvement Simulator logic



How to Use


Clone or download dashboard.html
Open in any browser — no server needed
Optionally swap in your own app list in the prompt to regenerate for your dataset



Key Learnings


15 app names is enough for a meaningful privacy risk profile — no access to private data needed
Ecosystem concentration is as important as the number of apps — 3 companies dominate my footprint
Cross-app correlation is the real risk — each app alone is manageable; combined they create a detailed behavioral model
Interactive simulators make abstract privacy concepts tangible and actionable
Claude can generate complete, self-contained HTML dashboards with working charts and interactive state in a single pass



Disclaimer

All risk scores, inferences, and Digital Twin Profile traits are Estimates based on publicly known industry data practices. No private databases were accessed. No certainty is claimed about any individual's actual data exposure. Facts (app list) and Estimates (inferences) are clearly separated throughout the dashboard.


Connect


🐙 GitHub: SANT0SH7
💼 LinkedIn: devsantosh
🏷️ Challenge: #60DayClaudeChallenge



Day 21 of 60 — Building one AI-powered tool every day with Claude.
