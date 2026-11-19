# Action Forge

A prompt builder for AI action videos. Two modes, room to grow.

## What it does

**Swap Prompt** — one tap gives you the character-swap prompt:
"Change the character in the video to the new character in the image."

**Action Prompt** — a full builder that writes a polished, Seedance-style
fight-scene prompt from your choices:

- **Tool:** Seedance, Kling, Minimax, Grok, Flow, Hedra
- **Time:** 10 or 15 seconds
- **Aspect:** 9:16 or 16:9
- **Opponents:** 1 vs 5 or 1 vs 10
- **Day / Night**, **Rain / Dry**
- **Clothes:** Regular, James Bond Suit, Matrix, Tactical Black
- **Environments:** 5 to choose from
- **Fight styles:** Wing Chun, Muay Thai, MMA/Judo, Capoeira, Krav Maga
- **Powers:** No Special Powers, Superhuman Speed, Super Strength,
  Enhanced Reflexes, Superhuman Durability, Directional Gravity
- **Add-ons (Yes/No):** Person, Place, Thing, Vehicle, Environment —
  Yes drops `[Person]`, `[Place]`, `[Thing]`, `[Vehicle]`, `[ENV]` into the
  prompt; No leaves them out (`[No]` for Environment)
- **Camera moves, sound design, and a negative-prompt section** on every
  forged prompt

**Pro Presets** — one-tap director-grade prompts. First up: **KAI —
Directional Gravity** (10s, 16:9, 3x action speed, one continuous take,
no slow motion, invisible power, 8 timed beats, open ending).

**Extend** — continues the action from the final frame of the last prompt,
adding more timed beats each tap and updating the total runtime.

## How to use

Open `action-forge.html` in any modern browser — phone or desktop.
No build step, no server, no account. Your choices stay in your browser.

To put it on the web, enable GitHub Pages for this repo (Settings →
Pages → Deploy from branch) and share the link.

## Files

- `action-forge.html` — the whole app, self-contained in one file.
