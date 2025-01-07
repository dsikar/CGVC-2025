# The Misclassification Likelihood Matrix: Some Classes Are More Likely To Be Misclassified Than Others

Research repository supporting our submission to the [Computer Graphics & Visual Computing Conference 2024 Special Issue](https://www.sciencedirect.com/special-issue/313098/computer-graphics-visual-computing-conference-2024-special-issue).

## Abstract

This study introduces the Misclassification Likelihood Matrix (MLM) as a novel tool for quantifying the reliability of neural network predictions under distribution shifts. The MLM is obtained by leveraging softmax outputs and clustering techniques to measure the distances between the predictions of a trained neural network and class centroids. By analyzing these distances, the MLM provides a comprehensive view of the model's misclassification tendencies, enabling decision-makers to identify the most common and critical sources of errors. The MLM allows for the prioritization of model improvements and the establishment of decision thresholds based on acceptable risk levels. The approach is evaluated on the MNIST dataset using a Convolutional Neural Network (CNN) and a perturbed version of the dataset to simulate distribution shifts. The results demonstrate the effectiveness of the MLM in assessing the reliability of predictions and highlight its potential in enhancing the interpretability and risk mitigation capabilities of neural networks. The implications of this work extend beyond image classification, with ongoing applications in autonomous systems, such as self-driving cars, to improve the safety and reliability of decision-making in complex, real-world environments.

## Repository Structure

```
CGVC-2025/
├── experiments/         # Reproducible experimental code
│   ├── baseline/       # Baseline model implementations
│   └── mlm/           # MLM computation and analysis
├── figures/            # Script-generated visualizations
├── tables/            # Script-generated data tables
└── docs/              # Reference papers and documentation
```

## Purpose

This repository contains all code and resources necessary to reproduce the experimental results presented in our paper. It serves three main purposes:

1. Providing a complete, reproducible codebase for all experiments and analyses
2. Generating all figures and tables used in the manuscript (maintained in Overleaf)
3. Supporting reproducibility of results for peer review
   
## Manuscript

The manuscript is maintained in a private Overleaf project, direct access to the manuscript requires previously granted permission.

Overleaf Project ID: 677c178dd075271166020dfb

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/dsikar/CGVC-2025.git
cd CGVC-2025
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the experiments:
```bash
python experiments/run_all.py
```

## Contributing

We welcome contributions to improve the codebase and extend the research. Please get in touch or send a pull request if you would like to contribute.

**Principal Investigator:** Daniel Sikar  
**Email:** daniel.sikar@city.ac.uk

## Citation

If you use this code or refer to our research, please cite:

```bibtex
@article{Sikar_mlm2025,
  title={The Misclassification Likelihood Matrix: Some Classes Are More Likely To Be Misclassified Than Others},
  author={D. Sikar, A. d'Avila Garcez, R. Bloomfield, T. Weyde, K. Peeroo, N. Singh, M. Hutchinson, D. Laksono, M. Reljan-Delaney},
  journal={Computer Graphics & Visual Computing Conference Special Issue},
  year={2025}
}
```

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)