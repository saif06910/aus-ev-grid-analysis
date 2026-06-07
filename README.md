# Australian EV Adoption & Grid Impact Analysis

An analysis of how Australia's growing electric vehicle fleet is changing demand on the electricity network — how many EVs are on the road, when they charge, and what that means for the grid by 2030.

---

## What this project covers

- EV registrations across all Australian states from 2019 to 2024
- Monthly sales trends and market share growth
- When EVs actually charge during the day — and why the timing matters
- How EV charging stacks on top of existing evening demand peaks
- What the grid needs to handle it by 2030

---

## Key finding

Most EV owners charge at home between 5 and 9 PM — the same window when electricity demand is already at its daily peak. By 2030, this adds around 200 MW of extra load to NSW's evening peak. If charging is managed smartly using battery storage at substations and time-of-use pricing, that impact can be reduced by about 40%.

---

## Results

| | 2024 | 2027 | 2030 |
|---|---|---|---|
| NSW EV fleet | 98,700 | ~210,000 | ~650,000 |
| Market share | ~12% | ~25% | ~40% |
| Extra evening load (unmanaged) | ~28 MW | ~96 MW | ~200 MW |
| Extra evening load (with smart charging) | ~17 MW | ~58 MW | ~120 MW |

---

## How to run

```bash
pip install -r requirements.txt
jupyter notebook Australian_EV_Grid_Analysis.ipynb
```

---

## Data sources

- EV Council Australia — Annual EV Sales Reports
- ABS Motor Vehicle Census (2019–2024)
- AEMO NEM demand statistics — NSW
- VFACTS monthly vehicle sales data

---

## Stack

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn