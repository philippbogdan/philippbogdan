# Philipp Bogdan

Curious across domains and build systems that just work.

Public work:

## Quantum computing

- [Carbon-Helix](https://github.com/philippbogdan/carbon-helix-ase): modelled 24.4x lower memory error per second than adaptive C4-Helix, using 92 of the 98 qubits on Quantinuum's Helios. **Est. value: [$0.1-10M](https://github.com/philippbogdan/carbon-helix-ase/blob/main/VALUE.md)**
- [Elevator codes](https://github.com/philippbogdan/elevator-codes-flagged-bit-flips): modelled 88 to about 59 physical qubits per logical qubit if 90% of bit flips are flagged with exact timing, gates included; gate flags remain unproven. **Est. value: [$0.1-5M](https://github.com/philippbogdan/elevator-codes-flagged-bit-flips/blob/main/VALUE.md)**

## Weather and climate computing

- [Sphere-on-a-torus](https://github.com/philippbogdan/sphere-on-a-torus): shallow-water solver advances a modelled 856x more simulated time per wall time than an unfiltered, polar-limited lat-lon grid on 64 Cerebras CS-3 systems; fixed 42-point neighbourhood, poles included. **Est. value: [$0.1-10M](https://github.com/philippbogdan/sphere-on-a-torus/blob/main/VALUE.md)**
- [Sphere grid errors](https://github.com/philippbogdan/sphere-grid-errors): simulated day-10 height error falls 3.94x when nudging flow near the grid's 4 special points, versus 2.52x for identical nudging around four other points; a diagnostic from one run at one resolution. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/sphere-grid-errors.md)**

## Materials

- [Rare-earth-free magnet alignment](https://github.com/philippbogdan/rare-earth-free-magnet-alignment): ceilings for 558 magnet and manufacturing combinations; 394 of 441 held-out published measurements fit, 13 clearly broke them. A textured parent caps printed MnAl(C) alignment at 0.61, against 0.50 for random grains. **Est. value: [$0.1-5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/rare-earth-free-magnet-alignment.md)**
- [Zero-bulk metamaterials](https://github.com/philippbogdan/zero-bulk-metamaterials): idealised layered designs retain 87 to 92% of the Hashin-Shtrikman shear-stiffness upper bound at zero bulk modulus; a literature search found no published three-dimensional construction this close at fixed solid fraction. **Est. value: [$0.1-3M](https://github.com/philippbogdan/philippbogdan/blob/main/values/zero-bulk-metamaterials.md)**

## Fusion energy

- [Tokamak Energy's RT-GSFit #103](https://github.com/tokamak-energy/rtgsfit/pull/103) (open): plasma equilibrium updates 5.4x faster, 1.1 ms to 0.2 ms median; flux agrees with the old solver to 1.5e-10. **Est. value: [$0.1-2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/rtgsfit-103.md)**
- [Proxima Fusion's VMEC++ #819](https://github.com/proximafusion/vmecpp/pull/819) (merged): cubic interpolation cuts vacuum-field error 16 to 100x versus linear, even with a quarter of the table points; at most 6.1% slower. **Est. value: [$0.05-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/vmecpp-819.md)**
- [Tokamak Energy's GSFit #127](https://github.com/tokamak-energy/gsfit/pull/127) (open): ST40 workflow 7.6x faster, 293 s to 39 s, at unchanged accuracy; 14 of 14 robustness cases finish, previously 12 of 14. **Est. value: [$0.02-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/gsfit-127.md)**

## Computer security

- [Optical inference leakage](https://github.com/philippbogdan/optical-inference-leakage): preliminary simulations show the client learns 5.4 to 6.5 bits per weight after one text at perplexity within 0.5% of digital BF16; for the 0.6B and 1.7B models, this is within about 28% of the one-way optical protocol's conditional minimum. **Est. value: [$0.02-2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/optical-inference-leakage.md)**

## Molecular modelling

- [Peptide dynamics from sequence](https://github.com/philippbogdan/peptide-dynamics-from-sequence): estimated 2,900x less GPU time per nanosecond than molecular dynamics, from sequence alone, with median free-energy error 0.26 to 0.39 kT versus 0.35 kT between two halves of the MD data. **Est. value: [$0.03-1M](https://github.com/philippbogdan/philippbogdan/blob/main/values/peptide-dynamics-from-sequence.md)**

## Analytical chemistry

- [MS2-indistinguishable isomers](https://github.com/philippbogdan/ms2-indistinguishable-isomers): 18.5% of 62,535 isomer comparisons in MassSpecGym have fragment spectra as similar as repeat measurements of the same molecule, under one similarity score. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/ms2-indistinguishable-isomers.md)**

## Mathematics

- [Cartogram bridge](https://github.com/philippbogdan/cartogram-bridge): links optimal-transport and diffusion cartograms by varying noise. Smooth planar tests give exponent 1.9994 ± 0.0002 for quadratic convergence to optimal transport as noise falls; the diffusion limit needs a clock set by the slowest heat-decay rate. **Est. value: [$0.01-0.5M](https://github.com/philippbogdan/philippbogdan/blob/main/values/cartogram-bridge.md)**
- [Optimal-transport cartogram](https://arxiv.org/abs/2609.14089): against diffusion on a matched benchmark, no rotation, 0 against 7 to 9 degrees median; lower directional distortion, 3.7 to 3.9 against 4.8 to 6.3, at transport cost within 0.3 to 0.4%. [Code](https://github.com/philippbogdan/historical-cartogram). arXiv.

## Fluid dynamics

- [One-step turbulence](https://github.com/philippbogdan/one-step-turbulence): estimated 5,360x lower cost for one-pass neural generators of turbulent flow fields at matched statistical precision against a solver, excluding training, yet flows lack its vortices and filaments; statistical agreement can hide missing structure. **Est. value: [$0.01-0.2M](https://github.com/philippbogdan/philippbogdan/blob/main/values/one-step-turbulence.md)**

## Robotics

- [EvoGym jumper loophole](https://github.com/philippbogdan/evogym-jumper-loophole): an estimated 97.2% of the best-found Evolution Gym jumping score comes from a simulator contact loophole. Closing it reduces the best-found score from 514.48 to 14.20; the floor was launching the robot. **Est. value: [$0.005-0.25M](https://github.com/philippbogdan/philippbogdan/blob/main/values/evogym-jumper-loophole.md)**

## Education

- [Learner history and calibration](https://openreview.net/forum?id=9uPqgPvXtJ): practice histories improved maths-question forecasts, Brier score 0.2148 to 0.2027 across 1,412 forecasts from 276 pupils. NeurIPS 2026 MATH-AI workshop paper, poster.
- [Atom Learning Model (ALM)](https://arxiv.org/abs/2608.21106): maths tutor with 1,934 checkable skills, used by 373 children in two English secondary schools; 26k+ marked attempts in seven weeks. arXiv.

## Audio

- [INSTRUMENTAL](https://arxiv.org/abs/2603.15905): recovers the 28 synth settings that recreate a sound from a song. [Code](https://github.com/philippbogdan/instrumental), [live demo](https://philippbogdan.com/instrumental). arXiv.

## Hackathons

- [AgentVerse](https://github.com/philippbogdan/Afterversed) (Amazon, Anthropic, Cisco), 1st place in the "Agents in the wild" track, Nov 2025; London Neurotech (Netholabs), Runner-Up, Netholabs NeuroAI track, Feb 2026, reverse-engineered a commercial fNIRS headset's Bluetooth overnight; Mozart AI Hack (OpenAI, ElevenLabs), 3rd place, Mar 2026; [Entrepreneur First Accessibility](https://github.com/philippbogdan/DotSpot), 3rd prize, Jan 2026; Cursor "Hands-Off", judge, 2026.
