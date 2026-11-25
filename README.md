# Exact monogamy of steering and remote Wigner negativity for multimode Gaussian nodes

Numerical results and figures for the paper

> S. Chakrabarty, *Exact monogamy of steering and remote Wigner negativity for multimode Gaussian nodes*.

The notebook [`exact_monogamy_numerics.ipynb`](exact_monogamy_numerics.ipynb) reproduces every numerical value quoted in the paper and all seven figures, in the order in which they appear in the paper. It has been executed in full, and all outputs and figures are stored in it, so it can be read directly on GitHub without running anything. The figures are also provided as PDF files in [`figures/`](figures).

## Running the notebook

```
pip install -r requirements.txt
jupyter notebook exact_monogamy_numerics.ipynb
```

With `QUICK = False` (the setting used for the stored outputs) the notebook uses the grids of the paper and runs in about forty minutes, mostly in the semidefinite programs and the three-setting Bell scan. With `QUICK = True` it uses coarser grids and runs in about twenty minutes. The stored outputs were produced with Python 3.13, NumPy 2.5, SciPy 1.18, Matplotlib 3.11, mpmath 1.3, CVXPY 1.9 and SCS 3.3.

## Contents

| Notebook section | Paper |
|---|---|
| Figure 1 | Sec. 1 |
| The share of a neighbor: Propositions 1 and 3, Table 2, Figure 2, Proposition 4 | Sec. 3 |
| The share bound: Theorem 1, Proposition 5, tight-frame network (Lemma 4) | Sec. 4 |
| Exact count for steering: Theorem 2, Proposition 6 | Sec. 5 |
| Remote Wigner negativity: Theorem 5, rates and imperfections, Figure 3 | Sec. 6 |
| Arbitrary measurements: Theorem 7, Figure 4, three and four settings, certificates (Table 5), I3322, Figure 5 | Sec. 7, Appendix I |
| Teleportation and entanglement: Theorem 8, Proposition 9, Figures 6 and 7 | Sec. 8 |

## Citation

If you use this code, please cite the paper.

## License

MIT License, see [`LICENSE`](LICENSE).
