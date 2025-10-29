# ThrustShield: Single-Pass Solar Thermal Oberth Architecture  
**Author:** Ilya Gazman  
**Date:** October 2025  
**Status:** Manuscript in submission to arXiv (astro-ph.IM / astro-ph.EP)

## Summary

ThrustShield is a mission architecture for launching a science probe out of the Solar System at extreme speed without using fusion, antimatter, laser sails, or multi-decade gravity assists.

The core idea is to perform a single, violent Oberth-style burn extremely close to the Sun, then discard almost the entire spacecraft. A tiny surviving probe continues outbound at interstellar precursor speeds.

This is a public timestamp of the concept and performance numbers.

## Mission Architecture (Baseline Tier)

- A ~1.5 tonne (wet mass) carrier stage is mostly liquid hydrogen propellant (~1.2 tonnes LH₂).
- The vehicle is inserted onto a Sun-diver trajectory with a perihelion of ~0.1 AU, where solar flux is ~100× higher than at Earth.
- The Sun-facing side is a **segmented high-temperature thermal shield**.  
  - This shield does two jobs at once:  
    1. It protects the rest of the spacecraft in its shadow.  
    2. It acts as a solar-thermal engine / heat exchanger.
- At perihelion (~0.1 AU), the shield is heated by direct solar flux and flash-heats hydrogen flowing through it.
- The stage performs a **seconds-long, very high-thrust burn** by expelling that superheated hydrogen.
- This burn provides on the order of **~20 km/s effective Δv**, but critically:
  - It happens when the spacecraft is already moving at ~100–150 km/s near the Sun.
  - Because of the Oberth effect, that ~20 km/s becomes enormously more valuable than it would be in deep space.

Immediately after the burn:
- The hot perihelion stage is **discarded**. ~99% of the original mass is thrown away.
- A hardened, autonomous **~20 kg science probe** survives in the shadowed region and separates cleanly.

## Resulting Performance

From that single perihelion event:

- The surviving ~20 kg probe exits the Solar System on a hyperbolic trajectory at roughly  
  **~80–110 km/s**, which is about  
  **~15–23 AU per year**.
- That means:
  - **~100 AU in ~5 years** after the burn (Baseline case).
  - Direct sampling of the outer heliosphere / heliopause / pristine very local interstellar medium on single-digit-year timescales, instead of decades.
- The discarded stage does not continue. It is sacrificial by design.

The probe:
- Carries a small ion propulsion package (Hall or gridded ion-style) with **~1–3 km/s** of its own Δv.
- Uses that Δv right after separation to clean up the outbound trajectory, target science geometries (heliopause crossing direction, Kuiper Belt / detached-object flybys), and set up communications geometry.
- Is intended to be on the order of **~20 kg total**, including:
  - comms + pointing,
  - power,
  - small plasma / field / dust / ENA / magnetometer payload,
  - the ion “afterburner.”

## Why This Is Different

1. **Single-pass, not multi-pass.**  
   ThrustShield does *one* perihelion dive and *one* burn.  
   It does **not** require storing liquid hydrogen for years while repeatedly diving to 0.1 AU over and over.

2. **Sacrificial stage.**  
   The big ~1.5 tonne vehicle is treated as an impulse stage that is allowed to die.  
   The science mission is carried by the ~20 kg “bullet” that survives.

3. **Oberth at perihelion.**  
   The ~20 km/s effective Δv is delivered while already moving ~100+ km/s near the Sun.  
   The Oberth effect multiplies the energy gain, so the final escape speed is 4–6× larger than the raw Δv.

4. **Near-term materials framing.**  
   The Baseline case uses ~0.1 AU perihelion (~100× solar constant) and seconds-scale survivability.  
   That keeps the dominant engineering problems in “how do we not melt for tens of seconds” and “how do we hold LH₂ for months,” not “how do we invent fusion.”

## Performance Tiers

The architecture naturally scales:

### Baseline ("Near-Term")
- Launch mass: ~1.5 t
- Perihelion: ~0.1 AU (~100× Earth solar flux)
- Effective Δv at perihelion: ~20 km/s (seconds-long burn)
- Escape speed of probe: ~80–110 km/s
- Cruise rate: ~15–23 AU/year
- Time to ~100 AU: ~5 years
- Time to ~1000 AU: ~50 years (order of magnitude)
- Science: heliopause boundary, pristine very local interstellar medium, outer heliosphere plasma and fields

### Aggressive
- Launch mass: ~3–3.5 t
- Perihelion: ~0.07 AU (~200× flux)
- Escape speed: ~110–150 km/s
- Cruise: ~23–31 AU/year
- ~100 AU in ~3–4 years
- ~1000 AU scale in ~30 years
- Science: same as Baseline, but faster; opens targeted high-speed Kuiper Belt / detached-object flybys

### Limit ("Icarus")
- Launch mass: ~6 t
- Perihelion: ~0.04 AU (~600× flux)
- Survive only for **seconds** at that flux
- Escape speed: >200 km/s
- Cruise: ~40–50+ AU/year
- ~100 AU in ~2 years
- ~1000 AU in ~20 years
- This is a physical limit case showing what happens if extreme perihelion thermal control and guidance close. It is not the first mission.

## What ThrustShield Enables

- A probe that reaches ~100 AU in a single-digit number of years, not multiple decades.
- Direct sampling of the heliopause, the outer heliosphere, and the pristine local interstellar medium.
- A practical path toward very-long-baseline solar gravitational lens science in a human timescale.
- An alternative to fusion drives, beamed sails, or multi-decade gravity assist chains.

## Status

- This concept is documented in a ~45 page manuscript with figures, mass breakdowns, perihelion flux levels, Oberth energy accounting, and mission timelines.
- The manuscript is being submitted to arXiv under astrophysics (Instrumentation and Methods for Astrophysics; Earth and Planetary Astrophysics as secondary).
- arXiv endorsement has been requested.

This repository exists to timestamp authorship and performance claims for the ThrustShield architecture.
