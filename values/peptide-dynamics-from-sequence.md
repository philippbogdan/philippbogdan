US$30,000 to US$1,000,000

*This is a very rough estimate produced by GPT 6 Astra (max) for reference.*

My estimate of the expected incremental benefit to the molecular simulation and peptide research industry over the next five years, in 2026 US dollars. A central judgement is about **US$200,000**. This is a range for expected value; the realised benefit could be close to zero.

The useful contribution is a model that generates approximate peptide dynamics from sequence, with trained weights, saved evaluation paths and reusable analysis code. The supplied results imply about **1,200 times less GPU time at a matched passage-time error measure**, making inexpensive exploratory calculations plausible. However, only 13 of 30 test tetrapeptides were evaluated, those sequences also influenced model selection, and the slowest relaxation is at least twice too fast in five or six peptides per sample. Evidence covers four-residue peptides in implicit solvent at 310 K. Longer peptides and explicit water remain unvalidated. The timing estimate uses a sibling model and excludes training and analysis. These limitations substantially reduce the probability of industrial gains. [Repository evidence](https://github.com/philippbogdan/peptide-dynamics-from-sequence/blob/main/docs/evidence.md)

I use two additive routes to value. Probabilities, adoption and attribution are my assumptions, not measured commercial demand. Benefits count research labour and computation saved after integration, validation and further development costs.

| Route | Chance of realising gains | Benefit attributable to this work if realised | Expected contribution |
| --- | --- | --- | --- |
| Reuse of the model and evaluation tools in peptide research | 25% to 60% | US$100,000 to US$1 million | US$25,000 to US$600,000 |
| Contribution to a validated method for larger systems, beyond those reuse savings | 0.5% to 3% | US$1 million to US$10 million | US$5,000 to US$300,000 |

The first row assumes 10 to 50 teams each save a net half to one researcher-month, valued at US$20,000 per month including employer overheads. That cost assumption is roughly twice the monthly salary implied by the US Bureau of Labor Statistics' **US$127,410 median annual wage** for biochemists and biophysicists in May 2025. [BLS](https://www.bls.gov/ooh/life-physical-and-social-science/biochemists-and-biophysicists.htm)

Compute savings support this estimate but are modest per peptide. The repository's MD baseline uses about six T4 GPU-hours per microsecond. At Google's listed Iowa T4 rate of **US$0.35 per hour**, that is about **US$2.10**, excluding host and storage charges. Avoiding 10,000 such runs would save about US$21,000 in GPU charges, provided the approximation were adequate. [Timing records](https://github.com/philippbogdan/peptide-dynamics-from-sequence/blob/main/results/value_summary.json), [Google Cloud pricing](https://cloud.google.com/products/compute/gpus-pricing)

The second row assumes 100 to 500 additional future projects save US$100,000 to US$200,000 each, with only 10% of that benefit credited to this contribution. Such gains require substantial advances in accuracy and scope. The work builds on the public [ManyPeptidesMD dataset](https://huggingface.co/datasets/transferable-samplers/many-peptides-md), while [other transferable dynamics methods](https://arxiv.org/abs/2510.07589) already address this opportunity. That limits both attribution and the chance of a distinctive industrial contribution.

Adding the rows gives US$30,000 to US$900,000, rounded to the headline range. The central case is 40% × US$300,000 plus 1.5% × US$5 million, or US$195,000. I inspected the code and checked the saved-result arithmetic; I did not independently rerun the simulations.
