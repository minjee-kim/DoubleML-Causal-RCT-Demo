# Double Machine Learning in Clinical Trials

This repository demonstrates the use of **Double Machine Learning (DoubleML)** for causal inference in
randomized clinical trials and applied health data.  

It includes two compact examples:

1. **RCT with non-compliance → DoubleML PLIV**  
   Simulated trial with partial treatment uptake, showing how to estimate a complier/local average treatment effect.

2. **Observational health (NHANES) → DoubleML IRM**  
   Application using real-world survey data to estimate the effect of smoking on blood pressure while adjusting for high-dimensional covariates.

---

## Why DoubleML?

Traditional regression often struggles with confounding and high-dimensional covariates.  
**Double Machine Learning** uses orthogonal scores and cross-fitting to debias nuisance estimation. "Debiased" causal effect estimation is possible even when machine learning models are used for adjustment.

These methods build on the original formulation by Chernozhukov et al. (2018), *Double/debiased machine learning for treatment and structural parameters*, *The Econometrics Journal* [doi:10.1111/ectj.12097](https://doi.org/10.1111/ectj.12097).

This repository uses the DoubleML package, an open-source implementation of the Double/Debiased Machine Learning framework originally proposed by Chernozhukov et al. (2018).

---

## DoubleML

- Partially Linear Instrumental Variables model

- Partial Linear Regression for Binary Treatment

---

## References

- Chernozhukov, V., Chetverikov, D., Demirer, M., Duflo, E., Hansen, C., Newey, W., & Robins, J. (2018).  
  *Double/debiased machine learning for treatment and structural parameters*.  
  *The Econometrics Journal*, 21(1), C1–C68.  
  [DOI: 10.1111/ectj.12097](https://doi.org/10.1111/ectj.12097)

- Zheng, C., Dai, R., Gale, R. P., & Zhang, M. J. (2020).  
  *Causal inference in randomized clinical trials*.  
  *Bone Marrow Transplantation*, 55, 4–8.  
  [Nature link](https://doi.org/10.1038/s41409-020-0793-6)

- Ling, Y., Upadhyaya, P., Chen, L., Jiang, X., & Kim, Y. (2022).  
  *Emulate randomized clinical trials using heterogeneous treatment effect estimation for personalized treatments: Methodology review and benchmark*.  
  *Journal of Biomedical Informatics*.  
  [PubMed link](https://pubmed.ncbi.nlm.nih.gov/36455806/) (PMCID: PMC9845190)

- **DoubleML Documentation** — Official package reference and tutorials:  
  [https://docs.doubleml.org/stable/index.html](https://docs.doubleml.org/stable/index.html)


---

## Repo Layout
