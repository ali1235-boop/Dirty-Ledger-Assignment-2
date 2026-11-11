# AI Use Log and Reflection

## AI assistance
I used AI assistance to:
- Understand the dataset inspection process.
- Identify missing and duplicate records.
- Convert the price column into numeric format.
- Standardize inconsistent product names.
- Flag suspicious values for further review.

## Decisions and verification

| Issue | Decision |
|---|---|
| Missing price | Kept missing; did not invent a value |
| Duplicate row | Removed exact duplicate |
| Product label | Standardized capitalization |
| Price 9999 | Retained and flagged for verification |
| Price format | Converted to numeric |

## Reflection
This assignment taught me that cleaning data is not simply deleting unusual values. Each decision needs a reason. I learned to inspect missing values, duplicates, inconsistent labels, and extreme observations before using a dataset for analysis.

The value 9999 remains unverified and should not be treated as a confirmed market price. The dataset is illustrative and cannot be used to make claims about actual Pakistani prices.

AI helped me understand the Python steps, but I needed to inspect the results and make decisions about how to handle the data.
