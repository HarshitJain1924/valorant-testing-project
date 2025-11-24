# 🐞 Bug Reports – VALORANT (Updated)

---

## BUG_UI_UE5_001 – UE5 Asset Streaming Causes First-Load Stutter
**Severity:** Medium  
**Steps:** 1. Fresh client start after patch 2. Load into match 3. Observe frame drops in first 30s  
**Expected:** Smooth entry without major stutters  
**Actual:** 1–2 second micro-stutter on low-end GPU; likely asset streaming change from UE5 conversion. :contentReference[oaicite:22]{index=22}  
**Status:** Open

---

## BUG_GAMEPLAY_PURCHASE_002 – Delayed Weapon Equip During Buy Phase
**Severity:** High  
**Steps:** 1. Buy Phase → purchase rifle 2. Observe equip latency  
**Expected:** Immediate equip  
**Actual:** 300–800 ms delay under simulated high-latency network  
**Impact:** Competitive disadvantage  
**Status:** Open

---

## BUG_NETWORK_VANGUARD_003 – Vanguard causing conflict with other kernel anti-cheats
**Severity:** Critical  
**Steps:** 1. Install Valorant (Vanguard) 2. Install another beta game with kernel anti-cheat 3. Attempt to launch both  
**Expected:** Both launch or clear guidance provided  
**Actual:** Second game fails to launch; Vanguard interaction suspected — documented widely in community and reported by vendors. :contentReference[oaicite:23]{index=23}  
**Status:** Open

---

## BUG_CROSSPROG_004 – Cross-progression item sync delay
**Severity:** Low  
**Steps:** 1. Claim cosmetic on PC 2. Link console account 3. Check for cosmetic on PS5/Xbox within 5 minutes  
**Actual:** Items sync but sometimes take several minutes (log timing and repro steps)  
**Status:** Open
