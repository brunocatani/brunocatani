# Bruno Catani

Senior Software Developer by day. The rest of the time I reverse-engineer Fallout 4 VR and build the physics engine it should have shipped with.

---

## ROCK / PAPER / SCISSORS — a VR interaction stack, built from nothing

Fallout 4 VR has no source code and no documentation for its VR-specific internals — including its own build of Havok physics. Nothing like this stack existed for it, so I mapped the binary with Ghidra and raw disassembly and built the physics on top myself: real per-finger collision, two-handed grabbing, active ragdoll.

<p align="center">
  <img src="https://raw.githubusercontent.com/brunocatani/ROCK/main/public/ROCK.png" width="48%" alt="ROCK">
  <img src="https://raw.githubusercontent.com/brunocatani/SCISSORS/main/public/SCISSORS.png" width="48%" alt="SCISSORS">
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=tPaIzmZ9P0o&t=113s"><strong>Watch ROCK in action &rarr;</strong></a>
</p>

| Project | What it does |
|---|---|
| **[ROCK](https://github.com/brunocatani/ROCK)** | Physics-based hand interaction. Full per-bone/per-finger body collision, real weapon collision, two-hand grabbing, and object handling driven by actual Havok rigid-body physics instead of scripted animation. The core of the stack — everything else builds on it. |
| **[SCISSORS](https://github.com/brunocatani/SCISSORS)** | Active ragdoll physics: damage, impulse, and full-body reaction running on top of ROCK's collision layer. |
| **PAPER Toolkit** *(to be released)* | Toolkit for probing and mapping FO4VR weapon animations, and fully integrating with ROCK's weapon interactions. |
| **[Collision Visualizer F4VR](https://github.com/brunocatani/CollisionVisualizerF4VR)** | The debugger I had to build to build the rest of this: renders every live Havok collision body, layer, and constraint directly into the VR headset. |
| **[hFRIK](https://github.com/brunocatani/hFRIK)** | Not mine — I'm an active contributor to the VR body/skeleton engine ROCK is built on. |

---

## Also, the day job

Senior Software Developer & AI Engineer, Brazil. Python/C++ backend, LLM agent systems, and WhatsApp-scale integrations.

**Stack:** Python · C++ · TypeScript · PyTorch/LangChain · AWS/Azure

<sub>[LinkedIn](https://www.linkedin.com/in/bruno-henrique-catani/) · [Email](mailto:brunohcatani@gmail.com)</sub>
