# Challenges in Production Machine Learning

1. **Performance on Critical Examples**  
   - Average test set accuracy isn't always sufficient for production.  
   - Certain examples, like **navigational queries** in web search, are disproportionately important and require flawless performance.  
   - Adjusting example weights can help but might not fully address these challenges.

2. **Fairness and Key Dataset Slices**  
   - Machine learning systems must avoid biases or discrimination in key slices, such as based on **protected attributes** (e.g., gender, ethnicity).  
   - High average accuracy isn't acceptable if it causes issues like unfair product recommendations or unequal treatment of user groups.  
   - Slice-based error analysis is crucial for identifying and addressing these problems.

3. **Handling Rare Classes and Skewed Data**  
   - Rare classes (e.g., diagnosing a rare medical condition) may be ignored by models optimized for overall accuracy.  
   - Algorithms must perform well on rare, critical cases even if their impact on average accuracy is small.  
   - Skewed data distributions demand specialized strategies to ensure reliable performance.

### Insight:  
- Achieving high test set accuracy is just the starting point.
- Effective machine learning engineers prioritize solving the actual application or business needs, addressing challenges beyond simple metrics. 
- Tools like error analysis and slice-based evaluations are essential for real-world success.
