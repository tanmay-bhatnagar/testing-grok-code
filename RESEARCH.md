# THE FELON — Research Dossier

**Project**: Premium interactive single-page website about the Sukhoi Su-57 (NATO: Felon)  
**Date of Research**: May 2026 (tool-augmented open-source synthesis)  
**Guiding Principle**: All claims must be traceable to open reporting. Speculation and estimates are explicitly flagged in UI.

---

## 1. Program History & Status

- **Official Designation**: Sukhoi Su-57 (internal: T-50 / PAK FA during development).
- **Developer**: Sukhoi (United Aircraft Corporation), Russia.
- **First Flight**: 29 January 2010 (T-50-1 prototype).
- **Service Entry**: Limited operational capability declared ~2018–2020 with the 23rd Fighter Aviation Regiment (Komsomolsk-on-Amur). Full-rate production ramp ongoing but slow.
- **Production (open-source estimates as of early 2026)**: Approximately 42 airframes built (including 10+ prototypes/test articles). Operational fleet size commonly assessed in the low-to-mid 20s. Slow pace attributed to sanctions, engine supply, and economic factors.
- **Variants in development**: Su-57M (upgraded), two-seat Su-57D trainer/lead-in, potential export Su-57E (Algeria announced interest).

**Key Sources**:
- Wikipedia "Sukhoi Su-57" (heavily referenced to TASS, Russian MoD, Aviation Week, Piotr Butowski analyses)
- Airforce Technology profiles
- IISS Military Balance and FlightGlobal reporting

---

## 2. Technical Specifications (Baseline Production Single-Seat)

| Parameter              | Value (approx)                  | Notes / Source Caveats                     |
|------------------------|---------------------------------|--------------------------------------------|
| Length                 | 20.1 m                         | Standard across sources                    |
| Wingspan               | 14.1 m                         | —                                          |
| Height                 | 4.6 m                          | —                                          |
| Empty weight           | ~18,500 kg                     | Estimates vary                             |
| Max takeoff weight     | 34,000–35,000 kg               | —                                          |
| Internal fuel          | ~9,700 kg                      | —                                          |
| Engines (current)      | 2 × Saturn AL-41F1 (izdeliye 117) thrust-vectoring | 3D canted nozzles |
| Thrust (with AB)       | ~142–147 kN per engine (emergency) | AL-51F1 / izdeliye 30 in slow rollout |
| Max speed              | Mach 2.0 (high altitude)       | Manufacturer claim                         |
| Supercruise            | ~Mach 1.3 claimed              | Not independently verified at Western levels |
| Combat radius          | ~1,250 km (internal)           | Subsonic; less when supersonic             |
| Service ceiling        | 18,800–20,000 m                | —                                          |
| g-limit                | +9                             | —                                          |
| Hardpoints             | 12 total (6 internal stations primary stealth config) | Up to ~7,500 kg payload |
| Internal bays          | 2 large tandem + 2 side bays   | Critical for stealth                       |
| Gun                    | 30 mm GSh-30-1 (150 rds)       | Internal                                   |

**Primary Source**: Aggregated from Sukhoi/Wikipedia technical data + cross-checked with Airforce Technology.

---

## 3. Stealth & Low-Observability (Heavily Flagged)

**Critical**: All RCS figures in the public domain are **estimates**, derived from:
- Russian patent №2502643 (Sukhoi, ~2013) describing design goal of average RCS reduction to 0.1–1 m² vs Su-27 baseline ~10–15 m².
- Analyses by Piotr Butowski, Jane’s, and Western defense media.
- Visual inspection of airframe quality improvements between prototypes and serial aircraft.

**Commonly cited range for production Su-57**:
- Frontal aspect emphasis: **0.1–0.5 m²** (optimistic Russian-aligned sources) to **~0.5–1 m²** (more skeptical Western analyst compilations).
- All-aspect average higher due to rear quadrant and nozzle treatment being less optimized (Russian doctrine favors operations under friendly IADS cover).

**Comparison benchmarks (also estimates)**:
- F-22 Raptor: ~0.0001–0.0005 m² (all-aspect optimized, gold standard).
- F-35: ~0.001–0.005 m² class.
- J-20: Forward hemisphere competitive with Western 5th-gen; all-aspect compromised by canards.

**Design features actually implemented**:
- Planform edge alignment + serrated panels.
- ~22–26% composites by weight, extensive RAM coatings.
- Internal weapons carriage (primary).
- Partial S-duct inlets + blocker grids (engine face hiding).
- Metal-oxide coated canopy (~30% RCS reduction contribution).
- Production aircraft show improved flush fasteners and panel tolerances vs early T-50 prototypes.

**Limitations openly discussed**:
- Rear aspect RCS significantly higher.
- Large size increases vulnerability to low-frequency (VHF/UHF) early-warning radars.
- Early prototypes had visible gaps/rivets that hurt real-world performance.

**UI Treatment**: Every RCS or "stealthier than..." claim must carry a prominent "ESTIMATED — based on open-source analysis & patents. No independently verified public measurements exist." badge.

**Sources**: Wikipedia Su-57 stealth section + patent references, The War Zone / The Drive technical deep-dives.

---

## 4. Sensors & Avionics

- **N036 Byelka AESA radar** (X-band primary + L-band side-looking arrays for 360° coverage emphasis).
- **101KS Atoll electro-optical suite**: IRST, missile warning, laser warning, etc.
- Distributed aperture / side-looking radars (unique among peers for some mission sets).
- Advanced electronic warfare suite + secure datalinks.
- Claimed AI-assisted sensor fusion (maturity unverified publicly).

---

## 5. Weapons

**Stealth configuration (internal)**:
- R-77M (izdeliye 180) active-radar BVR
- R-74M2 short-range IR
- R-37M (izdeliye 810) very-long-range (claimed >200 km, folding fins)
- Kh-69 / Kh-59MK2 standoff cruise missiles
- Kh-38M tactical ASM
- KAB-250/500 precision-guided bombs
- Potential integration of hypersonic-class weapons (Kinzhal derivative discussions)

**External** (non-stealth missions): Full legacy Russian arsenal + heavy munitions.

**Gun**: 30 mm internal.

**Source**: Wikipedia + Airforce Technology feature.

---

## 6. Combat Record (Strict OSINT Lens)

### Syria (2018, 2019)
- Limited deployment of prototypes to Khmeimim AB.
- ~10 flights total across two rotations.
- Russian MoD claimed successful live firing of cruise missile (likely Kh-59MK2).
- No independent verification of target effects or significant operational impact. Viewed primarily as combat trials / marketing.

### Ukraine (2022–2026)
- Employed primarily as standoff missile truck launching long-range weapons (R-37M, Kh-69) from Russian or occupied airspace.
- Russian claims (Oct 2022+): Multiple Ukrainian aircraft kills (Su-27, Su-24) via R-37M.
- **OSINT status**: No visual, wreckage, or independent confirmation of air-to-air victories attributed specifically to Su-57.
- Notable confirmed event (5 Oct 2024): Su-57 deliberately downed its own malfunctioning S-70 Okhotnik-B UCAV over Ukraine (to prevent capture).
- Increased use in 2024 for Kh-69 strikes.

**Losses (visually/OSINT confirmed)**:
- 0 airframes destroyed in flight or combat.
- 1 confirmed damaged on ground (Akhtubinsk airbase, June 2024) by Ukrainian drone strike — shrapnel damage verified via Maxar satellite imagery + Russian milblogger admissions (Fighterbomber). Not a write-off in follow-up reporting.
- One prototype lost in non-combat factory test flight (Dec 2019, pilot ejected).

**Key takeaway for site**: Russia has treated the type as a scarce high-value asset and has not risked it in contested airspace in ways that would allow robust independent assessment of its combat effectiveness. Most "combat record" claims remain unverified.

**Primary Sources**:
- Wikipedia Su-57 + "List of aircraft losses during the Russo-Ukrainian War"
- Reuters (June 2024 Akhtubinsk reporting)
- Oryx-style visual confirmation methodology
- Ukrainian GUR statements + Russian Telegram milbloggers (cross-checked)

---

## 7. Peer Comparison (F-22 vs J-20 vs Su-57)

**Philosophy differences** (2026 synthesis):
- **F-22**: Ultimate all-aspect stealth + supercruise + sensor fusion for first-day air dominance in peer conflict. Small elite fleet (~195 built), no new production. Highest qualitative edge.
- **J-20**: Large, long-range, BVR-focused penetrator with massive production (300+ by late 2025, 100+/yr rate). Canard configuration trades some all-aspect stealth for agility + range. Strong PL-15/PL-21 missile reach.
- **Su-57**: Supermaneuverable multirole "system-of-systems" node. Trades lowest-observable performance for kinematic performance, side-array sensors, payload flexibility (internal + external), and affordability. Operates under protective IADS umbrella. Smallest fleet and slowest production ramp.

**Publicly discussed relative strengths** (all speculative at classified levels):
- Stealth: F-22 >> J-20 (forward) > Su-57
- Kinematics / Dogfight: Su-57 (3D TVC + high AoA) edges many assessments; F-22 extremely close.
- BVR Missile Reach: J-20 (PL-15) often cited with advantage.
- Numbers & Industrial Base: J-20 >> F-22 > Su-57
- Sensor Fusion Maturity: F-22 generally assessed highest (combat proven in limited ops); J-20 and Su-57 evolving rapidly.

**UI Treatment**: Interactive comparator must label every "winner" or score as "open-source analytical synthesis, not classified performance data."

---

## 8. Image Assets (All Wikimedia Commons — Verified Direct URLs)

All images used must carry proper attribution in captions/modals per license. No hotlinking abuse; these are stable Commons URLs.

### Su-57 / T-50 Primary Images
1. **Hero / Dramatic in-flight (high-res)**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/3/35/MAKS_Airshow_2019_(2019-08-30)_303.jpg`  
   4608×3456, 7.05 MB, CC0 1.0 (Public Domain Dedication) — Krassotkin, MAKS 2019.

2. **Iconic vapor cone / high-G maneuver**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/b/be/PAK_FA_Prandtl_Glauert_singularity.jpg`  
   2780×1853, CC BY-SA 3.0 — Rulexip, MAKS-2015.

3. **Formation pair (051 & 052) on ground at MAKS 2019**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/5/5b/Su-57_052_and_Su-57_051_in_MAKS_2019.jpg`  
   CC BY 4.0 — Kremlin.ru / President of Russia.

4. **High-resolution side/profile in flight (MAKS-2013)**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/4/40/T-50_PAK_FA_-_MAKS-2013Firstpixflights02.jpg`  
   5616×3744, CC BY-SA 4.0 — Vitaly V. Kuzmin (renowned aviation photographer).

5. **Canopy close-up**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/2/29/Sukhoi_T-50_PAK_FA_canopy.jpg`  
   CC license per file page.

6. **Technical 3-view line drawing (SVG)**  
   URL: `https://upload.wikimedia.org/wikipedia/commons/4/47/Sukhoi_T-50_3-view.svg`  
   Clean orthographic for specs section.

### Rival Images (for comparison sections)
- **F-22 Raptor in flight** (iconic Kadena shot):  
  `https://upload.wikimedia.org/wikipedia/commons/e/e2/F-22_Raptor_edit1.jpg` — Public Domain (USAF).

- **J-20 pair in formation (CCAS2022)**:  
  `https://upload.wikimedia.org/wikipedia/commons/f/f7/Two_J-20s_at_CCAS2022_(20220827103601).jpg` — High-res, CC BY-SA.

**Attribution Practice**: Every image in the final site will include a small "Source: Wikimedia Commons / Photographer + License" line in gallery captions and detail views.

---

## 9. Speculation & Uncertainty Flags (Mandatory for UI)

The following topics **must** be visually distinguished from verified facts:
- Exact RCS values and "stealth ranking"
- Real-world supercruise performance & sustained Mach 1.3 capability
- Combat effectiveness claims (especially air-to-air kills)
- "AI fusion" or sensor performance vs F-22/J-20
- Future engine (izdeliye 30) maturity and in-service dates
- Export success and actual delivered numbers
- "What would happen in a peer fight" scenarios

**Design Language for Flags**:
- Amber/gold "ESTIMATED" pill badges
- Expandable "Sources & Caveats" accordions
- Footnote-style hover or click "Open-source analysis only — no classified test data released"

---

## 10. Design & Interaction Direction (Post-Research)

**Tone**: Cinematic editorial — "Aviation Week meets high-end magazine feature". Dark (near-black + deep slate), restrained gold/amber + cyan accents, generous whitespace, large dramatic typography, film-grain subtle overlays.

**Must-have interactions** (beyond static):
- RCS signature visualizer (Canvas + angle sliders) — heavily disclaimer'd
- Dynamic rival comparator with Chart.js radar charts + priority weighting sliders
- Scroll-driven or click timeline with image/state sync
- Elegant pure-JS gallery + modal lightbox with keyboard and attribution
- Spec "explorer" that feels alive (animated counters, conditional readouts)
- Micro details: magnetic CTAs, progressive disclosure, smooth section transitions

**Tech Stack (single-file constraint)**:
- Pure HTML5 + Tailwind CSS via Play CDN (or hand-crafted premium CSS)
- Vanilla JS + Chart.js (CDN) for data viz
- Native Canvas for custom viz
- No build step. All assets remote (images from Commons, fonts system or Google Fonts if needed for editorial feel)

**Accessibility & Performance**: Semantic HTML, reduced-motion respect, lazy-loaded images, critical CSS inlined.

---

## 11. References & Further Reading (Non-Exhaustive)

- Wikipedia: Sukhoi Su-57 (and linked talk pages for debate on numbers)
- "List of aircraft losses during the Russo-Ukrainian War"
- Piotr Butowski writings (various aviation journals)
- The War Zone / The Drive technical articles on Felon RCS & weapons
- Reuters, BBC, FlightGlobal reporting on deployments and losses
- Russian MoD / TASS statements (always labeled as such)
- Wikimedia Commons Category:Sukhoi Su-57 (primary image source)

---

**Research Sign-off**: All content above synthesized from the cited open sources in May 2026. No classified material accessed or reproduced. The interactive site will surface these caveats prominently rather than bury them.

Next step: Translate into ambitious, beautiful, honest interactive experience on `dev` branch.