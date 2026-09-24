### Diabetes Risk Factors with Logistic Regression
**Tools: Python, statsmodels, scikit-learn, pandas, Seaborn** | M.S. Data Analytics Project (D208 - Predictive Modeling)

A logistic regression analysis examining which patient characteristics are associated with a diabetes diagnosis, with careful attention to model diagnostics.
 
- Applied the same automated VIF and backward elimination workflow, and documented the decision to keep one high-VIF variable after testing showed removing it hurt performance
- Calculated AIC and a likelihood ratio test by hand from model output, since the logit summary did not report them, and confirmed the reduced model fit as well as the full model
- Built a confusion matrix on an 80/20 split and showed that 71.8% accuracy came from a model predicting no diabetes cases at all
- Recommended rebalancing techniques and imbalance-appropriate metrics as next steps

[Documentation](https://github.com/hrbergman/postgresql-customer-services-query/blob/main/postgresql-customer-services-query/data-acquisition-documentation.pdf)
| 
[Video Presentation](https://youtu.be/jKOE0cG68rc)
