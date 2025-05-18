# Selective Mechanical Pet Door for Robotic Mower

This repository contains design files for a fully mechanical, selective passage for robotic lawnmowers. It allows the mower to enter/exit a fenced area while preventing pets (e.g., medium-sized dogs) from escaping.

## Concept Overview

The system is a **bidirectional, self-latching "cat-flap" style door**. It's entirely mechanical, requiring no electricity.

The robot activates a trigger to unlock only the end of the door it's approaching. As the robot pushes this end, the entire door swings. The opposite, initially locked end of the door is passively forced open by the door's motion and then re-latches.

## Key Features

*   **Fully Mechanical:** No electronics or power needed.
*   **Bidirectional:** Allows robot entry and exit.
*   **Selective:** Designed for robot activation, difficult for pets to operate.
*   **Self-Latching:** Door automatically re-locks on both ends after passage.

## Operating Principle

1.  **Activation:** Robot pushes a **trigger**.
2.  **Local Unlock:** Trigger disengages **locking levers** (red in CAD & schematic) on the approached end of the **swinging door** (yellow in CAD).
3.  **Door Swing & Passive Unlock:** Robot pushes the unlocked door end. The door swings. The opposite the same.
4.  **Passage & Re-lock:** Robot passes. Door swings closed. Both ends automatically re-lock via springs on the locking levers.

## Design Notes

*   The CAD model may illustrate the system for clarity;
*   Dimensions are indicative and should be adapted.
*   Prototyping is crucial for testing mechanics, spring forces, and latching.
*   Material selection should consider durability and weather resistance.
