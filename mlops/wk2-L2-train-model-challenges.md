# Challenges in Training Machine Learning Models

## Framework for ML Systems
- **Components**: Machine learning systems involve both **code (algorithm/model)** and **data**.
- **Emphasis Shift**:
  - Historically: Focused on improving the algorithm/model.
  - Now: Customizing data is often more critical for specific applications.
  - Many cases involve using existing models and focusing efforts on data improvement.

---

## Process of Building a Machine Learning System
1. **Inputs**:
   - **Code**: Algorithm or model.
   - **Data**: Dataset for training.
   - **Hyperparameters**: Tuning variables like learning rate, regularization, etc.
2. **Output**:
   - Trained model capable of making predictions.

### Iterative Development Loop:
1. Start with a model, hyperparameters, and data.
2. Train the model.
3. Perform **error analysis**:
   - Identify improvements for the model, hyperparameters, or data.
4. Repeat until performance is satisfactory.
5. Final **error analysis and audit** before deployment.

---

## Why Model Development is Hard
- Requires multiple iterations of:
  1. **Error Analysis**.
  2. **Strategic Modifications** to code, data, or hyperparameters.
- Balances empirical testing with good decision-making at each iteration.

---

## Key Milestones in ML Projects
1. **Training Set Performance**:
   - Ensure the model fits the training data well.
   - Example: For housing prices, can the model fit a simple line to training data?

2. **Validation Set (Dev Set) & Test Set Performance**:
   - After succeeding on the training set, ensure generalization to holdout datasets.

3. **Business Metrics Alignment**:
   - High test set accuracy is not enough; the model must meet the project's business or operational goals.
   - Misalignment can cause friction between ML and business teams.

---

## Challenges Beyond Low Test Set Error
- Achieving low test set error doesn't always translate to project success.
- **Common Issues**:
  - Mismatch between technical metrics (e.g., accuracy) and business metrics.
  - Addressing specific project needs requires spotting and solving these mismatches.

---

### Takeaways:
- Think of ML development as a **cycle** involving:
  1. Input (data, code, hyperparameters).
  2. Training.
  3. Analysis and iteration.
- Focus not just on the **algorithm**, but on customizing **data** for specific applications.
- Align technical success with **real-world project goals**.
