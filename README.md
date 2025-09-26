# Nobel-Prize-Winners-Analysis
This project analyzes Nobel Prize winner data to identify patterns in gender, birth country, decades, female laureates, first woman laureate, and repeat winners using Python &amp; Pandas.
---

## Key Insights

* **Top Gender:** `top_gender`
* **Top Birth Country:** `top_country`
* **Decade with highest US-born ratio:** `max_decade_usa`
* **Most female laureates (decade & category):** `max_female_dict`
* **First female laureate:** `first_woman_name`, Category: `first_woman_category`
* **Repeat winners:** `repeat_list`

---

## Methodology

* Loaded data from `data/nobel.csv`.
* Created flags: `usa_born_winner`, `female_winner`, and `decade`.
* Grouped data to calculate proportions and identify key patterns.
* Visualized trends with **Seaborn** (optional).

---

## Project Structure

```
nobel-prize-analysis/
├── data/nobel.csv
├── notebooks/nobel_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## Requirements

* Python 3.x
* pandas, numpy, seaborn

Install with:

```bash
pip install pandas numpy seaborn
```

---

## Usage

```python
import pandas as pd
import numpy as np
import seaborn as sns
nobel = pd.read_csv('data/nobel.csv')
# Compute analysis variables as described
```
