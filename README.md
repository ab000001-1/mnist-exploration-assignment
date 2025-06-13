## MNIST Machine Learning Exploration

## Overview
This project modifies the instructor-provided MNIST Example Colab notebook to explore machine learning variations on the MNIST dataset. 
The program runs experiments using a T4 GPU runtime, analyzing different configurations of mini-batches, hidden units, and network architectures, and reports findings in a concise PDF.

## Project Description
The MNIST dataset is used to train and evaluate neural networks for digit classification. 

#### The project focuses on three experimental variations:

#### Mini-Batches: Compares the default 1000 mini-batches with iteration and epoch learning, testing alternative mini-batch sizes to recommend the optimal number.

#### Hidden Units: Evaluates a single-hidden-layer network with 784 units (baseline) against networks with 1/8th, 1/4th, 1/2, 2x, 4x, and 8x units. 
Analyzes loss over time and confusion matrices for training and testing datasets to recommend an ideal unit count.

#### Multi-Layer Networks: Designs three two-hidden-layer networks with approximately 623,290 parameters (matching the baseline’s total) and observes their training and performance.

## Output

#### A PDF report detailing observations, including:

#### Tables and graphs with titles, captions, and labeled axes.

#### Discussion of trends and notable findings for each experiment.

#### Modified Colab notebook with implemented variations.

## Notes

#### Emphasizes clear presentation with proper grammar, spelling, and formatting.

#### All experiments use the T4 GPU runtime for consistency.

#### Results are visualized and analyzed to support recommendations.

