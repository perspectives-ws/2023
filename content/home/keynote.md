+++
# Keynote page.
widget = "blank"
headless = true  # This file represents a page section.
weight = 30
active = true

# ... Put Your Section Options Here (title etc.) ...
title = "Keynote"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
+++

### Keynote: Teaching Algorithms to Explain Recommender Systems: A Counterfactual Evaluation Approach
Noam Koenigstein

**Abstract**
In this talk, I will introduce the Learning to eXplain Recommendations (LXR) framework, a model-agnostic, post-hoc framework to explain recommender systems. LXR can work with any differentiable recommender and learns to score the importance of users' personal data with respect to a recommended item. The framework's objective employs a novel counterfactual loss function that aims to identify the user data that best explains the item's recommendation. Additionally, in order to evaluate LXR, we propose several new evaluation metrics, inspired by saliency map evaluation in computer vision, for assessing explanations in recommender systems. Assessing explanations in artificial intelligence, especially those pertaining to recommender systems, is an emerging area of study that currently lacks universally accepted metrics or standardized test sets. Our evaluations are based on counterfactual test that attempt to gauge the impact of the provided “explanations” on the ultimate recommendations. LXR's code is publicly available at https://github.com/ExplainingRecommendations/LXR.

**Bio**  
Dr. Noam Koenigstein earned his B.Sc. in Computer Science with honors from the Technion – Israel Institute of Technology in Haifa in 2007. He followed this with an M.Sc. in Electrical Engineering from Tel-Aviv University in 2009 and a Ph.D. from the same institution in 2013. Noam began his professional career at Microsoft in 2011, joining the Xbox Machine Learning research team where he was instrumental in developing the recommendation algorithm that now serves millions of users globally. He later led Microsoft Store's recommendation research team.

In 2017, he transitioned to the financial sector, taking on the role of Senior Vice President and Head of Data Science at Citi Bank’s Israeli Innovation Lab. At Citi, he directed all data science initiatives at the Israeli research facility. The following year, Noam returned to academia, joining Tel Aviv University's Industrial Engineering Department as an Assistant Professor (Senior Lecturer). He currently spearheads the DELTA Lab, focusing on the practical application of deep-learning technologies with a special emphasis on recommender systems. Under his guidance, students explore a wide range of machine learning applications across various real-world challenges.