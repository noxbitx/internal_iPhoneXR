# internal_iPhoneXR
Experimental MobileGestalt rebuild and internal device restoration project. Reverse engineering activation pathways on a rare, unactivatable iPhone XR test unit. Research-focused, educational only.



# MobileGestalt Revival Project (iPhone XR Internal Restoration)

## Project Status
- [x] Project Started
- [x] Test Unit Confirmed (internal SEP-configured iPhone XR)
- [x] Deep File Analysis (MobileGestalt / Activation_Record exploration)
- [ ] A12 Exploit Research (early stage)
- [ ] MobileGestalt Rebuild Attempt
- [ ] ActivationRecord Spoofing
- [ ] Setup.app Bypass Tests
- [ ] Successful Boot Without Activation
- [ ] Full Documentation Writeup

---

## Overview
This project focuses on restoring limited functionality to a rare iPhone XR internal-use test unit that cannot be activated via traditional methods. The phone is missing critical activation files and factory data, rendering it permanently stuck in Setup.app.

The goal is to experiment with MobileGestalt structure rebuilding and explore potential bypass strategies without relying on official Apple tools.

---

## Key Findings
- Device missing: `MobileGestalt.plist`, `Activation_Record.plist`, `Factory_Ticket.plist`.
- Displays **"Need to Hacktivate?"** log — internal configuration confirmed.
- Activation not possible via PurpleRestore without valid MobileGestalt and activation data.
- Shortcuts tricks used to gain partial filesystem access.

---

## Experimental Approaches
- Pulling MobileGestalt templates from a working iPhone X.
- Manually building spoofed Activation_Record files.
- Investigating potential A12-compatible exploits to access lower-level tools.
- Using Flask-based local server tests to fake Setup.app endpoints.

---

## Current Screenshots
*( In `/media` folder.)*

---

## Tools & References
- Device: iPhone XR (internal unit)
- Tools: Shortcuts.app, Termux, Flask Server, PurpleRestore research
- Research Sources: [https://theapplewiki.com/wiki/Main_Page]

---

## Disclaimer
This project is for educational and research purposes only.  
No proprietary Apple software is distributed or reverse-engineered here.

---
