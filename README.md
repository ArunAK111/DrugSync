# DrugSync: Predicting Drug-Drug Interactions with Graph Neural Networks

## Overview

DrugSync is a deep learning model designed to predict potential drug-drug interactions (DDIs) using Graph Neural Networks (GNNs). DDIs can lead to serious adverse effects, especially in patients on chronic medications. DrugSync analyzes molecular structures and historical data to provide accurate predictions, aiding healthcare providers and patients in managing medication regimens.
<br><br><br>
<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/ArunAK111/DrugSync/blob/main/Images/Before_Interaction.png" alt="Before Interaction" style="width: 35%;">
  <img src="https://github.com/ArunAK111/DrugSync/blob/main/Images/After_Interaction.png" alt="After Interaction" style="width: 35%;">
</div>

<span>Before and After Interactions</span>

## Key Features

- **Graph Neural Network (GNN) Model**: Utilizes GNNs to focus on substructure interactions derived from SMILES data, enabling targeted and efficient DDI predictions.
- **State-of-the-Art Technology**: Implements Graph Attention Networks (GATs) to analyze molecular structures, ensuring precise interaction forecasts.
- **Enhanced Patient Safety**: Helps healthcare providers and patients avoid potential adverse drug reactions by predicting DDIs.
- **Scalable and Efficient**: Can handle large datasets, making it suitable for real-world applications in healthcare.

## How It Works

DrugSync processes drug molecular structures as graphs, where nodes represent atoms and edges represent bonds. It then applies GNNs to learn and predict potential interactions between drugs. The model is trained on a dataset of known DDIs and evaluated on its ability to correctly predict interactions in unseen drug pairs.

## Getting Started

To get started with DrugSync, follow these steps:

1. **Clone the Repository**: `git clone https://github.com/ArunAK111/DrugSync.git`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Download Datasets**: I have uploaded the datasets.
4. **Train the Model**: Use the provided scripts to train the DrugSync model on the dataset.
5. **Evaluate the Model**: Evaluate the trained model on a separate validation or test set to assess its performance.

## Contributing

We welcome contributions to DrugSync! If you have ideas for improvements or new features, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.
