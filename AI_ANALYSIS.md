# 🤖 AI-Assisted Testing – VALORANT (Updated)

## How AI was used (concrete steps)
1. **Test-case expansion** — used prompts to generate edge-case scenarios for agent ability combos and unusual input sequences (e.g., ability + animation-cancel sequences).  
2. **Performance triage** — fed sample FPS/time-series data into an ML prompt to highlight probable causes (asset streaming vs CPU spike).  
3. **Bug prioritization** — generated severity recommendations based on impact to competitive integrity (e.g., Vanguard conflicts = critical).  
4. **Automation ideas** — suggested scripts for repeated buy-phase latency testing using a network emulator + headless client and screenshot diffing.

## Example prompts used
- “List 30 edge-case test scenarios for an FPS buy-phase and equipment flow.”  
- “Given frame time series [0.016, 0.017, 0.05, 0.016], name likely causes and next diagnostic steps.”

## Notes on trust & verification
AI outputs were treated as suggestions and validated manually during test runs. All primary facts (engine migration, specs, Vanguard behavior, and console support) were verified against Riot/major press pages. :contentReference[oaicite:24]{index=24}
