# Disease-Gene-Prioritization-with-Privileged-Information-and-Heteroscedastic-Dropout
Sure, here is the README file in markdown format suitable for GitHub:

---

# Disease-Gene Association Predictions through Relational Graph Attention Networks

## Overview

This project explores the application of advanced Graph Neural Networks (GNNs) to predict disease-gene associations. We leverage the strengths of Graph Attention Networks (GATs) and introduce novel approaches such as the Relational Graph Attention Network (RGAT), Heat Kernel Convolution (HeatConv), and Partition Graph Convolutional Network (PGCN) to enhance the accuracy and robustness of predictions.

## Key Components

- **Replication of Baseline GAT Models:** Successfully replicated existing GAT-based models to establish a reliable performance benchmark.
- **Development of RGATConv:** Innovatively designed to incorporate relational data, improving the capture of intricate relationships within gene-disease associations.
- **Integration of HeatConv:** Utilizes heat diffusion processes to enhance feature representation and identify localized patterns.
- **Introduction of PGCN:** Segments the graph into subgraphs for more focused and efficient analysis, particularly beneficial for large-scale genomic data.

## Project Structure

- **/src:** Contains all source code for the models and data processing.
- **/data:** Includes the datasets used for training and evaluation.
- **/results:** Stores the results of model evaluations and experiments.
- **/docs:** Contains documentation, including this README file and detailed descriptions of methodologies and findings.
- **/notebooks:** Jupyter notebooks used for exploratory data analysis and model development.

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/disease-gene-prediction.git
   cd disease-gene-prediction
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Training the Models

To train the models, navigate to the `/src` directory and run the training scripts. For example:

```bash
cd src
python train_gat.py  # Train the baseline GAT model
python train_rgat.py  # Train the RGAT model
python train_heatconv.py  # Train the HeatConv model
python train_pgcn.py  # Train the PGCN model
```

### Evaluating the Models

Evaluation results, including metrics like accuracy and ROC AUC, will be saved in the `/results` directory. Use the provided scripts to generate evaluation reports:

```bash
python evaluate_models.py
```

### Visualizing Results

Jupyter notebooks in the `/notebooks` directory can be used to visualize and analyze the results. For example:

```bash
jupyter notebook notebooks/visualize_results.ipynb
```

## Key Findings

- **Improved Accuracy:** Achieved a significant increase in prediction accuracy over baseline models.
- **Enhanced ROC AUC:** Notable improvement in the ROC AUC metric, indicating better model performance in distinguishing between positive and negative associations.
- **Robustness Across Datasets:** Models demonstrated consistent performance across various genomic datasets, highlighting their adaptability and reliability.

## Future Work

Future research will focus on integrating multi-modal biological data, fostering interdisciplinary collaborations, exploring advanced computational techniques like reinforcement learning and quantum computing, and addressing ethical considerations in genetic data handling. The project aims to contribute to open science by making models, datasets, and findings publicly available.

## Acknowledgments

This research was conducted at the Viterbi School of Engineering, University of Southern California. We thank our advisors and collaborators for their support and guidance.

## Contact

For any questions or further information, please contact the authors:
- Saarthak Mehta: [mehtasaa@usc.edu](mailto:mehtasaa@usc.edu)
- Yihao Zheng: [yihaozhe@usc.edu](mailto:yihaozhe@usc.edu)
- Tiffany Hoi Ching Wong: [twong225@usc.edu](mailto:twong225@usc.edu)
- Oliver Swack: [swack@usc.edu](mailto:swack@usc.edu)
- Lei Zhu: [zhulei@usc.edu](mailto:zhulei@usc.edu)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This markdown version provides a structured and clear README file suitable for display on GitHub.
