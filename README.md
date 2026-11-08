# Sampling, Uncertainty and Statistical Inference in Cognitive Neuro

### An Interactive Python Tutorial

This interactive Jupyter notebook introduces fundamental concepts in statistical inference through simulated cognitive and neuroscience data. It is designed for students and researchers learning to use Python for statistical analysis, with practical exercises combining computational simulations, data visualisation and hypothesis testing.

The tutorial covers:

- Populations, samples and sampling variability
- Sampling distributions and hypothesis testing
- The influence of sample size on statistical inference
- Standard deviation and standard error of the mean (SEM)
- The central limit theorem
- Normal and Student's *t*-distributions

## Tutorial overview

The tutorial begins with a simulated visual detection experiment involving a reference population of 12,000 participants, with a mean reaction time of 310 ms and a standard deviation of 45 ms.

Using Python, we investigate how repeated random samples from this population vary, how sample size affects the precision of estimates, and how sampling distributions can be used to evaluate hypotheses about observed differences between groups.

Subsequent exercises introduce non-normally distributed neural-response measurements to demonstrate the central limit theorem and explore the distinction between population variability and uncertainty in sample estimates.

All datasets are synthetic and generated within the notebook.

## Getting started

**[Open the Jupyter notebook](sampling_and_inference.ipynb)**

The notebook can be viewed directly on GitHub or executed using Jupyter Notebook or Google Colab.

To run it locally, clone the repository and install the required packages:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
pip install -r requirements.txt
jupyter notebook sampling_and_inference.ipynb
```

Python 3.10 or later is recommended.

## Tutorial structure

| Section | Topic |
|---|---|
| 1 | Simulating a population |
| 2 | Drawing random samples |
| 3 | Constructing sampling distributions |
| 4 | Investigating the effect of sample size |
| 5 | Standard deviation versus standard error |
| 6–7 | Exploring the central limit theorem |
| 8 | Normal and Student's *t*-distributions |
| 9 | Generating non-normal distributions |
| 10 | Further exercises and interpretation |

## Python dependencies

The tutorial uses:

- **NumPy** — numerical computation and random sampling
- **SciPy** — probability distributions and statistical functions
- **Matplotlib** — statistical visualisation
- **Jupyter Notebook** — interactive code execution

All simulations use a fixed random seed for reproducibility. No external datasets are required.

## Learning outcomes

By completing this tutorial, students should be able to distinguish between population parameters and sample statistics, construct empirical sampling distributions using repeated simulation, explain the relationship between sample size and standard error, and apply fundamental principles of statistical inference to simulated experimental data.

Students will also gain practical experience writing Python code to generate random samples, manipulate numerical arrays and visualise probability distributions.

