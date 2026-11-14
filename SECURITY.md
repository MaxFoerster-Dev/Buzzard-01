# Security Policy

## Project Status & Supported Versions
**Buzzard-01** is currently an experimental, work-in-progress hobby project. Security updates and design fixes are applied exclusively to the latest state of the `main` branch.

| Component / Version | Supported |
| :--- | :--- |
| `main` branch (Latest PCB, 3D models & code) | ✅ Yes |
| Older commits / previous revisions | ❌ No |

## Physical & Hardware Safety Disclaimer
This repository contains designs for a model rocket, 3D-printed structural parts, and custom flight avionics (KiCad PCB and MicroPython firmware). **Building and launching model rockets involves inherent risks.**

* **Build at your own risk:** All files are provided "as is" without any warranty. The author is not responsible for physical injury, property damage, or legal issues resulting from the use or modification of these designs.
* **Battery & Electronics Safety:** When building the flight computer, ensure proper polarity, short-circuit protection, and safe handling of LiPo/alkaline batteries.
* **Launch Regulations:** Always follow local aviation laws, fire safety regulations, and established model rocketry safety codes (e.g., NAR or local equivalents). Never launch near people, buildings, dry vegetation, or airports.

## Reporting a Vulnerability or Critical Flaw
If you discover a critical flaw in the **KiCad schematics/PCB** (e.g., short circuits, thermal hazards) or a vulnerability in the **MicroPython flight software** (e.g., crashes, sensor read failures, unintended pyro/servo triggers), please report it responsibly:

1. **Do not** open a public issue for severe safety or security flaws before they are reviewed.
2. Contact the maintainer directly via email at **[DEINE-E-MAIL-ADRESSE]** (or use GitHub's *Private Vulnerability Reporting* feature under the **Security** tab).
3. Include a brief description of the issue, affected files, and steps to reproduce or fix it.

You can expect an initial response within a few days. Once verified, a fix will be pushed to the `main` branch.
