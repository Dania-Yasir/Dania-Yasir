# Hi, I'm Dania Yasir

I turn real-world data into useful predictions and clear business insights using machine learning and data analytics.

I'm an AI student at the Arab Open University (GPA 4/4) and a Machine Learning Engineer Intern at FlyRank AI.

**Portfolio:** [dania-yasir.github.io/my-portfolio](https://dania-yasir.github.io/my-portfolio/)
**Open to:** interviews for AI, machine learning, and data roles.

---

## Selected projects

### Search Impressions Decline Prediction
*FlyRank AI internship*

Predicts which content pages will lose search performance. Built on Google Search Console and GA4 data.

- My model ranked the 100 pages most likely to decline. **78% of them did decline, against a 46% baseline** (Precision@100, held-out test set).
- I defined the decline threshold and built the features.
- I validated with GroupKFold by client ID. Pages from the same client look alike, so a random split would leak information between folds and inflate the score.
- My first model scored 0.496 balanced accuracy. That is chance level. I kept it in the write-up because it shows why the validation setup matters.
- Honest note: the test set has only a small number of clients, so the 78% could move with a different draw.

**Tools:** Python, Jupyter, Google Search Console, GA4

[Case study](#) · [Code](#)

### Freight Rate Regression
*Spotter assessment*

Predicts freight rates from a dataset split by time.

- One model (HGB, absolute error loss) scored best on paper. Its predictions were flat and ignored the date.
- Another (HGB, squared error loss) scored worse, but it used the time patterns in the data.
- I chose the second one. A model that ignores time is not useful for a time-based problem, even with a better score.

**Tools:** Python, Jupyter, ReportLab (PDF report)

[Write-up](#) · [Code](#)

### Sales Performance Dashboard
*Excel / Power BI*

Analyses thousands of orders across customers, regions, and years.

- Technology is the top category.
- The West is the strongest region.
- Sales trend upward from 2014 to 2017.

[Dashboard](#)

### Call Center Dashboard
*Power BI and Excel*

Looks at the operational factors that affect call center performance.

<!-- TODO: add 1-2 concrete findings with numbers before publishing -->

[Dashboard](#)

---

## What I work with

Python · Jupyter · Machine learning (classification and regression) · Feature engineering · Model validation · Power BI · Excel

