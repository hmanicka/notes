### Raising HLP

#### 1. **Human-Level Performance (HLP) as a Reference in Machine Learning**
   - HLP is useful for benchmarking how well a model performs relative to human decision-making.
   - In cases where ground truth is externally defined (e.g., medical biopsies), HLP provides a reliable baseline for irreducible error.
   - When ground truth is based on human labeling, HLP measures consistency among human labelers rather than a true gold standard.

#### 2. **Impact of Inconsistent Labeling on HLP and Model Performance**
   - Low HLP often results from inconsistent labeling instructions rather than inherent human error.
   - Standardizing labeling criteria (e.g., defining a specific threshold for defects) can significantly improve consistency.
   - Raising HLP by improving labeling standards results in cleaner data, ultimately benefiting model accuracy.

#### 3. **HLP's Role in Error Analysis and Data Quality Improvement**
   - Measuring HLP helps identify gaps in data consistency and areas for process improvement.
   - If HLP is much lower than 100%, it signals a need to refine labeling standards to reduce ambiguity.
   - While improving HLP makes it harder for a model to "beat" humans, it leads to better data and more reliable predictions in real-world applications.
