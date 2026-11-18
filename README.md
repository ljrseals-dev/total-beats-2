# TOTAL BEATS 2

<p align="center">
  <img src="assets/total-beats-2-cover.svg" alt="TOTAL BEATS 2 — Melting Blue // Neural Tide 2030 book cover" width="420">
</p>

<p align="center"><strong>From Working Prototype to Living System</strong></p>

<p align="center"><em>Melting Blue // Neural Tide 2030 — Expanded Edition</em></p>

**Author:** Lewis James Seals Jr.  
**Publisher:** Lewis Seals Publishing L3C  
**Manuscript version:** 2.0  
**Edition:** First edition of the expanded text; second edition of the TOTAL BEATS project  
**Structure:** Eight parts, twenty-eight chapters, eight appendices  
**Length:** 142 pages

## About the book

*TOTAL BEATS 2* documents the completion pass for a generative music system that began as a single text file containing two engines: a rule-based soundscape generator and a small Transformer learning to compose while audio continued to play.

This is not a reboot. The book keeps the original engines, creative rule, and hum fix, then addresses the harder work of making the product survive: decomposed rewards, anti-collapse controls, bounded memory, release-quality rendering, expanded tests, versioned checkpoints, and repeatable listening evaluation.

The book's organizing principle is practical and explicit: repair first, refactor second. Composition is separated from synthesis; model size remains CPU-first; memory is bounded; and listening is part of release evaluation.

## Excerpts from the book

> “A feature that cannot be tested or heard is not finished.”

The preface makes this the standard for the chapters that follow: every claimed capability is paired with a test and a listening note. Experimental, repaired, extended, and planned work are identified rather than blurred together.

> “V2 is about making something that survives being left alone.”

The second edition shifts the engineering problem from merely avoiding crashes to long-session stability. Memory limits, restraint, rollback, and quiet operation become design requirements.

> “The pipeline is the project’s honesty made operational.”

The book treats repeatable checks as evidence, not ceremony. Its test and soak-test approach watches memory, reward behavior, rollbacks, output level, and checkpoint growth over time.

> “Whether it sounds like the sea is still a decision you make by listening.”

The closing chapter leaves the final musical judgment where it belongs: with the listener. Passing tests can establish that the system behaves; listening determines whether the result works as music.

## What the expanded edition covers

- **Continuity and scope:** preserve source lineage and distinguish repairs from extensions.
- **Learning and anti-collapse:** decompose the reward and keep the model from settling into repetitive safe output.
- **Memory and checkpoints:** bound retained experience and make saved state inspectable and migratable.
- **Sound and rendering:** separate composition from synthesis and bring offline output toward release quality.
- **Safety and long-run behavior:** define limits, monitor drift, and test the system over extended sessions.
- **Productization:** provide a CLI, readable configuration profiles, packaging, and reproducible workflows.
- **Evaluation:** use a test matrix, soak tests, and a repeatable listening protocol.

## A listening-first engineering project

The book's listening protocol includes blind A/B comparisons using different seeds, a thirty-minute fatigue test, repetition checks against novelty, a low-frequency spectral check, and a place test: does the sound feel like a place?

Its claims are deliberately bounded. The colophon says the described system can plausibly run for a day without losing itself, but does not yet claim a week of unattended operation. The roadmap is presented as unfinished work, not as a marketing promise.

## How to read it

- **As a build guide:** start at Chapter 5 and follow the milestones in order.
- **As a design argument:** read Parts I and III together to understand the small-model, decomposed-reward, bounded-memory approach.
- **As a reference:** use the appendices for schemas, the test matrix, reward specification, checkpoint migration, and listening protocol.

## Book

The complete expanded PDF is intended to be included in this repository as:

`TOTAL_BEATS_2_Lewis_James_Seals_Jr.pdf`

## License and attribution

The colophon identifies the project license as **MIT** and records the copyright notice for Lewis Seals Publishing L3C.

Copyright © 2026 Lewis Seals Publishing L3C. Written by Lewis James Seals Jr.

Preserve the copyright and license notice when redistributing the project. See the repository's license file when it is added.

---

*The cover artwork currently embedded above is a vector reconstruction for the README presentation, not the original uploaded PNG. The original cover image and complete PDF are not yet committed in this repository.*
