# Reproduction Code for "Comprehensive Study on Heisenberg-limited Quantum Algorithms for Multiple Observables Estimation" (arXiv:2505.00698)

This repository contains the Jupyter notebooks and auxiliary scripts required to reproduce **Figures 3, 5, and 8** in the pre‑print **Comprehensive Study on Heisenberg-limited Quantum Algorithms for Multiple Observables Estimation** (arXiv:2505.00698).

## Repository layout

```text
.
├── notebooks/              # All Jupyter notebooks used to generate figures
│   ├── plot_figure3_2505.00698.ipynb
│   └── plot_figure5_2505.00698.ipynb
│   └── plot_figure8_2505.00698.ipynb
├── data/                   # Input datasets (kept small; larger data via Zenodo DOI)
├── requirements.txt        # Exact package versions for pip users
```

## Quick start ★

```bash
# 1. Clone repository
$ git clone https://github.com/koizumiyuki/2505.00698-reproduction
$ cd 2505.00698-reproduction

# 2. Install exact dependencies
$ pip install -r requirements.txt

# 3. Launch notebooks & run all cells
$ jupyter lab  # or: jupyter notebook
```

## Dependencies

| Package    | Tested version |
| ---------- | -------------- |
| Python     | 3.11.8         |
| numpy      | 1.26.4         |
| pandas     | 2.2.2          |
| scipy      | 1.15.3         |
| matplotlib | 3.8.4          |

Exact pins are in *requirements.txt*.

## Citation

If you use this code, please cite both the paper and this repository:

```bibtex
@article{koizumi2025comprehensive,
  title={Comprehensive Study on Heisenberg-limited Quantum Algorithms for Multiple Observables Estimation},
  author={Koizumi, Yuki and Wada, Kaito and Mizukami, Wataru and Yoshioka, Nobuyuki},
  journal={arXiv preprint arXiv:2505.00698},
  year={2025}
}
```

The Zenodo DOI badge (see *About* panel) will appear after the first GitHub release.

## License

Distributed under the MIT License.  See *LICENSE* for details.

## Contact

For questions, please open an issue or reach out to **Yuki Koizumi** (<koizumi‑yuki903@g.ecc.u‑tokyo.ac.jp>).
