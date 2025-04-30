# project_NI
Neural Responses to Familiar and Unfamiliar Stimuli: Building a Binary Classifier

## Introduction

This project investigates how neural responses differ when processing familiar versus unfamiliar stimuli. It employs binary classification to distinguish between these two stimulus types based on neural activity.

## Methods

1.  **Feature Extraction:**
   * Firing Rate: Average firing rate of neurons.
   * Synchrony: Standard deviation of total neuron activity.
   * Frequency Domain: FFT-band power to capture oscillatory patterns.
2.  **Model Comparison:**
   * Logistic Regression
   * SVM-RBF

## Key Findings

* Firing rate and synchrony show distinct patterns for familiar and unfamiliar stimuli.
* Logistic Regression provides a balanced (simple) linear classification.
* SVM-RBF captures non-linear (complex) patterns and better distinguishes between classes.
* Adding FFT-band power enhances the model, highlighting the role of neural rhythms.

## Conclusion & Outlook

The study demonstrates the importance of firing rate and synchrony in decoding familiarity. Additional work could explore additional frequency ranges, dimensionality reduction techniques, and neural networks.
