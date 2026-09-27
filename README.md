<div align="center">
  <h1>Snake Game — Product Concept</h1>
  <p>An early interaction-design concept, retained with transparent project status</p>
  <img src="https://img.shields.io/badge/status-archived-6B7280?style=flat-square" alt="Status: archived" />
  <img src="https://img.shields.io/badge/type-design%20concept-F59E0B?style=flat-square" alt="Design concept" />
</div>

> [!NOTE]
> **Archived project concept.** This repository is preserved as a short project record. The original playable source is not present in this repository, so it is not presented as a current portfolio project.

## Product concept

🐍 A planned Gen-Z styled Snake Game: responsive HTML/CSS/JS gameplay with start/stop controls, levels, increasing speed, dark/light modes, colourful visuals, and arrow-key controls.

## Intended interaction flow

~~~mermaid
flowchart LR
    A[Start screen] --> B[Choose mode or level]
    B --> C[Arrow-key movement]
    C --> D[Score and speed update]
    D --> E{Collision?}
    E -- No --> C
    E -- Yes --> F[Game-over screen]
~~~

## Scope record

| Planned capability | Status in this repository |
| --- | --- |
| Responsive browser game | Planned only; no implementation committed. |
| Start/stop controls and levels | Planned only; no implementation committed. |
| Dark/light visual modes | Planned only; no implementation committed. |
| Arrow-key controls and increasing speed | Planned only; no implementation committed. |

This diagram documents the **planned product flow**, not a live or playable implementation.

## Why it remains public

This repository documents an early product idea and the intended interaction design. It is **not a playable demo** because the source was never committed here; keeping that distinction visible is more useful than presenting an incomplete repository as finished work.

## Current direction

The active profile prioritises agentic-AI and full-stack projects. This concept stays archived as part of the learning timeline.
