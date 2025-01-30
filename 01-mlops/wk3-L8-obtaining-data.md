### Obtaining Data

#### 1. **Efficient Data Collection Strategies**
   - Machine learning is an iterative process; quickly obtaining an initial dataset is crucial.
   - Avoid spending excessive time collecting data before training an initial model.
   - A practical approach is to set a short, fixed time (e.g., 7 days) to collect initial data and iterate from there.
   - Exceptions exist for well-known domains where prior experience indicates a minimum data requirement.

#### 2. **Evaluating and Selecting Data Sources**
   - Inventory potential data sources, considering cost, time, and feasibility.
   - Common data sources include owned datasets, crowdsourced recordings, transcribed audio, or purchased data.
   - Weigh trade-offs between financial cost, time investment, data quality, and regulatory/privacy constraints.
   - Structured decision-making can help balance speed and effectiveness in data acquisition.

#### 3. **Data Labeling and Dataset Scaling**
   - Choose the appropriate labeling strategy: in-house, outsourced, or crowdsourced.
   - Machine learning engineers labeling data initially can build intuition but isn't scalable long-term.
   - Specialized tasks (e.g., medical imaging) require subject matter experts for accurate labeling.
   - When expanding datasets, avoid increasing size by more than **10x** at a time to allow for iterative learning and error analysis.
