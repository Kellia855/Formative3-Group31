# Formative 3 – Group 31 Presentation

## Introduction
- Project applies probability distributions, Bayesian inference, and optimization.  
- Divided into 4 parts, each led by one member.  
- Part 3 was shared: each member performed one manual iteration.  
- Goal: demonstrate mathematical concepts with clear explanations, tables and plots.

---

## Part 1: Expectation-Maximization (EM) – Kellia
- **Dataset:** Galton Families (child heights).  
- **Steps:**  
  - Imported libraries, loaded dataset, visualized distribution.  
  - Initialized Gaussian parameters (means, variances, mixing coefficients).  
  - Implemented E‑step (responsibilities) and M‑step (parameter updates).  
  - Ran iterations with tracking table showing μ, σ, π, log‑likelihood.  
- **Demo:** Posterior classification for test height.  
- **Key Insight:** Splitting at global mean misclassifies overlapping data; EM provides probabilistic assignments.

---

## Part 2: Bayesian Probability – Henriette
- **Dataset:** IMDb reviews.  
- **Keywords:** Positive → *wonderful, excellent, brilliant*; Negative → *terrible, awful, boring*.  
- **Steps:**  
  - Computed prior, likelihood, marginal, posterior for each keyword.  
  - Verified correctness with direct ratio check.  
  - Displayed results in tables and summary visualization.  
- **Key Insight:** Positive keywords push posterior > 0.5, negative keywords push it < 0.5.  
- **Impact:** Shows how Bayes’ Theorem updates belief with evidence.

---

## Part 3: Gradient Descent (Manual Calculation) – Aime + All Members
- **Setup:** Linear regression with parameters m1, m2, b.  
- **Shared Work:** Each member performed one iteration manually.  
- **Steps:**  
  - Applied Chain Rule for partial derivatives (∂J/∂m, ∂J/∂b).  
  - Showed intermediate results for predictions, errors, gradients, cost.  
  - Updated parameters step by step.  
- **Observation:** Cost dropped sharply at first, then fine‑tuned toward convergence.  
- **Key Insight:** Manual iterations build intuition for optimization.

---

## Part 4: Gradient Descent in Code – Eloi
- **Implementation:** Python with SciPy for derivatives.  
- **Steps:**  
  - Defined cost function (MSE).  
  - Ran gradient descent loop with parameter updates.  
  - Printed predictions, costs, gradients across iterations.  
  - Plotted parameter values and cost reduction.  
- **Key Insight:** Automated gradient descent mirrors manual work, confirming convergence.  
- **Impact:** Demonstrates optimization efficiency with code.

---

## Contributors
- Henriette Biziyaremye  
- Kellia Kamikazi  
- Aime Shyaka  
- Eloi Iradukunda  
