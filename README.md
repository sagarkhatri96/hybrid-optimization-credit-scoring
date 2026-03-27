# A Hybrid Optimization Framework for Efficient Feature Selection in Credit Scoring

**MSc Data Science — Thompson Rivers University, BC, Canada (2025)**

---

## Overview

Credit scoring models rely on high-dimensional datasets where many features are redundant or irrelevant. This project develops a **hybrid metaheuristic optimization framework** that intelligently selects the most predictive features for credit scoring, improving model accuracy while reducing computational overhead.

The framework combines the complementary strengths of multiple metaheuristic algorithms — addressing the "No Free Lunch" theorem limitation where no single algorithm consistently outperforms others across all problem types.

---

## Key Results

| Metric | Improvement |
|---|---|
| Feature space reduction | ~20% |
| Model classification accuracy | +14% |
| Processing time | >10% reduction |

---

## Project Structure

```
├── Codes/
│   ├── Feature selection/     # Feature selection algorithms (MATLAB)
│   └── Optimization/          # Hybrid metaheuristic optimization (MATLAB)
├── Project Report/
│   └── Sagar_FinalReport_V2.pdf   # Full MSc report
```

---

## Methodology

The framework consists of two core components:

**1. Feature Selection**
- Wrapper-based feature selection that evaluates subsets using actual model performance
- - Captures nonlinear dependencies and interaction effects among features
  - - Better suited for metaheuristic search than filter-based methods
   
    - **2. Hybrid Metaheuristic Optimization**
    - - Combines global exploration and local search behaviors
      - - Addresses limitations of individual metaheuristic algorithms
        - - Fuses multiple strategies synergistically to improve convergence speed and solution diversity
         
          - **Domain: Credit Scoring**
          - - Binary classification — categorizing borrowers as low-risk or high-risk
            - - Applied to real-world credit dataset with high-dimensional feature space
             
              - ---

              ## Tools & Technologies

              - **Language:** MATLAB
              - - **Domain:** Machine Learning, Metaheuristic Optimization
                - - **Techniques:** Feature Selection, Classification, Hybrid Optimization, EDA
                 
                  - ---

                  ## Academic Context

                  - **Institution:** Thompson Rivers University, Kamloops, BC, Canada
                  - - **Degree:** Master of Science in Data Science
                    - - **Submitted:** April 2025
                     
                      - ---

                      ## Author

                      **Sagar**
                      - LinkedIn: [linkedin.com/in/sagar96](https://www.linkedin.com/in/sagar96/)
                      - - GitHub: [github.com/sagarkhatri96](https://github.com/sagarkhatri96)
