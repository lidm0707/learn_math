# Plan 01 - What to Learn Next After Linear Algebra

## Prerequisites Check
- [ ] Complete all 20 exercises in `03_linear_algebra_exercises.ipynb`
- [ ] Run `02_linear_algebra_visual.ipynb` and understand every plot
- [ ] Watch 3Blue1Brown "Essence of Linear Algebra" (YouTube)

## Learning Roadmap (Priority Order)

### Step 1: Calculus for ML (The "How Things Change" Math)
Why: Neural networks learn by adjusting weights. Calculus tells you WHICH direction to adjust.
- Derivatives = rate of change (slope of curve)
- Partial derivatives = change one variable, keep rest fixed
- Gradient = vector of all partial derivatives (points uphill)
- Chain rule = how to compose derivatives (backpropagation = chain rule)
- Notebook: `learn/04_calculus_basics.ipynb`

### Step 2: Probability & Statistics (The "Uncertainty" Math)
Why: Real data is noisy. You need to understand distributions, likelihood, and uncertainty.
- Mean, variance, standard deviation
- Normal distribution (bell curve)
- Bayes' theorem
- Random variables
- Notebook: `learn/05_probability_basics.ipynb`

### Step 3: Applied Linear Algebra (Going Deeper)
Why: Connect linear algebra to real algorithms.
- PCA (dimensionality reduction) = eigenvalues in action
- Least squares regression = solving overdetermined systems
- Cosine similarity vs dot product
- Matrix factorization (LU, QR, Cholesky)
- Notebook: `learn/06_applied_linear_algebra.ipynb`

### Step 4: Optimization (The "Finding the Best" Math)
Why: ML = optimization. Find parameters that minimize error.
- Gradient descent (the engine of deep learning)
- Learning rate
- Loss functions (MSE, cross-entropy)
- Convexity (why some problems are easy, some are hard)
- Notebook: `learn/07_optimization_basics.ipynb`

## Optional (Advanced)
- Step 5: Information Theory (entropy, KL divergence)
- Step 6: Graph Theory (neural network architectures)

## Status
- [x] Step 1: Calculus → `04_calculus_basics.ipynb` (8 sections, visual)
- [x] Step 2: Probability & Statistics → `05_probability_basics.ipynb` (9 sections, visual)
- [x] Step 3: Applied Linear Algebra → `06_applied_linear_algebra.ipynb` (5 sections, 4 real algorithms)
- [x] Step 4: Optimization → `07_optimization_basics.ipynb` (7 sections, full training loop)

## TODO
- [ ] Run `uv add matplotlib scipy` to add dependencies
- [ ] Verify all notebooks run correctly in Jupyter
