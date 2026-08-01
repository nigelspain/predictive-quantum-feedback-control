# Active Governance Framework

This repository contains the experimental code and circuits for the paper: *"Real-Time Predictive Classical-Quantum Feedback Control on a Superconducting Quantum Processor."*

## Reproducibility
To reproduce the empirical hardware validation results:
1. **Environment:** Install the required dependencies via `pip install -r requirements.txt`.
2. **Circuit Execution:** Run the files in `/circuits` on the IBM Kingston backend using the provided Qiskit runtime configuration.
3. **VAE Training:** Use `/notebooks/train_vae.ipynb` to reconstruct the VAE-FFN controller weights.
4. **Data Verification:** The noise profiles in `/data` mirror the Kingston backend calibration snapshot (2026-07-12).

## Citation
If you utilize this framework in your research, please cite the paper and the archival DOI:https://doi.org/10.5281/zenodo.21610328
