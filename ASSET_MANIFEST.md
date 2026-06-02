# Elemental Ring Fights Asset Manifest

Future Codex: check this file before asking what assets exist or what still needs to be added.

## Provided Assets Currently In Project

### `src/assets/ELogos`
- `Water-Logo.png`
- `Toxic-Logo.png`
- `Plant-Logo.png`

### `src/assets/ESkins`
- `Water-Normal.png`
- `Water-Hurt.png`
- `Toxic-Normal.png`
- `Toxic-Hurt.png`
- `Plant-Normal.png`
- `Plant-Hurt.png`

### `src/assets/EAttack`
- `Syringe.png`
- `Flytrap-Idle.png`
- `Flytrap-Attack1.png`
- `Flytrap-Attack2.png`
- `Flytrap-Attack3.png`

### `src/assets/ESFX`
- `Honk.mp3`

### Empty Or Not Yet Provided
- `src/assets/EParticles`
- `src/assets/Misc`

## Assets Still Wanted

### `src/assets/ELogos`
- Random logo
- Modifier logo

### `src/assets/EParticles`
- Water pass-through or splash effect
- Toxin hit effect
- Plant grow effect
- Flytrap snap effect
- Ball explosion effect

### `src/assets/ESFX`
- Syringe throw
- Syringe hit/inject
- Flytrap grow
- Flytrap snap
- Ball hit
- Wall hit
- Power hit
- Ball explosion
- Button click
- Countdown tick
- Fight start

### `src/assets/Misc`
- Duck image
- Optional title logo
- Optional custom pedestal art
- Optional arena backgrounds

## Current Code Asset Usage

- Character select logos use the provided `ELogos` images.
- Pedestal balls and battle balls use the provided `ESkins/*-Normal.png` images.
- Hurt skin files are available but not yet conditionally swapped during damage frames.
- Syringes use `EAttack/Syringe.png`.
- Flytraps use `Flytrap-Idle.png` and attack frames.
- Duck button uses `ESFX/Honk.mp3`; no duck image exists yet.

