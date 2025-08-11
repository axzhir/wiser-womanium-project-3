# Quantum Algorithm as a PDE Solver for Computational Fluid Dynamics (CFD)

## Project Name
Quantum Algorithm as a PDE Solver for Computational Fluid Dynamics (CFD)

## Team Name
FLÖ

## Team Members
- **Fanizza Tarum Tahir**: WISER Enrollment ID: gst-UV3r5RuEyWXEeON
- **James Austin Myer**: WISER Enrollment ID: gst-YPgLYog6eIo6JnE
- **Ramachandran Sekanipuram Srikanthan**: WISER Enrollment ID: gst-TnqxR0ZVOHep4gl


## Project Summary
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

<a href="https://docs.google.com/presentation/d/1IC_zrRhK3f3vYvj-IyBRz7qliAawMNREAn9lE4xF0Ic/edit?usp=sharing">Presentation</a>

## Repository Structure
```
quantum_cfd_solver_created_by_Fanizza_Tahir.ipynb - Implementation Notebook
quantum_cfd_solver_created_by_fanizza_tahir.py - Implementation file
optimization_history.csv - train results
summary_stats.csv - Optimized values and associated error.
Algorithm_Design_Brief_for_2025_Womanium___WISER_project_3__Quantum_PDE_solvers_for_CFD_with_Fanizza_Tahir___Ramachandran_Sekanipuram_Srikanth (3).pdf - Implementation Report
FLÖ.pdf - Presentation
```

## Installation and Setup
1. Clone the repository: `git clone https://github.com/axzhir/wiser-womanium-project-3.git`
3. Run Jupyter notebooks or Python scripts in the respective task directories.

## Usage Report
Algorithm_Design_Brief_for_2025_Womanium___WISER_project_3__Quantum_PDE_solvers_for_CFD_with_Fanizza_Tahir___Ramachandran_Sekanipuram_Srikanth.pdf  - Repo file which has the report.

## References

<OL>
<LI>Zhaoyuan Meng and Yue Yang. Quantum computing of fluid dynamics using the hydrodynamic Schrödinger equation. Phys. Rev. Research 5, 033182 https://doi.org/10.1103/PhysRevResearch.5.033182</LI>
<LI>Sreenivasan, Katepalli R. "Chandrasekhar's Fluid Dynamics." Annual Review of Fluid Mechanics 51 (2019): 1-24.</LI>
<LI>Barenghi, Carlo F., and Nick G. Parker. A primer on quantum fluids. Berlin: Springer, 2016.</LI>
<LI>La Mantia, M., and L. Skrbek. "Quantum, or classical turbulence?." EPL (Europhysics Letters) 105.4 (2014): 46002.</LI>
<LI>Skrbek, Ladislav, and Katepalli R. Sreenivasan. "How similar is quantum turbulence to classical turbulence?." Ten Chapters in Turbulence. Cambridge University Press, 2010. 405-4.</LI>
<LI>Wang, Xueying. "Quantum Turbulence, and How it is Related to Classical Turbulence." (2018).</LI>
<LI> https://youtu.be/2E-_VwyTeIU 

</OL>

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
