<p align="center"><img src="shell_midsurface.png#gh-light-mode-only" width="600"\></p>
<p align="center"><img src="shell_midsurface_dark.png#gh-dark-mode-only" width="600"\></p>

# Physics-Informed Neural Networks for Shell Structures

We introduce a framework to simulate the mechanical small-strain response of shell structures via PINNs as described in ['Physics-Informed Neural Networks for shell structures'](https://doi.org/10.1016/j.euromechsol.2022.104849).

To run the studies, simply clone this repository via
```
git clone https://github.com/jhbastek/PhysicsInformedShellStructures.git
```
and run `main.py` with the indicated study. For the strong form, simply run `main_strong.py`. You may choose your own setting by providing the corresponding values in `params.py`. To consider different surfaces, simply add the corresponding charts in similar style as the given charts to `src.geometry.py`. 

For further information, please first refer to the [publication](https://doi.org/10.1016/j.euromechsol.2022.104849), or reach out to [Jan-Hendrik Bastek](mailto:jbastek@ethz.ch).

## Requirements

The requirements are fairly basic. Though we do not foresee any compatibility issues, we provide each version that was verified to work correctly.

- Python (tested on version 3.7.1)
- Python packages:
  - Pytorch (1.11.0 with CUDA 11.7)
  - NumPy (1.19.2)
  - SciPy (1.5.2)
  - Matplotlib (3.3.2, only required for plotting)

## Citation

If this code is useful for your research, please cite our [publication](https://doi.org/10.1016/j.euromechsol.2022.104849).
```bibtex
@article{Bastek2023,
author = {Bastek, Jan-Hendrik and Kochmann, Dennis M.},
doi = {10.1016/j.euromechsol.2022.104849},
issn = {09977538},
journal = {European Journal of Mechanics - A/Solids},
pages = {104849},
title = {{Physics-Informed Neural Networks for shell structures}},
url = {https://linkinghub.elsevier.com/retrieve/pii/S0997753822002790},
volume = {97},
year = {2023}
}
```
