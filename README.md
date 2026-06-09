# MATH 5010: Foundations of Statistical Theory & Probability

This repository contains the Quarto book for **MATH 5010 — Foundations of Statistical Theory & Probability**.

The book is designed for graduate students learning probability theory, mathematical statistics, statistical inference, and computational methods. It includes lecture notes, worked examples, practice problems, interactive HTML modules, and Python/Jupyter computer labs.

Published book:

<https://wanghemath.github.io/Book-ProbabilityStatisticalTheory/>

Repository:

<https://github.com/wanghemath/Book-ProbabilityStatisticalTheory>

## Book structure

```text
Book-ProbabilityStatisticalTheory/
├── _quarto.yml
├── index.qmd
├── introduction.qmd
├── labs-summary.qmd
├── chapters/
├── htmls/
├── labs/
├── assets/
└── docs/
```

## Main contents

### Part I. Probability

1. Basic Probability
2. Random Variables and Distributions
3. Joint and Conditional Probability
4. Expectations, Moments, and Moment Generating Functions
5. Transformations of Random Variables
6. Conditional Distributions and Conditional Expectations
6 Extra. Multinomial, Dirichlet, and Multivariate Normal Distributions
7. Inequalities and Identities
8. Sampling and Order Statistics
9. Convergence Theory
10. Monte Carlo Sampling

### Part II. Statistical Inference

11. Sufficient Statistics
12. Point Estimation I
13. Point Estimation II
14. Hypothesis Tests I
15. Hypothesis Tests II
16. Interval Estimation I
17. Interval Estimation II
18. ANOVA I
19. ANOVA II and Applications
20. Bayesian Inference

## Interactive HTML modules

Interactive learning pages are stored in the `htmls/` folder.

The summary page `labs-summary.qmd` links all interactive modules, including:

- `section1_probability_interactive.html`
- `section2_random_variables_interactive.html`
- `section3_joint_conditional_interactive.html`
- `section4_expectation_mgf_interactive.html`
- `section5_transformations_interactive.html`
- `section6_conditional_distribution_interactive.html`
- `section7_inequalities_interactive.html`
- `section8_random_samples_interactive.html`
- `section9_convergence_interactive.html`
- `section10_monte_carlo_interactive.html`
- `section11_sufficient_statistics_interactive.html`
- `sections12_13_point_estimation_interactive.html`
- `sections14_15_hypothesis_tests_interactive.html`
- `sections16_17_interval_estimations_interactive.html`
- `sections18_19_anova_interactive.html`
- `section20_bayesian_inference_interactive.html`

## Computer labs

Jupyter notebook labs are stored in the `labs/` folder.

Students can open notebooks directly in Google Colab using links of the form:

```text
https://colab.research.google.com/github/wanghemath/Book-ProbabilityStatisticalTheory/blob/main/labs/NOTEBOOK_NAME.ipynb
```

The lab index is available in:

```text
labs-summary.qmd
```

## Build locally

Install Quarto first:

<https://quarto.org/docs/get-started/>

Then clone this repository and render the book:

```bash
git clone https://github.com/wanghemath/Book-ProbabilityStatisticalTheory.git
cd Book-ProbabilityStatisticalTheory
quarto render
```

To preview locally:

```bash
quarto preview
```

The rendered website is written to the `docs/` folder, which can be used for GitHub Pages.

## GitHub Pages setup

In the GitHub repository, go to:

```text
Settings → Pages
```

Use:

```text
Source: Deploy from a branch
Branch: main
Folder: /docs
```

After rendering and pushing the `docs/` folder, the book should appear at:

<https://wanghemath.github.io/Book-ProbabilityStatisticalTheory/>

## Updating the book

After editing `.qmd` files or adding labs/HTML files:

```bash
quarto render
git add .
git commit -m "Update MATH 5010 Quarto book"
git push origin main
```

## License

Unless otherwise noted, the educational text, lecture notes, examples, exercises, interactive pages, and notebooks in this repository are licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**.

See `LICENSE` for details.

## Author

**He Wang, Ph.D.**  
Associate Teaching Professor  
Department of Mathematics  
Northeastern University
