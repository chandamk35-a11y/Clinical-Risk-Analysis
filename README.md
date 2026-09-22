# Clinical Risk Analysis (NumPy Practice)

Practicing NumPy fundamentals — summary statistics, boolean masking,
combining conditions — on a synthetic diabetes/hypertension patient dataset (1,000 rows).

**Note:** Data is synthetic, generated for practice. Not real patient data.

## What's in the notebook

- Summary stats: mean/median age, mean BMI, mean & std systolic BP
- Handling missing values with `np.nanmean` / `np.nanmax`
- Prevalence of diabetes and hypertension (boolean masking)
- Patients aged 65 and above
- Comorbidity analysis: diabetes and hypertension together (combining conditions with `&`)

## Key findings

| Metric | Value |
|---|---|
| Patients | 1,000 |
| Mean age | 51.6 years |
| Median age | 52 years |
| Mean BMI | 27.4 kg/m² |
| Mean systolic BP | 139.8 mmHg |
| Std. dev. systolic BP | 18.2 |
| Highest HbA1c | 9.1% |
| Lowest fasting glucose | 55.0 mg/dL |
| Diabetes prevalence | 15.1% (151 patients) |
| Hypertension prevalence | 50.0% (500 patients) |
| Aged 65+ | 18.3% (183 patients) |
| Diabetes + hypertension | 10.6% (106 patients) |

## Tools

Python, NumPy, pandas

## Running it

```bash
pip install numpy pandas
jupyter notebook Clinical_Risk_Analysis_cleaned.ipynb
```

Make sure `synthetic_diabetes_hypertension_patient_dataset.csv` is in the same
folder as the notebook before running.
