<p align="center">
  <img src="BellevueCollegeLogoHorzClr.jpg" alt="Bellevue College" height="70">
</p>

<h1 align="center">CS 310 — Python for Data Science</h1>

<p align="center">
  <strong>Bellevue College · Fall 2026</strong><br>
  Pedro Albuquerque · <a href="mailto:pedro.albuquerque@bellevuecollege.edu">pedro.albuquerque@bellevuecollege.edu</a>
</p>

---

## About the Course

This course explains the **engine** behind the newest and most powerful data science models — so that we remain **accountable** for their usage. That means being able to:

- Provide **criticism** — question model outputs instead of accepting them blindly.
- Make **adjustments** — tune and correct models when they fall short.
- Drive **innovation** — build new solutions on top of a solid understanding.

Understanding is only half of the story — we also **build**: practical Python implementations of every model we study, leveraging LLM tools and agents such as **Gemini**, working hands-on in **Google Colab** — no local setup required.

> **In one sentence:** understand the models deeply enough to **use**, **judge**, and **improve** them — with the human in charge and AI as technological support.

## Lectures

Every lecture is a self-contained Jupyter notebook. Click the badge to open it directly in Google Colab.

| # | Lecture | Topics | Open in Colab |
|:-:|:--------|:-------|:-------------:|
| 1 | [Introduction](Lecture1.ipynb) | The 4th Industrial Revolution · Data Generating Process · Supervised Learning · Loss Functions & ERM · Strong Law of Large Numbers · Uniform Convergence · VC Dimension & PAC Learning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PedroBSB/CS310/blob/main/Lecture1.ipynb) |

Each notebook includes worked **examples** with runnable code and a set of **exercises**, each accompanied by a **Suggested Gemini Prompt** you can paste into Colab's built-in Gemini assistant.

## Getting Started

**Option 1 — Google Colab (recommended).** Click a Colab badge above. Everything runs in the browser; no installation needed.

**Option 2 — Run locally.**

```bash
git clone https://github.com/PedroBSB/CS310.git
cd CS310
pip install numpy pandas matplotlib scipy jupyter
jupyter notebook
```

To load a dataset from this repository inside any notebook (works in Colab and locally):

```python
import pandas as pd
url = "https://raw.githubusercontent.com/PedroBSB/CS310/main/Data/College.csv"
college = pd.read_csv(url)
```

## Datasets

The [`Data/`](Data) folder contains all datasets used in lectures, exercises, and assignments. Most come from *An Introduction to Statistical Learning* (James, Witten, Hastie, Tibshirani).

| Dataset | Description |
|:--------|:------------|
| `Advertising.csv` | Sales vs. TV, radio, and newspaper advertising budgets |
| `AirPassengers.csv` | Classic monthly airline passengers time series (1949–1960) |
| `Auto.csv` / `Auto.data` | Gas mileage, horsepower, and other specs for 392 vehicles |
| `Bikeshare.csv` | Hourly usage of a bike sharing program in Washington, DC |
| `Boston.csv` | Housing values and neighborhood attributes in Boston suburbs |
| `BrainCancer.csv` | Survival times for patients with primary brain tumors |
| `Caravan.csv` | Caravan insurance purchases with 85 customer attributes |
| `Carseats.csv` | Simulated child car seat sales at 400 stores |
| `Ch12Ex13.csv` | Gene expression data for unsupervised learning exercises |
| `College.csv` | Statistics for 777 US colleges (applications, tuition, graduation rate) |
| `Credit.csv` | Credit card balance and customer demographics |
| `CreditCard.csv` | Credit card applications and spending behavior |
| `Default.csv` | Simulated credit card default data |
| `Fund.csv` | Returns of 2,000 fund managers over 50 months |
| `Heart.csv` | Cleveland Clinic heart disease diagnostic data (303 patients) |
| `Hitters.csv` | Major League Baseball player statistics and salaries |
| `Income1.csv` / `Income2.csv` | Simulated income vs. education (and seniority) |
| `OJ.csv` | Orange juice purchase choices (Citrus Hill vs. Minute Maid) |
| `Portfolio.csv` | Simulated asset returns for portfolio risk estimation |
| `Publication.csv` | Time to publication of clinical trial results |
| `Smarket.csv` | Daily S&P 500 returns, 2001–2005 |
| `Wage.csv` | Wages and demographics for male workers in the Mid-Atlantic |
| `Weekly.csv` | Weekly S&P 500 returns, 1990–2010 |
| `Customers.csv` / `Orders.csv` / `Products.csv` / `Location.csv` | Relational retail tables for pandas joins and aggregation |
| `bank_transactions.csv` | Bank transaction records for large-scale data wrangling |
| `marketing_campaign.csv` | Customer personality and campaign response data |
| `acsi_data.csv` | American Customer Satisfaction Index survey data |
| `bfi.csv` | Big Five personality inventory (25 items) for factor analysis |

## Using AI in This Course

You are encouraged to use **Gemini** (and other LLM tools) throughout this course — that is part of the point. But two failure modes must be avoided:

1. **Fear:** rejecting AI and losing its power as a tool.
2. **Blind delegation:** handing all reasoning and responsibility to the machine.

> *"A computer can never be held accountable, therefore a computer must never make a management decision."*
> — IBM internal training manual, 1979

Run, read, and criticize every line of AI-generated code before you submit it. Accountability — legal, ethical, and professional — always rests with the **human** who acts on the outputs.

---

<p align="center">
  <sub>CS 310 · Python for Data Science · Bellevue College</sub>
</p>
