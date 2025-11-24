# 📝 Test Cases – VALORANT (Updated)

### TC_01 – Client Install & Patch
| Module | Client/Launcher |
| Objective | Verify install + update flow on Windows 10/11 |
| Steps | 1. Download installer 2. Install 3. Launch 4. Watch auto-patch process |
| Expected | Installer completes, patches applied; client launches to main menu |
| Notes | Validate installer works after UE5 migration (assets/patch size differences may apply). :contentReference[oaicite:17]{index=17}

---

### TC_05 – Account Login + MFA
| Module | Authentication |
| Steps | 1. Enter Riot ID 2. Enter Password 3. Complete MFA (if enabled) |
| Expected | Successful redirect to home; cross-progression link shows console-owned items if linked. :contentReference[oaicite:18]{index=18}

---

### TC_12 – Agent Abilities (Functional)
| Module | Gameplay |
| Steps | Execute each ability in controlled map instance |
| Expected | Visual + mechanical effect matches ability docs; no UE5-render artifacts |

---

### TC_18 – Weapon Buy Phase (Latency)
| Objective | Verify weapon purchase responsiveness under varied network conditions |
| Steps | 1. Enter buy phase 2. Purchase weapon 3. Observe equip delay |
| Expected | Instant equip; record and log any delays (server/engine-induced). Note: report if UE5 asset streaming causes delay. :contentReference[oaicite:19]{index=19}

---

### TC_22 – Performance Baseline
| Objective | FPS & frame-time stability (30/60/144 tiers) |
| Steps | Run custom match, record FPS via client overlay or FRAPS |
| Expected | Meets recommended thresholds on given spec tiers (Riot support specs). :contentReference[oaicite:20]{index=20}

---

### TC_30 – Vanguard Interaction (Compatibility)
| Objective | Check if Vanguard blocks other kernel-level software or causes startup issues |
| Steps | Install Valorant with Vanguard; install another tested anti-cheat or software known to run at kernel level; reboot; attempt to launch other software |
| Expected | Document conflicts, workarounds, and whether uninstall or disable is required; capture logs. Note: Vanguard has known deep-system interactions — see support pages. :contentReference[oaicite:21]{index=21}
