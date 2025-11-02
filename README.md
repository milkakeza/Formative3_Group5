# Formative 3: Probability Distributions, Bayesian Probability, and Gradient Descent Implementation 

A comprehensive exploration of Probability Distributions, Bayesian Probabilisty, and Gradient Descent.
## Relevant Links
- Link to the Google Colab: [Formative3_Group5.ipynb](https://colab.research.google.com/drive/1CpG3gW1nvbBv_uFEsxkuEcmiPngB2pdK?usp=sharing)
- Link to Gradient Descent Manual Calculation: [Gradient Descent Manual Calculation.pdf](https://drive.google.com/file/d/1Z4oUGABow4JvLxkb4rKUfx7U4RWmtyWJ/view?usp=sharing)
- Link to Contribution pdf: [Formative3_Group5-Contributions.pdf](https://drive.google.com/file/d/1bVlpd3Aw1t_g_tnGr0_dr9v8TAY2QqhI/view?usp=sharing)

## Overview

This project implements and analyzes three fundamental machine learning concepts:
- Bivariate probability distributions
- Bayesian probability with sentiment analysis
- Gradient descent

## Project Structure

### Part 1: Probability Distributions
Analysis of skin-care product data using bivariate normal distributions.
- Dataset: Skin-care products (price vs. stars)
- Correlation coefficient: -0.13
- Visualizations: Contour plots and 3D surface plots

### Part 2: Bayesian Probability
Sentiment analysis on IMDB movie reviews using Bayes' theorem.
- Dataset: 50,000 IMDB movie reviews
- Keywords analyzed: Positive (loved, best, amazing, enjoyed) and Negative (boring, terrible, worst, bad)
- Calculated: Prior, likelihood, marginal, and posterior probabilities

### Part 3: Gradient Descent Manual Calculation
Hand-calculated gradient descent iterations for linear regression.
- [Manual calculations document](https://drive.google.com/file/d/1Z4oUGABow4JvLxkb4rKUfx7U4RWmtyWJ/view?usp=sharing)
- 5 iterations performed by team members

### Part 4: Gradient Descent Implementation
Programmatic implementation using NumPy and SciPy.
- Initial parameters: m = -1, b = 1
- Learning rate: 0.1
- Final MSE: 0.032 (after 4 iterations)
- 93.8% error reduction in first iteration

## Requirements

```
numpy
pandas
matplotlib
scipy
kagglehub
```

## Key Results

- **Probability**: Weak negative correlation (-0.13) between price and ratings
- **Bayesian**: Successfully computed sentiment probabilities for keyword-based classification
- **Gradient Descent**: Achieved convergence with MSE = 0.032, demonstrating rapid early-stage optimization

## Team Contributions

| Member | Responsibility |
|--------|---------------|
| Mike Kevin Ntwari | Manual Iteration 1, Code Implementation |
| Lorita Sesame Icyeza | Probability Distributions, Manual Iteration 2 |
| Milka Isingizwe | Visualizations, Manual Iteration 3 |
| Nick-Lemy Kayiranga | Bayesian Probability, Manual Iterations 4-5 |

## Usage

Run the notebook in Google Colab for automatic dataset downloads via `kagglehub`.

---

**Note**: Early stopping recommended after 3-4 iterations as error reduction becomes minimal.
