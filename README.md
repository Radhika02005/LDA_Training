# LDA_Training
Linear Discriminant Analysis (LDA) for Classification

Overview

This project implements Linear Discriminant Analysis (LDA) to classify samples as "Good" or "Bad" based on sensor readings. The dataset is preprocessed, normalized, and projected onto an LDA component for visualization and analysis.

Features

Data Preprocessing: Handles dataset loading, balancing, and normalization.

LDA Implementation: Uses sklearn.discriminant_analysis.LinearDiscriminantAnalysis.

Visualization: Generates histograms to visualize class separation.

Feature Importance Analysis: Determines feature contributions using LDA coefficients.

Installation

Install dependencies using:

pip install pandas numpy matplotlib scikit-learn

Usage

Load dataset and assign labels based on conditions.

Normalize features using StandardScaler.

Perform LDA and project data onto a single component.

Visualize results using histograms.

Analyze feature contributions using LDA coefficients.

Expected Output

Histogram Plot: Displays class separation.

Feature Importance Table: Ranks feature contributions.

License

Open-source under the MIT License.

Author

Created by [Your Name]
