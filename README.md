# Quantum Algorithm as a PDE Solver for Computational Fluid Dynamics (CFD)

## Project Name
Quantum Algorithm as a PDE Solver for Computational Fluid Dynamics (CFD)

## Team Name
Flödinger

## Team Members
- **Fanizza Tarum Tahir**: WISER Enrollment ID: gst-UV3r5RuEyWXEeON
- **James Austin Myer**: WISER Enrollment ID: WP2025-YYYY (Placeholder)
- **Ramachandran Sekanipuram Srikanthan**: WISER Enrollment ID: gst-TnqxR0ZVOHep4gl


## Project Summary (500 Words)
We solve the Burgers' equation for a 1-dimensional shock tube (Burgers' 1-D) via discovery of optimal parameters (a, m) for a Schrödinger equation such that its Madelung transform is as close as possible to the desired Burgers' equation (with appropriate boundary & initial conditions).

**Tasks:**  
<OL>
<LI>Algorithm Design Brief - ≤ 5page PDF describing the chosen framework (QTN, HSE, or hybrid), mapping of PDE (1D Burgers’ Equation), gate decomposition, and resource estimates.</LI>

<LI>Prototype Code - Open‑source implementation runnable on a noiseless simulator and at least one real QPU backend (IBM, IonQ, Rigetti, Quantinuum, etc.).</LI>

<LI>Validation & Benchmark - Perform a quantitative comparison of the quantum solver against a classical solver reference for the 1-D viscous Burgers shock tube; report L₂-error, wall-clock time, and noisy-simulator metrics (e.g., effective error rates) for ≥ 3 time steps.</LI>

<LI>Resource & Noise Analysis - Table of qubits, two‑qubit‑gate depth, T‑count (if relevant), and mitigation strategy (e.g. ZNE, Clifford data regression).</LI>

<LI>Quantum Hardware Run - Execute at least one time step of the 1‑D Burgers benchmark on a physical QPU and present raw and error‑mitigated results, with runtime and noise diagnostics.</LI>

<LI>Scalability Study - Show how resources scale with grid size.</LI>

<LI>Algorithm Comparison - Discuss trade‑offs between QTN and HSE. </LI>
</OL>

## Project Presentation Deck
[Link to Presentation Deck] (It doesn't exist yet.)

## Repository Structure
```
quantum_cfd_solver_created_by_Fanizza_Tahir.ipynb - Implementation Notebook
quantum_cfd_solver_created_by_fanizza_tahir.py - Implementation file
optimization_history.csv - train results
summary_stats.csv - Optimized values and associated error.
Report.pdf - Implementation Report
```

## Installation and Setup
1. Clone the repository: `git clone https://github.com/axzhir/wiser-womanium-project-3.git`
3. Run Jupyter notebooks or Python scripts in the respective task directories.

## Usage Report
Report.pdf  - Repo file which has the report.

## References

<OL>
<LI>Zhaoyuan Meng and Yue Yang. Quantum computing of fluid dynamics using the hydrodynamic Schrödinger equation. Phys. Rev. Research 5, 033182 https://doi.org/10.1103/PhysRevResearch.5.033182</LI>
<LI>https://www.bqpsim.com/blogs/quantum-fluids-explain-turbulence-in-classical-fluids</LI>
</OL>

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
