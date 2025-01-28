# Counterfactual Explanations for Model Distillation

Machine learning plays an important role in industries like finance and healthcare, helping organizations make smarter decisions. Advances in algorithms, computing power, and access to large datasets have made it easier to develop powerful models. However, **complex machine learning models** such as random forests and decision trees, often become difficult to understand, **sacrifice transparency and interpretability** , which is a problem when decisions significantly impact people's lives.

Let's take the credit lending sector as an example—machine learning models evaluate customer profiles based on factors like income and credit score to decide whether to approve a loan. These decisions directly affect both the financial well-being of the customer and the risk management of the company. To build trust, companies need to explain these decisions clearly and transparently. Yet, complex machine learning models often fall short in providing explanations.

This is where **counterfactual explanations** come in. They answer "what-if" questions by showing how small changes in input features could lead to different outcomes. For instance, a counterfactual explanation might suggest that increasing a credit score by 50 points would change a loan decision from rejection to approval. These explanations are particularly useful for understanding the behavior of complex models and offering clearer insights.

The project focuses on exploring **how counterfactual explanations can be integrated into model distillation**. Model distillation is a technique where a simpler model uses the knowledge from a complex model, helping to **balance interpretability and accuracy**. 
## Objectives

This project aims to develop a practical framework that generates counterfactual explanations using random forest models. These newly generated datapoints are then used to retrain models like logistic regression, decision trees, and random forests. The study systematically compares the performance of these models by evaluating their accuracy, F1 score, and AUC score. By examining the impact of counterfactual explanations on model training, the research seeks to understand how they can enhance both interpretability and predictive performance of simple models.

**Key objectives include:**

- Exploring methods for generating meaningful counterfactual explanations.
- Identifying the best ways to use counterfactuals in model distillation.
- Understanding how counterfactuals relate to decision boundaries in models.
- Using counterfactuals to create synthetic datasets for training simplified models.

The ultimate goal is to create machine learning systems that are **transparent, reliable,** and **accurate**, making them suitable for critical applications such as credit risk assessment and insurance predictions.


## Authors

- [Dide Uzun](https://www.github.com/dideuzun) - [LinkedIn ](https://www.linkedin.com/in/dideuzun/) - **Email:** dideuzun99@gmail.com
- Project Supervisor: [Riccardo Pinosio](https://github.com/riccardopinosio)
- Project Second Assessor: Raymond Zwaal <br /> <br />
Amsterdam University of Applied Sciences <br />
Master Digital Driven Business <br />
