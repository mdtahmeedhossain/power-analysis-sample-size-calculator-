# Statistical Power Analysis: Sample Size Calculator

A simulator that helps determine optimal sample sizes for A/B testing experiments by analyzing the relationship between sample size and statistical power.

## Overview
This tool allows users to input baseline conversion rates and minimum detectable effects, then calculates the required sample size and validates it through simulation. Perfect for planning A/B tests before running them.

## How It Works
1. **User defines parameters**: Baseline rate (22%) and target rate (26%) 
2. **Calculate sample size**: Uses power analysis formula to determine required users
3. **Validate through simulation**: Runs 1000 simulated experiments 
4. **Display results**: Shows the percentage of simulations that achieve statistical significance

## Key Results
- **Required sample size**: 3,568 users needed
- **Simulation validation**: 79.6% of experiments detect the effect (close to target 80%)
- **Planning scenario**: Detecting 22% → 26% conversion rate improvement
- **Effect size**: 18% relative improvement (4 percentage points absolute)

## Use Case
This simulator helps experiment planners determine:
- How many users needed for adequate statistical power
- Whether a planned experiment is feasible given traffic constraints  
- Confidence that real effects will be detected if they exist

## Tools Used
- Python (NumPy, Pandas, Matplotlib)
- Statistical power analysis and Monte Carlo simulation
- Jupyter Notebook
