<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# Ippa Kittum (ഇപ്പ കിട്ടും!) 🎯
> *"Play adichu nokk mone... ippa kittum! (Thottu kaanikkyedaa) 🥱"*  
> **🏆 100% Mathematically & Architecturally Unwinnable Parody Game**

---

## Basic Details
### Team Name: FaFa

### Team Members
- **Team Lead**: Fayiza Mariyam - KMEA Engineering College
- **Member 2**: Mohammed Fahim ES - KMEA Engineering College

---

## Project Description
*Ippa Kittum* is a hyper-polished, golden-hour arcade web game disguised as a friendly egg-catching challenge. Built with zero external dependencies using pure HTML5, CSS3, ES6 JavaScript, and real-time procedural Web Audio synthesis, the game lures players into a two-tiered psychological trap designed to crush hopes right at the finish line.

The game is divided into two deceptive phases:
1. **The Runaway "▶ NJEKKIKKO" Landing Prank**: The Start Button itself refuses to be clicked. It watches your cursor with googly pupils, panics into sweaty tremors, sprouts running sneakers, and frantically flees across the stage over 9 distinct behavioral stages while an interactive Kozhi podium, roaming spy cat, live odds ticker, and rage meter roast your lack of dexterity.
2. **The "Potta" Bucket Betrayal Arena**: Once players finally breach the start screen, they enter a golden-hour arcade arena where a hen glides on an aerodynamic spear perch dropping eggs with trailing wind streaks. Equipped with a wooden bucket reinforced with hazard tape (`⚠️ POTTA`), the player attempts to catch 10 eggs. However, the game physics are 100% rigged:
   - If an egg lands in the bucket's left-hand blowout hole, it slips straight through and splatters on the floor.
   - If an egg lands on the intact right rim, the hard base shatters it on impact anyway (*"100% catch, 100% pottal!"*).
   - If the player misses, it shatters on the floor.
   - Result: Guaranteed **0/10 saved eggs**, crowning the player with the legendary **"THOTTU THOPIYETTU! 🤡"** defeat screen.

---

## The Problem (that doesn't exist)
Modern humans suffer from dangerously inflated self-confidence, an unhealthily low daily frustration quotient, and a naive, unwarranted belief that hard work and precision always yield success. Furthermore, our sociologists identified an alarming, catastrophic shortage of digital Malayali poultry specifically engineered to instill existential dread, build false hope, and shatter dreams right before victory.

---

## The Solution (that nobody asked for)
We engineered a zero-dependency, hyper-reactive browser experience that delivers maximum comedic emotional damage across two distinct stages:

### Phase 1: The Interactive Pre-Game Gauntlet
- **Living Prank Button (`#playBtn`)**:
  - **Googly Eye Cursor Tracking**: Pupils calculate trigonometric angles (`Math.atan2`) to gaze directly at the user's cursor in real time.
  - **Panic Tremor & Sweat**: As the cursor nears (<110px), the eyes dilate red (`.panic`), sweat drops appear (`💧`), and the button trembles in fear.
  - **9-Stage Evasion State Machine**: Progresses through shakes, teleports, shrinking, erratic jittering, and animated running sneakers (`.btn-legs`) with cloud dust puffs (`💨`) and taunts (*"Dhaa ivide! 😜"*, *"Odi mone! 🏃"*).
- **Interactive Kozhi (Hen) Glass Podium**:
  - Real-time pupil tracking, poke reactions, clucking sounds, and feather bursts (`🪶`).
  - **Decoy Chick Surprise**: Poking 3 times spawns a surprise bouncing chick (`🐣`) with high-pitched chirps.
  - **Costume Wardrobe (5 Outfits)**: Switch between *Naadan* (classic), *Thug Life 😎* (shades & straw), *Raja Kozhi 👑* (crown), *Dr. Kozhi MBBS 🩺* (head mirror), and *CID Kozhi 🕵️‍♂️* (trench hat & mustache).
  - **"🌽 Theetta Kodukk" Mini-Game**: Feed corn kernels to the hen to trigger animated pecking, tail wiggling, and the laying of a sparkling **Golden Fortune Egg (`🥚✨`)** containing satirical Malayali fortunes.
- **Arcade Dashboard & Troll Cosmetics**:
  - **Live Odds Ticker**: Real-time ticker showing *"Jayikkanulla Chance: 0.000000%"*, which drops into negative percentages as you play (`-99.999% CHANCE THEERNNU 💥`).
  - **Player Patience Gauge**: Decays in real-time from 100% to *"0% (Choodaayi Puka! 🔥)"*.
  - **Rage Meter**: Nitro gauge filling up with every failed click up to `100% (FULL KOPAM! 🤬)`.
  - **Pro Tips Sticky Note**: Interactive pinned note cycling through 7 satirical pro-tips on click.
  - **Drifting Troll Clouds**: Clickable sky clouds (`☁️`) that pop and rain sarcastic emoji showers (`😂`, `🥚`, `⚡`).
  - **6-Point Surveillance Spy Cat (`😼`)**: A roving feline state machine that peeks from all 6 screen edges (bottom-right, bottom-left, bottom-center, left border, right border, and upside-down from the top edge) brandishing Malayalam protest placards (*"Thottu thopiyetto? 😂"*, *"Kozhi 1 - Nee 0 🤡"*, *"Screen-inte ella side-ilum njan undu! 🚩"*).
  - **Surrender Certificate**: Clicking *"Enne kondu aavoolla"* awards the player an official downloadable-style **"OFFICIAL THOLVI CERTIFICATE"** 📜.

### Phase 2: The Rigged "Potta" Bucket Arena
- **Aerodynamic Spear Perch SVG (`170px × 24px`)**:
  - Hand-crafted SVG featuring an oak wood shaft, dual brass binding rings, gold collar, razor-sharp steel blade with center specular shine, and a crimson fluttering streamer tassel.
  - Directional speed streaks (`.spear-wind-streaks`) that trail behind the spear and flare up when the hen squats to lay an egg.
  - Dynamic wind gust particles (`💨`, `彡`, `〰️`) drifting across the arena during movement.
- **The "Potta" Wooden Bucket SVG (`116px × 60px`)**:
  - Detailed curved staves with oak gradients, arched steel wire handle with wooden grip, twin brushed steel hoops with gleaming rivets, and caution hazard tape: **`⚠️ POTTA`**.
  - **The Permanent Blowout Fracture**: Prominently features a jagged bottom-left hole showing the arena floor beneath.
- **Velocity Tilt Inertia Physics**:
  - Moving the bucket left/right calculates mouse velocity `vx` and tilts the bucket dynamically up to `±14°`, returning to level with frame-by-frame exponential damping (`basketTilt *= 0.86`).
- **The Triple-Fail Catch Logic**:
  - *Left hole catch*: Egg slips through the hole with accelerated speed (`1.35x`), tumbling straight through to shatter on the floor.
  - *Right rim catch*: Egg collides with the solid steel/wood base, triggers an elastic squash bounce (`@keyframes basketBounce`), rings out with a metallic iron CLANG, and shatters on impact (*"Perfect catch! Still broke, kandilla? 🤦‍♂️"*).
  - *Floor miss*: Shatters into 4 distinct shell shards and glowing yolk with sarcastic roasts.
  - Result: Every egg is guaranteed to break. Final score: `Veena Mutta: 10`, `Pottiyathu: 10`, `Rakshapetta Mutta: 0`.

---

## Technical Details

### Technologies Used
For Software:
- **Languages**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Frameworks**: None (100% Pure Vanilla Web Architecture — 0 external npm dependencies)
- **Audio Architecture**: Native Browser **Web Audio API** — Complete real-time procedural sound synthesis engine (no external audio MP3/WAV files):
  - `playCluck()`: Dual-oscillator square wave FM synthesis with randomized pitch.
  - `playCrack()`: Synthesized white-noise buffer with exponential gain decay.
  - `playClang()`: Triangle + Sine harmonic dual oscillator for resonant metallic bucket strikes.
  - `playWhoosh()`: Sweeping sine-wave pitch drop for button dodges and wind gusts.
  - `playWahWah()`: 4-step descending sawtooth "sad trombone" for surrender events.
  - `playChirp()`, `playBoing()`, `playPeck()`, `playPop()`, `playSqueak()` for micro-interactions.
- **Rendering & Animation**: Pure DOM + SVG rendering with CSS Keyframes and a high-precision `requestAnimationFrame` game loop with delta-time normalization.
- **Typography & Aesthetics**: Golden Hour Arcade Glassmorphism palette, Google Fonts (`Outfit`, `Fredoka`, `Nunito`).
- **Tools Used**: Visual Studio Code, Git, GitHub, Browser Developer Tools.

For Hardware:
- **Main components**: Pure Web Software (No physical hardware required).
- **Specifications**: Runs smoothly on any device with a modern web browser (Chrome, Edge, Safari, Firefox).
- **Required peripherals**: 1x Mouse, Trackpad, or Touchscreen; 1x Set of speakers/headphones; 1x Healthy sense of humor and infinite emotional resilience.

---

## Implementation

### Installation
```bash
# Clone the repository
git clone https://github.com/faheec/useless_project_temp.git

# Navigate into the project directory
cd useless_project_temp
```

### Run Locally
```bash
# Open index.html directly in any web browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html

# Or run via Python local development server:
python -m http.server 8000
```

### Built-in Judge & Preview Anchors
For judging review and rapid testing, you can jump directly into specific screens using URL hash anchors:
- **Standard Start Screen**: `index.html`
- **Instant Gameplay Arena**: `index.html#preview-game`
- **Instant Defeat Overlay**: `index.html#preview-lose`

---

## Project Documentation

### Architecture & Player Journey Flowchart
```mermaid
flowchart TD
    Start([User clicks ▶ NJEKKIKKO]) --> ChooseCosmetic[Equip Kozhi Cosmetics: Thorthu / Sunglasses / Crown]
    ChooseCosmetic --> SpawnHen[Hen glides horizontally on Spear Perch]
    SpawnHen --> DropEgg[Hen drops high-velocity egg with wind streaks]
    DropEgg --> PlayerControl[Player moves Potta Bucket left/right]
    PlayerControl --> CatchCheck{Catch egg?}
    CatchCheck -- Miss early --> EarlyCrack[Egg cracks on floor -> Life lost]
    CatchCheck -- Caught --> IncrementScore[Score increases: 1/10 ... 8/10]
    IncrementScore --> NineScore{Score reaches 9/10?}
    NineScore -- No --> SpawnHen
    NineScore -- YES: Final 10th Egg! --> FalseHope[10th Egg drops into Bucket]
    FalseHope --> PottaBlowout[⚠️ BUCKET BOTTOM BLOWOUT!]
    PottaBlowout --> FloorShatter[Egg falls straight through hole and shatters]
    FloorShatter --> Defeat[🤡 'THOTTU THOPIYETTU!' Defeat Screen]
    Defeat --> CatRoast[Spy Cat roams screen borders with savage Malayalam signs]
    CatRoast --> Replay([Player clicks TRY AGAIN out of pure rage])
    Replay --> SpawnHen
```
*Figure 4: Complete state machine & emotional journey of an Ippa Kittum player.*

For Hardware:

# Schematic & Circuit
*Not Applicable — This is a pure web software project.*  
*(The only electrical circuits involved are the microchips inside your CPU sweating while computing unwinnable physics).*

# Build Photos
*Not Applicable — Pure digital artifact with 0 physical hardware components.*  
*(All builds occur instantaneously in the browser DOM).*

### Project Demo
# Video
[Demo Video Link](https://github.com/faheec/useless_project_temp) *(Replace with your YouTube/Drive demo video link once recorded)*  
*Demonstrates the googly-eyed runaway start button, cosmetic wardrobe switching, corn feeding minigame, fortune egg cracking, 6-zone cat surveillance, spear perch wind animations, bucket tilt inertia, and the inevitable 10/10 Potta bucket blowout betrayal.*

### Additional Links
- **Source Code Repository**: [https://github.com/faheec/useless_project_temp](https://github.com/faheec/useless_project_temp)
- **Live Local Preview**: Open `index.html` directly in your browser.

---

## Team Contributions

### Fayiza Mariyam (Team Lead)
- **Conceptual Direction & Satirical Writing**: Devised the core comedic premise of an unwinnable Malayali arcade game and wrote all Manglish roasts, pro-tips, Kozhi Devi fortunes, and cat protest placards.
- **UI/UX Design System**: Crafted the **Golden Hour Arcade Glassmorphism** visual theme, multi-stop radial gradient lighting, crystal blur cards, and responsive layout for mobile and desktop screens.
- **Character Design & Cosmetics**: Conceptualized and styled the Kozhi accessory wardrobe (*Naadan*, *Thug Life*, *Raja Kozhi*, *Dr. Kozhi MBBS*, *CID Kozhi*), drifting troll clouds, and the Official Tholvi Certificate modal.

### Mohammed Fahim ES (Member 2)
- **Game Engine & Physics Loop**: Engineered the frame-rate independent `requestAnimationFrame` game loop, delta-time normalization, and the velocity-driven bucket tilt inertia physics (`vx` damping).
- **SVG Modeling & Visual FX**: Designed the detailed SVG vector assets directly in code: the aerodynamic **Spear Perch SVG** with trailing wind streaks and the **Potta Bucket SVG** with jagged blowout fracture and caution hazard tape.
- **Procedural Web Audio Engine**: Architected the 100% synthesized Web Audio sound engine (clucks, cracks, metallic clangs, whooshes, squeaks, and sad trombone) requiring zero external audio assets.
- **AI State Machines & Git Management**: Implemented the 9-stage button evasion logic, cursor eye-tracking math, 6-border roaming spy cat state machine, and repository maintenance.

---

Made with ❤️ at TinkerHub Useless Projects

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)

