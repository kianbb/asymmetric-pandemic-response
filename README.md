# Faster Uptake, Slower Let-Down: Asymmetric Community Responses to Changing Risks During a Pandemic

This repository contains the code and data accompanying the paper:

> **Babaei Shalmani, K., DiGennaro, C., Rahmandad, H., & Ghaffarzadegan, N. (2026).** Faster Uptake, Slower Let-Down: Asymmetric Community Responses to Changing Risks During a Pandemic. *Risk Analysis*. https://doi.org/10.1111/risa.70228

### Authors and affiliations

- **Kian Babaei Shalmani** — Department of Industrial and Systems Engineering, Virginia Tech, USA
- **Catherine DiGennaro** — MIT Sloan School of Management, USA
- **Hazhir Rahmandad** — MIT Sloan School of Management, USA
- **Navid Ghaffarzadegan** (corresponding author) — Department of Industrial and Systems Engineering, Virginia Tech, USA

A precursor version appeared as a peer-reviewed conference paper at the 2024 International System Dynamics Conference (Bergen, Norway): *"Debiasing Human Response Estimations in Dynamic Models: Exploring the Significance of Delay Structure and Asymmetries"* — Honorable Mention, Dana Meadows Award.

---

## Overview

We study how communities adjust their protective behaviour as pandemic risk changes. Using synthetic experiments and state-level empirical analysis across all 50 U.S. states and Washington, D.C., we show that community responses to changing risk are asymmetric: protective behaviours are adopted faster than they are relaxed. Ignoring this asymmetry biases parameter estimates and forecasts in behaviourally responsive epidemic models, with implications for the design of vaccination and non-pharmaceutical interventions.

## Repository structure

├── Data/                       # Real-world and synthetic data
├── Models/Python/              # Jupyter notebooks
│   ├── 100_simulation.ipynb    # Generates synthetic data for simulation studies
│   ├── final_edits.ipynb       # Extended analysis and plotting on a synthetic case
│   ├── empirical_study.ipynb   # State-level empirical analysis and mobility plots
│   └── ARDL.ipynb              # Comparison with ARDL-based estimation
├── LICENSE
└── README.md

## Reproduction

**Requirements:** Python 3.x with NumPy, pandas, matplotlib, statsmodels, SciPy; Jupyter notebook or JupyterLab.

**Steps:**
1. Clone this repository:
```bash
   git clone https://github.com/kianbb/asymmetric-pandemic-response.git
   cd asymmetric-pandemic-response
```
2. Open the notebooks in `Models/Python/` and run in order. Synthetic data can be regenerated from `100_simulation.ipynb`; empirical analyses use the files in `Data/`.

## Citation

```bibtex
@article{babaei_shalmani_2026_asymmetric,
  author  = {Babaei Shalmani, Kian and DiGennaro, Catherine and Rahmandad, Hazhir and Ghaffarzadegan, Navid},
  title   = {Faster Uptake, Slower Let-Down: Asymmetric Community Responses to Changing Risks During a Pandemic},
  journal = {Risk Analysis},
  year    = {2026},
  doi     = {10.1111/risa.70228}
}
```

## License

MIT — see `LICENSE`.

## Contact

For questions, please open an issue in this repository, or contact:
- Kian Babaei Shalmani — kianb@vt.edu
- Navid Ghaffarzadegan (corresponding author) — navidg@vt.edu
