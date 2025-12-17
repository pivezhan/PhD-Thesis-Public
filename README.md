# PhD Dissertation: Data-Efficient AI-Guided Energy- and Thermal-Aware Scheduling on Heterogeneous Multicore Systems

**Author:** Mohammad Pivezhandi
**Institution:** Wayne State University
**Department:** Computer Science
**Advisor:** Dr. Abusayeed Saifullah
**Defense:** December 2025

## Overview

This repository contains the compiled PDF of my PhD dissertation on data-efficient AI-guided scheduling for heterogeneous multicore embedded systems. The dissertation presents a comprehensive framework integrating hierarchical multi-agent reinforcement learning, statistical learning, distribution-aware flow matching, model-based reinforcement learning, and graph neural network-driven performance modeling.

## Download

**[Download Dissertation PDF](outputs/thesis.pdf)** (238 pages)

## Key Contributions

| Contribution | Result |
|-------------|--------|
| HiDVFS (Hierarchical MARL) | 31.7% energy reduction, 34.1% makespan improvement |
| Statistical Feature Selection | 10% energy reduction, 5°C temperature decrease |
| ZeroDVFS (Model-based MARL) | 7x thermal prediction improvement, zero-shot transfer |
| FlowRL (Flow Matching) | 30% frame rate improvement in few-shot RL |
| GraphPerf-RT (GNN Performance Model) | Automated code variation selection |

## Dissertation Structure

| Chapter | Title | Description |
|---------|-------|-------------|
| 1 | Introduction | Challenges and framework overview |
| 2 | HiDVFS | Hierarchical multi-agent RL for energy/thermal-aware DVFS |
| 3 | Feature Evaluation | Statistical learning for task-to-core allocation |
| 4 | ZeroDVFS | Model-based MARL for zero-shot platform transfer |
| 5 | FlowRL | Distribution-aware flow matching for data augmentation |
| 6 | GraphPerf-RT | Graph neural network-driven performance modeling |
| 7 | Conclusion | Summary of contributions and future directions |

## Related Research Projects

| # | Project | Description |
|---|---------|-------------|
| 1 | [01-HiDVFS](https://github.com/pivezhan/01-HiDVFS) | Hierarchical Multi-Agent RL for DVFS |
| 2 | [02-FeatureEvaluation](https://github.com/pivezhan/02-FeatureEvaluation) | Statistical Learning for Task-to-Core Allocation |
| 3 | [03-ZeroDVFS](https://github.com/pivezhan/03-ZeroDVFS) | Model-based Policy Learning for Scheduling |
| 4 | [04-FlowRL](https://github.com/pivezhan/04-FlowRL) | Distribution-Aware Flow Matching for Few-shot RL |
| 5 | [05-GraphPerf-RT](https://github.com/pivezhan/05-llm-based-profiler) | Graph-Driven Performance Modeling |

## Platforms Validated

- NVIDIA Jetson TX2
- NVIDIA Jetson Orin NX
- Rubik Pi
- Intel Core i7 (8th and 12th Gen)
- Intel Xeon 2680 v3

## Benchmarks

- **BOTS** (Barcelona OpenMP Task Suite): FFT, Strassen, N-Queens, Sort, SparseLU, Floorplan, Health, UTS, Alignment, Knapsack, Fib, Concom
- **PolyBench/C**: 30 kernels across linear algebra, stencils, medley, and datamining categories

## Citation

```bibtex
@phdthesis{pivezhandi2025dissertation,
  title={Data-Efficient AI-Guided Energy- and Thermal-Aware Scheduling on Heterogeneous Multicore Systems},
  author={Pivezhandi, Mohammad},
  year={2025},
  school={Wayne State University},
  department={Computer Science}
}
```

## Source Materials

The complete source materials including LaTeX files, code, and experimental data are available in the private repository:

```
private-source/  # Submodule: pivezhan/PhD-Thesis (private)
```

To access (requires authorization):
```bash
git submodule update --init --recursive
cd private-source/Thesis
make thesis
```

## License

Copyright (c) 2023-2025 Mohammad Pivezhandi. All rights reserved.

The PDF document is provided for academic reference. For source code and data access, please contact the author.

## Contact

- **Email:** pivezhandi@wayne.edu
- **Advisor:** Dr. Abusayeed Saifullah
- **Committee:** Dr. Ali Jannesari, Dr. Zheng Dong, Dr. Nathan Fisher

---

*Last updated: December 2025*
