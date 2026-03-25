+++
title = "IFCS Settings"
description = "Default settings for IFCS"
weight = 1
sort_by = "weight"
[extra]
+++

{% badge_secondary() %}
  Updated 4.7.0
{% end %}

Okay, so here’s the reality. The Intelligent Flight Control System (IFCS) is basically a safety layer sitting between you and the ship, constantly trying to “help” by smoothing inputs, limiting force, and preventing mistakes. That sounds nice until you realize every one of those protections is also stealing performance from you. In PvP and racing, that cost gets you killed.

This setup is about giving you full authority over your ship so you can actually push it to its limits. You fly the ship, not the other way around.



| Setting Name | Recommended Value | Optional |
| :------- | :------: | :-------: |
| Defaults - Flight - Automatic Slowdown On     | No  | ❌ |
| Defaults - Flight - Decoupled On              | No  | ❌ |
| Defaults - Flight - ESP On                    | Yes | ❌ |
| Defaults - Flight - Gravity Compensation On   | No  | ❌ |
| Defaults - Flight - Wind Compensation On      | No  | ❌ |
| Defaults - Flight - G-Safe On                 | No  | ❌ |
| Defaults - Flight - Boost Disables G-Safe     | Yes | ✔  |
| Defaults - Flight - Cruise Mode On            | No  | ❌ |
| Defaults - Flight - Space Brake Enables Boost | No  | ✔  |
| Defaults - Flight - Speed Limiter On          | No  | ❌ |
| Defaults - Flight - Proximity Assist On       | No  | ❌ |


## Setting Breakdown

What we are doing here is removing anything that interferes with direct control. If you input something, the ship should do exactly that, immediately, without second guessing you. The more the system tries to correct or protect you, the less precise and predictable your ship becomes. High level pilots are not relying on safety systems, they are relying on control, awareness, and discipline.

### Automatic Slowdown — OFF (Non-Negotiable)
- Limits you to 30 m/s with landing gear down.
- Accidentally triggering this in a fight will get you killed.
- Also prevents fast takeoffs and makes dropship piloting ineffective.

### Decoupled Mode — ON (Non-Negotiable)
- Required for high-level flight control.
- Critical for both dogfighting and racing.
- If you are not flying decoupled, you are limiting your ceiling.

### ESP — ON (Non-Negotiable)
- Aim assist system.
- The game is balanced around this being enabled.
- Without it, you are at a direct disadvantage regardless of input method.

### Gravity Compensation — TOGGLE (Default OFF)
- When ON: simulates space-like flight in atmosphere.
- When OFF: allows you to use gravity for acceleration and braking.
- Recommendation: keep OFF, but bind to a toggle for edge cases.

### Wind Compensation — TOGGLE (Default OFF)
- When ON: uses thrust to compensate for wind forces.
- When OFF: allows you to have full control of your thrusters.
- Recommendation: keep OFF, but bind to a toggle for edge cases.

### G-Safe — OFF (Non-Negotiable)
- Prevents blackout/redout by limiting G-forces.
- This also limits your ability to maneuver aggressively.
- You must be able to push both your ship and your body to the limit.

### Boost Disabled by G-Safe — Irrelevant
- G-Safe should already be OFF, making this setting meaningless.

### Cruise Mode — OFF
- Only functions in coupled mode.
- No real use in PvP or racing.
- Accidental activation can disrupt control.

### Space Brake Engages Boost — OFF
- Prevents accidental boost usage when braking.
- Boost is one of your most valuable resources—do not waste it.

### Speed Limiter — OFF (Non-Negotiable)
- Artificially caps your speed.

There is no scenario in competitive flight where this is preferable to manual control.

### Proximity Assist — OFF (Non-Negotiable)
- Reduces maneuverability near objects.
- This will cut your performance in close-range fights and around terrain.
- Exactly where control matters most.