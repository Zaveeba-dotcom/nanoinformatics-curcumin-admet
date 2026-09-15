# 🧬 Nanoinformatics: Molecular Docking & ProTox-3.0 ADMET Analysis

> **An end-to-end computational workflow evaluating 3D structural modeling, target binding affinity, and machine-learning ADMET toxicity predictions for Curcumin.**

---

## ⚡ Key Capabilities
* **3D Structural Conformation**: 3D spatial modeling and energy minimization using MolView.
* **ProTox-3.0 ADMET Profiling**: Toxicity prediction, organ toxicity identification, and acute oral toxicity ($LD_{50}$) estimation.
* **In-Silico Docking Analysis**: Binding energy ($r$) evaluation against target receptor active sites.

---

## 📂 Repository Layout

```text
Nanoinformatics_Project/
├── README.md                          # Repository homepage
├── structures/
│   ├── curcumin_2d_structure.png      # 2D chemical structure image
│   ├── curcumin_3d_model.png          # 3D ball-and-stick model image
│   └── ligand_curcumin.sdf            # Structural coordinate file
└── results/
    ├── ProTox-3.0_Report.pdf          # Full ProTox prediction output
    └── binding_summary.csv            # Tabulated binding & toxicity data
