### Skewed Data sets

1. **Skewed Datasets and Raw Accuracy**: 
   - Skewed datasets, where positive and negative examples are imbalanced (e.g., 99% negatives), can lead to misleading high accuracy when using a simple algorithm that always predicts the majority class. In such cases, raw accuracy isn't a reliable metric.

2. **Confusion Matrix, Precision, and Recall**: 
   - A confusion matrix is used to evaluate the performance of algorithms on skewed datasets, highlighting the number of true positives, true negatives, false positives, and false negatives. Precision and recall are more informative than raw accuracy: precision measures how many predicted positives are true, while recall measures how many actual positives were identified.

3. **F1 Score and Multi-Class Classification**: 
   - The F1 score is a combined metric that balances precision and recall, especially when there's a trade-off between the two. It's particularly useful for comparing models and prioritizing defects or rare classes in multi-class classification, such as detecting different types of smartphone defects, where accuracy alone may be misleading.
