### Balanced train/dev/test splits

#### 1. **Balanced Data Splitting for Small Datasets**
   - Randomly splitting small datasets can lead to unrepresentative train, dev, and test sets.
   - A balanced split ensures that each subset maintains the same proportion of positive and negative examples.
   - This technique improves the reliability of model evaluation, reducing variability caused by uneven distributions.

#### 2. **Random Splitting Works for Large Datasets**
   - When working with large datasets, a random split is generally representative of the overall data distribution.
   - The probability of major deviations in class proportions decreases as dataset size increases.
   - Explicit balancing is unnecessary in such cases, as random splits naturally approximate the true distribution.

#### 3. **Balanced Splits Improve Model Performance for Small Data**
   - A balanced train-dev-test split provides a more reliable measure of model performance.
   - Helps avoid misleading evaluation results caused by disproportionate class distributions.
   - Especially beneficial when working with limited data, ensuring fair model comparison and validation.
