# Open-Source Datasets for CAE Engineers

This document provides a curated list of open-source datasets to enhance your skills in simulation, optimization, and design within the field of Computer-Aided Engineering (CAE).

---

## Automotive Aerodynamics

1. **AhmedML**
   - **Description:** A dataset comprising high-fidelity Computational Fluid Dynamics (CFD) simulations of 500 geometric variations of the Ahmed car body. This dataset is designed to aid in the development and testing of machine learning surrogate models for external automotive aerodynamics.
   - **Access Link:** [AhmedML Dataset](https://neilashton.github.io/caemldatasets/ahmedml/)

2. **DrivAerML**
   - **Description:** An open-source dataset containing high-fidelity CFD simulations of various DrivAer model configurations. It is intended to support machine learning applications in automotive aerodynamics.
   - **Access Link:** [DrivAerML Dataset](https://neilashton.github.io/caemldatasets/drivaerml/)

3. **WindsorML**
   - **Description:** This dataset offers 355 geometric variants of the Windsor body, each accompanied by high-fidelity CFD simulation data. It serves as a resource for developing machine learning models focused on external automotive aerodynamics.
   - **Access Link:** [WindsorML Dataset](https://neilashton.github.io/caemldatasets/windsorml/)

---

## Structural Analysis & Mechanical Design

4. **DeepJEB (Jet Engine Bracket Dataset)**
   - **Description:** A synthetic dataset comprising over 2,000 jet engine bracket designs, each with corresponding structural analysis data. Generated using deep learning models and automated simulation pipelines, it is ideal for training surrogate models in structural engineering.
   - **Access Link:** [DeepJEB Dataset](https://www.narnia.ai/dataset)

5. **SimJEB**
   - **Description:** This dataset includes 381 jet engine bracket designs analyzed under multiple load cases, providing a foundation for finite element analysis (FEA) workflows.
   - **Access Link:** [SimJEB Dataset](https://simjeb.github.io/)

6. **FRAMED**
   - **Description:** A collection of 4,500 bicycle frame designs, each with data on stress, deflection, and safety factors. This dataset is useful for studies in structural integrity and optimization.
   - **Access Link:** [FRAMED Dataset](https://decode.mit.edu/projects/framed/)

7. **OSU-Honda CarHoods10k**
   - **Description:** Featuring over 10,000 car hood frame designs in STL format, this dataset includes performance metrics suitable for developing surrogate models and structural optimization studies.
   - **Access Link:** [OSU-Honda CarHoods10k Dataset](https://datadryad.org/stash/dataset/doi:10.5061/dryad.2fqz612pt)
  
8. **SimuStruct (Plate with Holes Dataset)**  
   - **Description**: A dataset containing 2D plate structures with various hole configurations, their corresponding meshes, and finite element analysis (FEA) results under different loading conditions. Generated using the FEniCS solver.  
   - **Applications**: AI-assisted meshing, stress prediction, surrogate modeling for structural analysis.  
   - **Access Link**: [SimuStruct Dataset](https://inductiva.ai/blog/article/simustruct-dataset)
  
9. **FEA Stress Analysis Images (PyCalculix)**  
   - **Description**: A dataset of over 270,000 simulated stress-field images of 2D mechanical structures under fixed base and gravity loading, computed using finite element analysis (PyCalculix).  
   - **Applications**: Stress field prediction, ML-driven CAE analysis, anomaly detection in FEA.  
   - **Link**: [FEA Stress Images Dataset](https://data.mendeley.com/datasets/wzbzznk8z3/1)
  
10. **Composite Turbine Blade FEA & Testing**  
   - **Description**: Contains real-world physical test data and FEA simulation results for a 13-meter composite wind turbine blade, including dynamic response and static load tests.  
   - **Applications**: Validation of AI-driven FEA models, material behavior prediction, digital twin development.  
   - **Link**: [Composite Blade Dataset](https://www.seanoe.org/data/00694/80564/)

11. **Kaggle FEM Simulation Dataset**  
   - **Description**: A collection of about 6,000 FEM simulations from a mechanical design optimization study, including input parameters and resulting stress or displacement fields.  
   - **Applications**: Machine learning models for structural optimization, surrogate modeling.  
   - **Link**: [Kaggle FEM Dataset](https://www.kaggle.com/datasets/daalgi/fem-simulations/data)

---

## Computational Fluid Dynamics (CFD)  

12. **Johns Hopkins Turbulence Database (JHTDB)**  
   - **Description**: A multi-terabyte dataset containing Direct Numerical Simulation (DNS) turbulence data, including isotropic turbulence and turbulent channel flows.  
   - **Applications**: AI-driven turbulence modeling, flow field prediction, super-resolution reconstruction.  
   - **Link**: [JHTDB](http://turbulence.pha.jhu.edu/)

13. **Airfoil Shape CFD Dataset (OEDI)**  
   - **Description**: A dataset containing flow simulations for 1,830 different airfoil shapes, providing lift, drag, and pressure distributions computed via a RANS solver across various angles of attack.  
   - **Applications**: AI-based aerodynamic performance prediction, shape optimization, surrogate modeling.  
   - **Link**: [Airfoil CFD Dataset](https://data.openei.org/submissions/5970)

14. **LLNL Atmospheric Dispersion CFD Dataset**  
   - **Description**: A dataset of 16,000 CFD simulations modeling pollutant dispersion in the atmosphere under different wind speeds and release locations.  
   - **Applications**: AI-based pollutant dispersion modeling, environmental impact prediction.  
   - **Link**: [LLNL CFD Dataset](https://data-science.llnl.gov/open-data-initiative)

15. **DrivAerNet++ Automotive Aerodynamics Dataset**  
   - **Description**: Contains 8,000 variations of the DrivAer car model with high-fidelity CFD results, including flow fields and aerodynamic performance metrics.  
   - **Applications**: AI-based aerodynamic shape optimization, drag reduction studies.  
   - **Link**: [DrivAerNet++](https://github.com/Mohamedelrefaie/DrivAerNet)

16. **Fluid Cube Dataset (0.1)**
   - **Description**: Contains 100 unique fluid simulations within a unit cube using Smoothed Particle Hydrodynamics (SPH) to capture varied fluid behavior.
   - **Applications**: Fluid dynamics research, ML-based fluid flow prediction, and dynamic metrics analysis. 
   - **Link**: [Fluid Cube Dataset](https://inductiva.ai/blog/article/fluid-cube-dataset)

---

## Thermal Simulation  

17. **Conduction Heat Transfer Dataset**  
   - **Description**: A dataset of thermal simulations focused on heat conduction, formatted as temperature field images for deep learning applications.  
   - **Applications**: AI-driven temperature prediction, physics-informed neural networks.  
   - **Link**: [Heat Transfer Dataset](https://data.mendeley.com/datasets/rw9yk3c559/1)

---

## Electromagnetics Simulation  

18. **Synthetic Ground-Penetrating Radar (GPR) Dataset**  
   - **Description**: A dataset generated using the gprMax FDTD simulator, containing synthetic GPR B-scan signals for different subsurface scenarios.  
   - **Applications**: AI-based signal interpretation for buried object detection, geophysical studies.  
   - **Link**: [GPR Dataset](https://www.kaggle.com/competitions/gpr-data-processing)

19. **Electromagnetic Interference (EMI) Signals Dataset**  
   - **Description**: Contains labeled electromagnetic interference signal traces vs. normal signals, useful for EMI detection and mitigation studies.  
   - **Applications**: AI-based EMI detection, signal classification, real-time monitoring of electrical systems.  
   - **Link**: [EMI Signals Dataset](https://www.kaggle.com/datasets/ucimachinelearning/electromagnetic-interference-dataset)

---

## Ship Design

20. **Ship-D**
   - **Description:** A comprehensive dataset containing over 30,000 parametric ship hull designs, each accompanied by detailed performance metrics. It is tailored for hydrodynamic optimization tasks.
   - **Access Link:** [Ship-D Dataset](https://github.com/noahbagz/ShipD)

---

## CAD Model Generation

21. **DeepCAD**
   - **Description:** This extensive dataset comprises over 179,000 CAD models, each with detailed construction sequences. It is designed to train generative models for 3D design applications.
   - **Access Link:** [DeepCAD Dataset](https://github.com/ChrisWu1997/DeepCAD)
  
22. **ABC Dataset**
    - **Description:** A comprehensive collection of one million Computer-Aided Design (CAD) models, each consisting of explicitly parametrized curves and surfaces. This dataset provides ground truth for differential quantities, patch segmentation, geometric feature detection, and shape reconstruction, facilitating research in geometric deep learning methods and applications.
    - **Access Link:** [ABC Dataset](https://archive.nyu.edu/handle/2451/43778)

---

**How to Get Started:**

- **Select a Dataset:** Choose a dataset that aligns with your specific area of interest or project requirements.
- **Engage in Hands-On Practice:** Utilize the dataset to develop and validate models, automate workflows, or explore innovative solutions.
- **Share Your Findings:** Document your progress and share insights with the CAE community to contribute to collective learning.

*Note: Ensure you review the licensing agreements associated with each dataset to comply with usage guidelines.*

For any additional datasets or suggestions, feel free to contribute to this document.

---
