# Introduction

In previous lectures, we have learned how models are trained and diagnosed, and how we can make learning more efficient using unlabeled data. 
In today's lecture, you are going to learn about **model inference**—the ways we can deploy predictive machine learning models and use them 
in real-world scenarios to guide experiments.

### What You'll Learn

If you have trained a machine learning model, you will quickly realize that it can produce more predictions than you could ever possibly test in the lab. 
So how do you decide which predictions to follow? What if your engineering problem has multiple parameters of interest (stability, toxicity, activity, etc.)? 
These are the questions we are addressing today:

1. **Bayesian Optimization (BO):**
    - **Model Calibration (Conformal Predictions):** How much error can I expect from my predictions?

    - **Uncertainty:** How do we deal with uncertainty (exploration vs. exploitation)?

2. **Multi-Objective Optimization:**
    - **Pareto Front:** How do we balance multiple objectives?
    - **Uncertainty:** Measuring the uncertainty of multiple objectives.

Finally, we are going to discuss the promises and limitations of model uncertainties and Bayesian optimization, along with perspectives on addressing these limitations.
