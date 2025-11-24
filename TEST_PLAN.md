# 📘 Test Plan – VALORANT (Updated 2025)

## 1. Scope & Goals
Validate gameplay features, UI/UX, performance (including UE5-related rendering changes), network resilience, and anti-cheat interactions across PC and console (PS5/Xbox Series S|X — console parity matters for cross-progression flows). :contentReference[oaicite:12]{index=12}

## 2. In-Scope Features
- Client installation, launcher and updates
- Account login / Riot ID / MFA flows
- Agent selection & ability behavior
- Weapon purchase and buy-phase mechanics
- Matchmaking, ranked/competitive flows
- Cross-progression & account sync between PC and consoles (skin/ownership checks). :contentReference[oaicite:13]{index=13}
- Performance variations introduced by UE5 rendering features
- Interaction with Riot Vanguard (boot-time behavior and compatibility checks). :contentReference[oaicite:14]{index=14}

## 3. Out-of-Scope
- Server source code / anti-cheat internals beyond user-observable behavior
- Third-party backend services not surfaced in-game

## 4. Test Environment Matrix
- **PC**: Win10/11, GPU tiers: low / mid / high (to test 30/60/144+ FPS). Minimum requirements per Riot support. :contentReference[oaicite:15]{index=15}
- **Console**: PS5 and Xbox Series X|S (validate cross-progression and parity of unlocks). :contentReference[oaicite:16]{index=16}
- **Network**: Stable 20–40 ms, simulated 100–300 ms, packet loss 0–5%.

## 5. Test Types
- Functional (gameplay, UI)
- Performance (FPS, frame time, stutters — esp. after UE5 migration)
- Network (latency spikes, reconnection)
- Compatibility (Vanguard interactions, other kernel-level drivers)
- Regression & Smoke

## 6. Exit Criteria
- All critical/major issues resolved or accepted
- Repro rate < 1% for critical issues under test harness
- Performance baseline met on recommended hardware
