US$100,000 to US$2,000,000

Estimated total incremental value to fusion research over the next five years, in today's dollars. A central estimate is about US$500,000. This is a range of expected values; the realised benefit could still be zero.

The supplied [pull request](https://github.com/tokamak-energy/rtgsfit/pull/103) reports complete reconstruction updates falling from 1.104 ms to 0.205 ms on an Apple M4, with numerical differences around 1e-10 to 1e-9. The diff supports a substantive improvement: a separable Poisson solver, less redundant boundary work, skipped zero basis entries, validation tests and automatic fallback. I have not independently reproduced the timings. Production hardware and ST40 operating constants remain untested in the supplied evidence.

[RT-GSFit already controlled plasma shape on ST40 in November 2025](https://github.com/tokamak-energy/rtgsfit#1-introduction), with a design target below 1 ms. The opportunity is extra capacity for finer grids, additional iterations and other control calculations, potentially improving experimental usefulness and reducing future performance engineering. Fivefold faster reconstruction does not imply fivefold more experiments.

My calculation uses three distinct benefit streams. Probabilities include deployment and practical usefulness; they are unconditional judgements, so need not sum to 100%. Benefits are additional to the likely alternative without this PR, after allowing for validation, integration and maintenance costs.

| Benefit over five years | Chance of realisation | Net value if realised | Expected contribution |
| --- | --- | --- | --- |
| Future performance engineering avoided at ST40 | 50% to 80% | US$100,000 to US$400,000 | US$50,000 to US$320,000 |
| Additional useful experimental output at ST40, excluding that engineering time | 10% to 40% | US$500,000 to US$3 million | US$50,000 to US$1.2 million |
| Additional benefits from reuse at one or two other facilities | 5% to 25% | US$200,000 to US$2 million total | US$10,000 to US$500,000 |

The engineering allowance represents 0.5 to 2 years of specialist time released, using an assumed US$200,000 annual cost including overheads. For scale, [BLS reports median pay of US$140,300 for computer and information research scientists in May 2025](https://www.bls.gov/ooh/computer-and-information-technology/computer-and-information-research-scientists.htm). For experimental output, I assume fewer repeated experiments or more informative pulses worth roughly 1% to 6% of the [US$52 million, five-year ST40 upgrade programme](https://www.energy.gov/science/articles/doe-partners-uks-desnz-and-tokamak-energy-ltd-accelerate-fusion-energy-development). That budget provides a rough scale for valuing research capacity; it does not establish savings. Reuse assumes comparable benefits at a small number of sites. Summing the contributions gives US$110,000 to US$2.02 million, rounded above.

The maintainer's positive response and extensive numerical comparisons support adoption. However, operational timing, useful control improvements and outside uptake remain uncertain. [LIUQE already demonstrated updates of about 200 microseconds on a smaller grid in 2015](https://doi.org/10.1016/j.fusengdes.2014.09.019), limiting the advantage over alternatives. The estimate credits earlier useful research and avoided effort, without attributing future fusion electricity revenues to this optimisation.
