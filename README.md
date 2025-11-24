# 🎮 Valorant – Game Testing & QA Analysis Project (Updated 2025)

This is an updated QA test project for Riot Games' VALORANT, built using latest public information (engine migration, patches, platform support, and anti-cheat behavior). This repo contains test plans, test cases, sample bug reports, and notes on how AI accelerated the QA workflow.

## Important verified facts used in this project
- VALORANT recently migrated development to **Unreal Engine 5** (from UE4) to enable new tooling and improved rendering/performance. :contentReference[oaicite:5]{index=5}
- Official system requirements and recommended specs are referenced from Riot's support pages. :contentReference[oaicite:6]{index=6}
- Riot’s **Vanguard** anti-cheat runs at a deep system level and has produced compatibility concerns with other kernel-level anti-cheats; Riot has publicly discussed plans to reduce kernel-level footprint. :contentReference[oaicite:7]{index=7}
- VALORANT is available on **PC** and has launched on **PS5 & Xbox Series X|S**; cross-progression is supported while crossplay between PC and consoles is limited to preserve competitive fairness. :contentReference[oaicite:8]{index=8}

## Project Contents
- TEST_PLAN.md
- TEST_CASES.md
- BUG_REPORTS.md
- AI_ANALYSIS.md
- /screenshots (add captures here)

## Test environment recommended (derived from official specs)
- OS: Windows 10 (Build 19041+) or Windows 11 (64-bit). :contentReference[oaicite:9]{index=9}
- RAM: 4 GB minimum (8+ GB recommended for smooth testing). :contentReference[oaicite:10]{index=10}
- GPU: Mid-range GPU for 60+ FPS testing (GTX 1050 Ti recommended as a baseline). :contentReference[oaicite:11]{index=11}

## How to use
1. Clone repo.  
2. Run test cases locally while recording logs/screenshots.  
3. Upload screenshots to `/screenshots` and update `BUG_REPORTS.md`.  
