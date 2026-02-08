Task:
Decide how to handle missing and invalid values during the data cleaning process.

Plan:
1. Identify which values are missing or invalid
2. Understand why these values may have occurred
3. Decide on a cleaning strategy that preserves useful information

Actions:
- Inspect the dataset to locate null or missing values
- Identify invalid values such as negative or zero entries where only positive values are expected
- Separate true missing values from clearly invalid data points

Tool Use:
Tool: Data inspection
Input:
A dataset containing numeric features expected to have positive values

Observed Issues:
- Missing (null) values in some records
- Negative values where negatives are not meaningful
- Zero values that violate domain assumptions

Final Answer:
Missing and invalid values require different handling strategies. Missing values may be imputed, flagged, or removed depending on their frequency and importance. Invalid values that violate domain rules should be corrected if possible or excluded to avoid misleading analysis.

Reflection:
Cleaning decisions directly affect model behaviour. Treating all anomalies the same can reduce data quality, while careful differentiation improves reliability and transparency.