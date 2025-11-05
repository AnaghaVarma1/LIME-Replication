## A Reproducibility Study of LIME: A From-Scratch Implementation and Critical Analysis

**Author:** Anagha Varma

**[Please find the full paper here (PDF)](./Research Paper/LIME Replication (v1).pdf)**

**For any questions or comments, please connect with me on [LinkedIn](https://www.linkedin.com/in/anagha-varma/)**
---

### Abstract
The increasing complexity of “black box” machine learning models poses a significant challenge to their safe and reliable deployment. Explainable AI (XAI) seeks to address this, and the Local Interpretable Model-agnostic Explanations (LIME) algorithm remains a foundational method for generating local model explanations.

This paper presents a from-scratch reproducibility study of LIME, detailing the implementation of both its instance-level explainer and the Submodular Pick (SP-LIME) algorithm for global summaries. Using a Naïve Bayes classifier trained on a binary text classification task, our implementation was validated against the benchmark LIME library.

We then extended the replication to conduct a novel comparative analysis, revealing divergent reasoning strategies between Naïve Bayes and a Logistic Regression model.
