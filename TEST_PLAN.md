# 📘 Test Plan – Valorant Game Testing

## 1. Introduction
Valorant is a 5v5 tactical FPS game.  
The goal of this test plan is to validate gameplay mechanics, UI components, game stability,  
and feature functionality.

## 2. Test Scope
### In Scope
- Game launch & client functionality  
- Login, authentication, Riot ID validation  
- Agent selection  
- Weapons & ability usage  
- In-game store  
- Matchmaking & server connection  
- Ping & network stability  
- UI/UX  
- Performance (FPS drops, texture loading)

### Out of Scope
- Server-side architecture  
- Anti-cheat system internals (Vanguard)  
- Payment gateways

## 3. Test Environment
| Component | Details |
|----------|---------|
| OS | Windows 10 – 64 bit |
| GPU | NVIDIA GTX 1650 |
| RAM | 8 GB |
| Network | 40–80 ms ping average |
| Game Version | Episode 9 / 2025 |

## 4. Test Types
- Functional Testing  
- UI/UX Testing  
- Compatibility Testing  
- Performance Testing  
- Smoke & Regression Testing  
- Network Testing  
- AI-assisted Testing (test case generation + analysis)

## 5. Exit Criteria
- All critical bugs resolved  
- No game-breaking issues  
- Stable FPS (above 80)  
- No matchmaking failures in 10 tries
