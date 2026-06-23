# AEGIS-1 Terminal: Season 1 Complete

---

## 🌌 Overview

**AEGIS-1 Terminal: Season 1 Complete** is an immersive, text-based psychological cosmic horror game built using the Twine ecosystem and the SugarCube story format. Players take on the role of an operative awakening on a malfunctioning space station, forced to navigate a shifting reality while balancing survival and data extraction.

---

## 🚀 Features

* **Dynamic Vital Telemetry**: Real-time side-panel monitoring of Oxygen (O2) supply and Sanity levels, featuring automated critical alerts when resources fall dangerously low.


* **Evidence Log Matrix**: A secure archive tracking database that monitors recovered data packets regarding "Case File 24" to prevent duplication.


* **Branching Narratives & Multiple Endings**: Player decisions dictate the progression pathway, leading to different final outcomes such as the True Climax Ending or the Uncertain Survival Route.


* **Immersive Cybernetic UI**: Custom-built style layouts emulating old-school CRT computer screens, complete with terminal blink animations and structural hull rumble effects.



---

## 🛠️ Technical Stack

* **Story Format**: SugarCube v2.37.3


* **Language/Syntax**: Twee / CSS / Vanilla JavaScript


* **State Management**: Implements secure array lookups and safe boundary tracking (`Math.max()`) to ensure absolute runtime stability and prevent negative value bugs.


* **Configuration**: Optimized for persistent browser storage with automatic autosaves enabled and a controlled history state cap.



---

## 📂 Project Structure

* `AEGIS-1 Terminal SS1 .twee`: The core game architecture containing story passage nodes, initialization scripts, custom widgets, and stylesheet elements.


* `images/`: Directory hosting ambient visual assets embedded natively into key narrative frames like the Central Junction and Season 1 Finale Climax artwork.



---

## 💻 How to Compile and Play

To compile this project into a playable standalone HTML file, you can utilize **Tweego** (the command-line compiler for Twine) or manually import the source contents into the Twine desktop application.

### Using Tweego:

```bash
tweego -o index.html "AEGIS-1 Terminal SS1 .twee"

```
