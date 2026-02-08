Task:
Identify and handle edge cases in a dataset where some values violate domain expectations.

Plan:
1. Define what values are considered valid for the feature
2. Identify values that fall outside expected ranges
3. Decide how to handle these cases without harming data integrity

Actions:
- Inspect the dataset for negative, zero, or missing values
- Compare these values against domain assumptions
- Categorise invalid and missing values as edge cases

Tool Use:
Tool: Data inspection
Input:
A numeric feature where values are expected to be positive

Observed Issues:
- Negative values (e.g., -5, -20)
- Zero values where zero is not meaningful
- Missing or null values

Final Answer:
Negative, zero, and missing values are treated as edge cases when they violate domain assumptions. These values are not typical but can appear due to data collection or logging issues. Explicit handling is required to prevent misleading analysis or model behaviour.

Reflection:
Ignoring edge cases can introduce errors or bias into downstream processes. Clearly identifying and justifying how these cases are handled improves robustness and transparency in data-driven systems.
