# Penalty Kick — Week 14 Assignment

A 2D penalty-kick mini-game built in Unity as part of an introductory game
design course. This repository contains the module's starter project with my
modifications to the **S06_PenaltyKick** scene.

## What I changed

- Replaced the ball's main sprite with a soccer ball using the provided
  `Assets/Visuals/Soccer.png`, so the ball now renders as a soccer ball in the
  Penalty Kick scene.
- Produced a playable build of the `S06_PenaltyKick` scene and published it to
  itch.io.

## How to play

Aim and kick the ball toward the goal while the goalie tries to block it. The
score is shown at the top of the screen.

- **Mouse:** aim / interact with on-screen UI
- **Keyboard:** gameplay input (see in-game prompts)
- **ESC:** pause

## Project details

- **Engine:** Unity 6 LTS (6000.3.14f1)
- **Main scene:** `Assets/Scenes/S06_PenaltyKick.unity`
- **Input:** Unity Input System package (processed on Fixed Update)

## Build / itch.io

The playable build is hosted on itch.io — see the assignment submission for the
link.

## Repository notes

- `main` — stable branch
- `development` — working branch for changes
- `feature/*` — feature work branch(es)
- A Unity-specific `.gitignore` excludes non-project files (e.g. `Library/`,
  `Temp/`, `Build/`) so only `Assets/`, `Packages/`, and `ProjectSettings/` are
  tracked.
