# Philipp Bogdan

Curious across domains and build systems that just work.

Public work:

## Quantum error correction

- [Carbon-Helix](https://github.com/philippbogdan/carbon-helix-ase): modelled 24.4x lower quantum memory error per logical qubit per second than adaptive C4-Helix on Quantinuum's Helios. **Est. value: [$0.1-10M](https://github.com/philippbogdan/carbon-helix-ase/blob/main/VALUE.md)**
- [Elevator codes](https://github.com/philippbogdan/elevator-codes-flagged-bit-flips): modelled 88 to about 59 physical qubits per logical qubit if 90% of bit flips have exact timing flags, gates included. **Est. value: [$0.1-5M](https://github.com/philippbogdan/elevator-codes-flagged-bit-flips/blob/main/VALUE.md)**

## Simulation and mapping

- [Sphere-on-a-torus](https://github.com/philippbogdan/sphere-on-a-torus): modelled 856x faster global shallow-water simulation on 64 Cerebras CS-3 systems than an unfiltered, polar-limited latitude-longitude grid. **Est. value: [$0.1-10M](https://github.com/philippbogdan/sphere-on-a-torus/blob/main/VALUE.md)**
- [Peptide dynamics from sequence](https://github.com/philippbogdan/peptide-dynamics-from-sequence): estimated 2,900x less GPU time per nanosecond than tetrapeptide molecular dynamics. **Est. value: [$0.03-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/peptide-dynamics-from-sequence.md)**
- [Cartogram bridge](https://github.com/philippbogdan/cartogram-bridge): links optimal-transport and diffusion population maps through noise, with diffusion time rescaled. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/cartogram-bridge.md)**

## Materials

- [Rare-earth-free magnet alignment](https://github.com/philippbogdan/rare-earth-free-magnet-alignment): grain alignment ceilings consistent with 394 of 441 held-out measurements. **Est. value: [$0.1-5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/rare-earth-free-magnet-alignment.md)**
- [Zero-bulk metamaterials](https://github.com/philippbogdan/zero-bulk-metamaterials): idealised layers compress uniformly without resistance, retaining 87 to 92% of the shear-stiffness bound at fixed solid content. **Est. value: [$0.1-3M](https://github.com/philippbogdan/philippbogdan/blob/main/values/zero-bulk-metamaterials.md)**

## Fusion software

- [Tokamak Energy's RT-GSFit #103](https://github.com/tokamak-energy/rtgsfit/pull/103) (open): plasma equilibrium updates 5.4x faster (median 1.1 to 0.2 ms). **Est. value: [$0.1-2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/rtgsfit-103.md)**
- [Proxima Fusion's VMEC++ #819](https://github.com/proximafusion/vmecpp/pull/819) (merged): 16 to 100x lower vacuum-field error than linear interpolation. **Est. value: [$0.05-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/vmecpp-819.md)**
- [Tokamak Energy's GSFit #127](https://github.com/tokamak-energy/gsfit/pull/127) (open): ST40 plasma reconstruction 7.6x faster (293 to 39 s), unchanged accuracy. **Est. value: [$0.02-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/gsfit-127.md)**

## Limits and failure modes

- [Optical inference leakage](https://github.com/philippbogdan/optical-inference-leakage): one-way optics leak 5.4 to 6.5 bits per model weight to the client after one text at near-digital quality (preliminary simulations). **Est. value: [$0.02-2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/optical-inference-leakage.md)**
- [Sphere grid errors](https://github.com/philippbogdan/sphere-grid-errors): simulated flow nudges near 4 special points cut day-10 height error 3.94x versus 2.52x near four others; diagnostic only. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/sphere-grid-errors.md)**
- [MS2-indistinguishable isomers](https://github.com/philippbogdan/ms2-indistinguishable-isomers): 18.5% of MassSpecGym isomer comparisons have spectra as similar as repeat measurements, under one score. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/ms2-indistinguishable-isomers.md)**
- [One-step turbulence](https://github.com/philippbogdan/one-step-turbulence): generated flows matched the solver's statistics at an estimated 5,360x lower cost (excluding training) but lacked its vortices. **Est. value: [$0.01-0.2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/one-step-turbulence.md)**
- [EvoGym jumper loophole](https://github.com/philippbogdan/evogym-jumper-loophole): simulator contact loophole supplied an estimated 97.2% of the best jumping score found. **Est. value: [$0.005-0.25M](https://github.com/philippbogdan/philippbogdan/blob/main/values/evogym-jumper-loophole.md)**

## Papers

- [Learner history and calibration](https://openreview.net/forum?id=9uPqgPvXtJ): practice histories improved forecasts of pupils' maths performance (Brier score 0.2148 to 0.2027). NeurIPS 2026 MATH-AI workshop paper, poster.
- [Atom Learning Model (ALM)](https://arxiv.org/abs/2608.21106): maths tutor; 373 pupils, 26k+ marked attempts in seven weeks. arXiv.
- [INSTRUMENTAL](https://arxiv.org/abs/2603.15905): recovers 28 synth settings to recreate a sound from a song. [Code](https://github.com/philippbogdan/instrumental), [live demo](https://philippbogdan.com/instrumental). arXiv.
- [Optimal-transport cartogram](https://arxiv.org/abs/2609.14089): population maps without rotation versus diffusion's 7 to 9 degrees median on matched tests. [Code](https://github.com/philippbogdan/historical-cartogram). arXiv.

## Hackathons

- [AgentVerse](https://github.com/philippbogdan/Afterversed), 1st place in the "Agents in the wild" track; London Neurotech, Runner-Up, Netholabs NeuroAI track; Mozart AI Hack, 3rd place; [Entrepreneur First Accessibility](https://github.com/philippbogdan/DotSpot), 3rd prize; Cursor "Hands-Off", judge.
