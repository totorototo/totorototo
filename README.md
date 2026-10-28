# Hi there, I'm Thomas 👋

I'm a developer passionate about building tools that bridge the gap between technology and the outdoors. I work across the full stack, from polished frontend experiences (React) to systems-level work (Zig, geospatial libraries). I enjoy solving problems that require both precision and performance.

### 🏔️ What I'm building
**Trail suite**: a prepare → plan → race → review toolchain for ultra trail running, in the browser on a Zig/WASM core:
- 🔨 **[Waymark](https://github.com/totorototo/waymark)**: Edit a race director's GPX, pin waypoints and cut-offs on a map, export an extended GPX.
- 🔨 **[Regimen](https://github.com/totorototo/regimen)**: Plan the race on a Waymark course: pace model, checkpoint arrivals and cut-off margins, fueling, exported as `plan.json` for Terminus and Retrace.
- 🔨 **[Terminus](https://github.com/totorototo/terminus)**: Race intelligence PWA. GPS route analysis, effort modelling (Minetti), offline maps, live tracking and 3D visualization.
- 🔨 **[Retrace](https://github.com/totorototo/retrace)**: Plan-vs-actual race analysis PWA. Compares the predicted plan with the executed run (FIT).

Zig libraries powering them:
- ✅ **[gpxz](https://github.com/totorototo/gpxz)**: GPX analytics and plan library + CLI.
- ✅ **[fitz](https://github.com/totorototo/fitz)**: Garmin FIT file parser + CLI.
- ✅ **[debriefz](https://github.com/totorototo/debriefz)**: Plan-vs-actual comparison library + CLI, built on gpxz and fitz.

Training data:
- 🔨 **[Ledger](https://github.com/totorototo/ledger)**: Garmin Connect dashboard (Personal API): yearly and all-time totals, training load, running efficiency. Ships Claude Code skills that read the exported stats and publish insights: weekly review, load check, aerobic progress, and race and trail/ultra time predictors fitted on your own races.

Earlier work:
- ✅ **[navigo](https://github.com/totorototo/navigo)**: Rust/WASM geospatial crate, on npm as `@totorototo/navigo` ([demo](https://navigo-demo.netlify.app)).
- 📦 [Ultra Buddy](https://github.com/totorototo/ultra-buddy) · [Positic](https://github.com/totorototo/positic) · [Lybitos-Strava](https://github.com/totorototo/strava)

### 🛠️ Tech Stack
- **Languages:** JavaScript, TypeScript, Zig, Rust, OCaml (ReasonML)
- **Frameworks & tools:** React, Vite, Zig/WASM (Zigar), Rust/WASM, MapLibre, Three.js, PartyKit, Claude Code
- **Interests:** Full-stack Development, Frontend Architecture, Systems Programming, Geospatial Data, Sports Tech, Functional Programming

### 🌱 Currently exploring
- Zig 0.17: allocators, comptime, build.zig
- Zig → WASM in web workers for geospatial and file-parsing performance
- Claude Code skills for training analysis: the code computes the metrics, the model only interprets them
- Terrain overlays (runnability, daylight, exposure) from GPS traces and DEMs

### 📫 Find me
- [GitHub](https://github.com/totorototo)
- [LinkedIn](https://linkedin.com/in/totorototo)

---
*"If it involves a GPX file and a mountain, or low-level memory management, I'm probably interested."*
