# Divergent Ensemble Networks (DEN) for Uncertainty Estimation

This repository contains the implementation of Divergent Ensemble Networks (DEN), an advanced framework for uncertainty estimation. The code demonstrates three methods: traditional ensembles, MC Dropout, and DEN, showcasing their performance in various uncertainty estimation scenarios.

## Paper Reference
If you use this code in your research, please cite our work:
- **[ArXiv Link](https://arxiv.org/abs/2412.01193)**

## Overview of the Notebook
1. **Ensemble Models**: Demonstrates traditional ensemble methods for uncertainty estimation.
2. **MC Dropout**: Implements Monte Carlo Dropout as a baseline for comparison.
3. **Divergent Ensemble Networks (DEN)**: Implements the proposed DEN architecture, which leverages multi-branch models for efficient and accurate uncertainty estimation.

## Features
- **Ensemble Methods**: Evaluate the effectiveness of uncertainty quantification with multiple model outputs.
- **MC Dropout**: Approximate Bayesian inference using dropout layers at test time.
- **DEN Architecture**: Efficient uncertainty estimation with reduced inference time and computational cost.
- **Evaluation Metrics**: 
  - Confidence
  - Variance
  - Entropy

## Requirements
Install all dependencies using the provided `requirements.txt`.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/Arker123/Divergent-Ensemble-Networks.git
    cd DEN
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter notebook (`DEN.ipynb`) and run the cells sequentially to:
   - Train ensemble models.
   - Implement MC Dropout.
   - Train and evaluate the Divergent Ensemble Networks (DEN).

4. The notebook outputs include metrics for each method and visualizations for uncertainty estimation.

## Data
The data is generated for the regression and Mnist and NotMnist comes preinstalled with the requirments.

## Results
DEN achieves faster inference while maintaining or improving the accuracy of uncertainty estimation compared to traditional ensembles and MC Dropout. This makes it particularly useful for time-sensitive applications like robotics, manufacturing testing, and medical diagnostics.

## Contributing
Feel free to submit pull requests or open issues for suggestions, improvements, or bug fixes.

## License
This repository is licensed under the MIT License. See `LICENSE` for details.

---


