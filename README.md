# PhD Thesis: Data-Efficient AI-Guided Energy- and Thermal-Aware Scheduling on Heterogeneous Multicore Systems

**Author:** Mohammad Pivezhandi
**Institution:** University of Texas at El Paso (UTEP)
**Department:** Computer Science

## Overview

This repository contains the compiled PDF outputs of my PhD dissertation on data-efficient AI-guided scheduling for heterogeneous multicore systems. The thesis explores machine learning approaches for energy and thermal-aware task scheduling.

## Dissertation Structure

The thesis is organized into the following chapters:

| Chapter | Title | Research Area |
|---------|-------|---------------|
| 1 | Introduction | Overview and Motivation |
| 2 | Hierarchical Multi-Agent RL (HMARL) | Energy/thermal-aware scheduling using hierarchical MARL |
| 3 | Feature Evaluation | Statistical learning for feature-aware task-to-core allocation |
| 4 | Distribution-Aware Flow Matching | Few-shot RL with distribution-aware approaches |
| 5 | LLM-Based Profiler | LLM-based task profiling (in progress) |
| 6 | Proposed Work & Conclusions | Future directions and summary |

## Compiled Documents

The `outputs/` directory contains:

- `thesis.pdf` - Complete dissertation document
- `chapters/` - Individual chapter PDFs (when available)
- `papers/` - Published/submitted papers from each chapter

## Related Publications

This dissertation is based on the following research projects:

| # | Project | Repository | Description |
|---|---------|------------|-------------|
| 1 | 01-HiDVFS | pivezhan/01-HiDVFS | Hierarchical Multi-Agent RL for DVFS |
| 2 | 02-FeatureEvaluation | pivezhan/02-FeatureEvaluation | Statistical Learning for Task-to-Core Allocation |
| 3 | 03-ZeroDVFS | pivezhan/03-ZeroDVFS | Model-based Policy Learning for Scheduling |
| 4 | 04-FlowRL | pivezhan/04-FlowRL | Distribution-Aware Flow Matching for Few-shot RL |
| 5 | 05-llm-based-profiler | pivezhan/05-llm-based-profiler | LLM-Based Task Profiling |
| 6 | FPGA-Vision-Survey | pivezhan/FPGA-Vision-Survey | Vision FPGA Accelerators Survey (public) |

## Source Materials

The complete source materials including LaTeX files, code, and experimental data are available in the private repository linked as a submodule:

```
private-source/  # Submodule: pivezhan/PhD-Thesis (private)
```

To access the full source (requires authorization):
```bash
git submodule update --init --recursive
```

## Building from Source

If you have access to the private submodule:

```bash
cd private-source/Thesis
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Survey Paper

This repository also includes materials from our comprehensive survey:

- **Vision FPGA Accelerators: A Comprehensive Survey (2015-2025)**

## License

Copyright (c) 2023-2025 Mohammad Pivezhandi. All rights reserved.

The PDF documents are provided for academic reference. For source code and data access, please contact the author.

## Contact

- **Email:** pivezhandi@wayne.edu
- **Advisor:** Dr. Abusayeed Saifullah
- **Committee:** Dr. Ali Jannesari, Dr. Prashant Modekurthy, Dr. Zheng Dong
