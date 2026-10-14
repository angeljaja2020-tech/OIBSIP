# Titanic Dataset Cleaning

I used Python and pandas to inspect and clean the Titanic dataset.

The original dataset contained 891 rows and 12 columns. I found missing values in Age, Cabin and Embarked, but no duplicate rows.

I filled missing ages with the median, used the most common embarkation port for the two missing entries, and labelled missing cabin values as `Unknown`.

I also used the IQR method to check for unusual fares. It flagged 116 fares above the upper threshold of approximately 65.63. I kept these records because an unusual fare is not necessarily an error.

## Files

- `Titanic_Cleaning.ipynb` — the notebook containing the code and analysis.
- `Titanic_Cleaned.csv` — the cleaned dataset.

## Results

All missing values were handled, and the final dataset retains its original 891 rows and 12 columns. No duplicate rows were found.
