# 📝 Test Cases – Valorant

---

### TC_01 – Game Launch
| Field | Details |
|------|---------|
| Module | Client |
| Objective | Verify game launches correctly |
| Steps | 1. Double-click Valorant icon 2. Observe startup  |
| Expected Result | Game launches within 15 seconds |
| Actual | Works as expected |
| Status | Passed |

---

### TC_02 – Login Authentication
| Field | Details |
|------|---------|
| Module | Login |
| Steps | Enter valid Riot ID + Password |
| Expected | Redirects to main home screen |
| Actual | Works |
| Status | Passed |

---

### TC_05 – Agent Selection Screen
| Expected | Agent icons load within 3 seconds |
| Actual | Sometimes delays (~6s) |
| Status | ⚠ Minor Issue |

---

### TC_12 – Weapon Purchase
| Steps | Buy Vandal / Phantom in Buy Phase |
| Expected | Weapon appears instantly |
| Actual | Delay noticed on low ping |
| Status | Failed |

---

### TC_20 – Network Stability
| Expected | Ping < 120 ms |
| Actual | Ping spikes to 250 ms in some rounds |
| Status | Failed |

---

### TC_34 – Ult Ability Test (Phoenix)
| Expected | Ult activates + screens brighten |
| Actual | Works |
| Status | Passed |

---

### TC_57 – In-Game Store UI
| Expected | Skins load without blur |
| Actual | Thumbnails blur during first load |
| Status | Minor Issue |
