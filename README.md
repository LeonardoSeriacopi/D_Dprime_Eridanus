
# D and D′ Operators in Void Analysis

This repository presents the first implementation and visualization of the operators **D** (causal derivative) and **D′** (conformal adjoint), designed to diagnose elastic transitions in cosmic voids based on radial density profiles.

## 🧠 Background

In underdense regions of the universe, traditional fluid approximations break down. This study introduces a dual-operator formalism where:

- **D(ρ)** captures directional, causally-constrained density changes.
- **D′(ρ)** accumulates conformal energy in regions of structural instability.

These operators are applied to a modeled profile inspired by the Eridanus Supervoid. The results reveal a transition at ~70 Mpc, interpreted as the point of **causal rigidity breakdown**.

## 🔬 Structure

- `paper/` – LaTeX source and compiled PDF of the academic note.
- `figures/` – All figures used in the manuscript (density profile, D, D′, and conformal integral).
- `scripts/` – Python scripts to compute each operator and generate the figures.
- `data/` – Sample CSV file with the synthetic radial density model.

## 📈 Results

Key findings include:

- Synchronization of D and D′ at the causal saturation radius.
- Visualization of elastic energy accumulation.
- Structural interpretation of void dynamics beyond metric expansion.

## 🧪 Requirements

- Python 3.10+
- `numpy`, `matplotlib`, `scipy`

## ▶️ Run Example

```bash
python scripts/operator_D.py
python scripts/operator_Dprime.py
```

## 📜 Citation

> Seriacopi, L. (2025). *Elastic Dynamics in Voids: Visualization of D and D′ Operators*. Preprint.

## 🤝 License

This project is licensed under the MIT License.
