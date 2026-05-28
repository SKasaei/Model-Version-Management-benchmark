
Welcome to the official repository for **BenchmarV**, a benchmark designed to systematically evaluate model versioning systems. This repository accompanies the paper:

> M.-S. Kasaei, A. Fatemi, M. Sharbaf, B. Zamani, D. Blouin, **A feature model and benchmark for model version management in collaborative modeling environments**, Journal of Software: Evolution and Process 38 (5) (2026) e70102


## 📌 Overview

BenchmarV offers:
- A **feature model** and **comparison tables** covering state-of-the-art versioning approaches.
- A set of **8 representative model versioning scenarios**, designed to reflect real-world collaborative modeling needs.
- Detailed **scenario descriptions** and **model artifacts** to enable consistent benchmarking across different tools and techniques.

This repository serves both as a reference implementation and a reusable benchmark for researchers and tool developers working on model versioning and collaborative modeling systems.

---

## 🧩 Repository Structure

- **FeatureModel**: Contains the feature model diagram, its XMI representation, and comparison tables of existing tools.
- **Models**: Includes eight folders, each representing a model versioning scenario with relevant model files. The history of versioning changes are recorded in this part.
- **Scenarios**: Includes the documentation of model versioning scenarios.
- **Questionnaire**: Includes the documentation of a questionnaire for assessing MVMS capabilities .

---

## 📘 Usage

You can use the artifacts in this repository to:
- Evaluate your model versioning approach/tool.
- Reproduce the benchmark scenarios in your modeling environment.
- Compare versioning capabilities.

> Note: Artifacts are provided in standard formats (e.g., XMI and ECORE) for interoperability. If your tool uses a different format, you may adapt the models while preserving their structure and semantics.

---

## 📘 Formulas

> $$ AMVM-Capability = UMVM-Capability × (VAF + BAF) $$

> $$ UMVM-Capability = (NL1 × wl(L1)) + (NL2 × wl(L2)) + (NL3 × wl(L3)) $$

> $$ VCF = {\\frac{1}{Number Of Versioning Scenarios} \sum_{i=1}^{scenarios} v_i } $$

> $$ BCF = {\\frac{1}{Number Of Branching Scenarios} \sum_{i=1}^{scenarios} b_i } $$

> $$ VAF = VCF × {\\frac{1}{max(Versioning Question Values)} \sum_{i=1}^{8} f_i } $$

> $$ BAF = BCF × {\\frac{1}{max(Branching Question Values)} \sum_{i=1}^{5} g_i } $$

> $$ wl(L1) = 1, wl(L2) = 2, wl(L3) = 3 $$

---

## 📄 License

This repository is licensed under the MIT License. Feel free to use, modify, and extend the materials with appropriate citation.

---

## 📬 Contact

For questions, contributions, or collaboration inquiries, please contact:

**Mohammad-Sajad Kasaei**  

Email: smskasaei@gmail.com

---

## 🔗 Citation

If you use BenchmarV in your work, please cite the original paper:
> https://onlinelibrary.wiley.com/doi/10.1002/smr.70102


