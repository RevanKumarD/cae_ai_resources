# Physics-Informed Neural Networks (PINNs) for CAE Workflows

This document provides resources for **Physics-Informed Neural Networks (PINNs)** and their applications in **Computer-Aided Engineering (CAE)**.

## 📌 Fundamentals & Tutorials

* **PINNs Tutorial by Raissi, Perdikaris, Karniadakis (Original Authors)**: [https://maziarraissi.github.io/PINNs/](https://maziarraissi.github.io/PINNs/)
  * An excellent starting point with code examples, but uses TensorFlow 1.x and needs updating to TensorFlow 2.x/PyTorch for modern use.
* **YouTube Tutorials on PINNs**: Search "Physics Informed Neural Networks tutorial" on YouTube for many video explanations and code-walkthroughs.
* **"Introduction to PINNs" by The Engineered Mind**.
* **"Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations" - Original PINNs Paper (2019)**: [https://www.sciencedirect.com/science/article/pii/S004579491832403X](https://www.sciencedirect.com/science/article/pii/S004579491832403X)
  * A must-read for understanding the core concept.

## 📌 Libraries & Tools

* **DeepXDE**: [https://deepxde.readthedocs.io/en/latest/](https://deepxde.readthedocs.io/en/latest/)
  * A Python library focused on PINNs that supports TensorFlow and PyTorch.
  * Offers tutorials and examples on implementing PINNs for various engineering problems.
* **Modulus (NVIDIA)**: [https://developer.nvidia.com/modulus](https://developer.nvidia.com/modulus)
  * A commercial platform but with a free tier for research, and a powerful platform for physics-ML.
* **SciANN**: [https://sciann.readthedocs.io/en/latest/](https://sciann.readthedocs.io/en/latest/)
  * A Keras/TensorFlow wrapper for scientific computations and physics-informed deep learning.
  * A Python library for scientific machine learning that includes PINNs.
* **TensorFlow and PyTorch**: PINNs can be implemented directly using these frameworks.

## 📌 Research Papers

* **"Physics-Informed Neural Networks: A Comprehensive Review"**: This paper provides an extensive overview of PINNs, discussing their formulation, applications in solving partial differential equations, and relevance to CAE workflows.
* **"Physics-Informed Neural Networks for Engineering Applications" by Fraunhofer IISB**.
* **"Data-driven solutions of nonlinear partial differential equations" (2017 - Precursor to PINNs)**: [https://arxiv.org/abs/1706.07831](https://arxiv.org/abs/1706.07831)
  * Important earlier work.
* **"On the approximation properties of neural network-based PDE solvers" (2020)**: [https://arxiv.org/abs/2007.01338](https://arxiv.org/abs/2007.01338)
  * Explores theoretical aspects of PINNs approximation.

## 📌 CAE-Specific Applications & Research Papers

* **Solving PDEs in CAE contexts (heat transfer, fluid flow, solid mechanics)**:
  * Papers on PINNs for forward and inverse problems in various engineering disciplines: Search Google Scholar for "physics informed neural networks fluid dynamics" "PINNs heat transfer" "PINNs solid mechanics"
* **Applications of PINNs for parameter identification and model calibration in CAE**:
  * Search Google Scholar for "PINNs parameter identification CAE" "PINNs model calibration simulation"
* Many application-specific PINNs papers exist - search in your specific CAE domain.

## 📌 Case Studies

* **EPFL's Computer Vision Lab applications in aeronautics engineering**.

This resource list should provide a strong starting point for exploring PINNs in CAE. Remember to search Google Scholar for application-specific papers relevant to your particular CAE domain.

---

📌 *Contribute additional resources by submitting a pull request!*