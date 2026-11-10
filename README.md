# My First Python Data Project: Influencer Marketing

An exploratory data analysis of 150,000 influencer marketing campaigns, made with Python and pandas.

## Goal

Find out which platforms, influencer categories and campaign types bring the most sales.

## Dataset

The dataset file is included in this repository. Original source: [Influencer Marketing ROI Dataset](https://www.kaggle.com/datasets/tfisthis/influencer-marketing-roi-dataset) by tfisthis on Kaggle, licensed under [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

150,000 campaigns with platform, influencer category, campaign type, start and end dates,
engagements, estimated reach and product sales.

## Tools

Python · pandas · Matplotlib · SciPy · Google Colab · Claude (AI assistant)

## Project Structure

| Part | What I did |
|---|---|
| 1. Load the Data | loaded the CSV file from Google Drive |
| 2. First look | explored columns, data types and summary statistics |
| 3. Basic checks | checked missing values, duplicates and unique IDs |
| 4. Most used platforms | counted campaigns by platform |
| 5. Top selling groups | compared average sales by platform, category and campaign type |
| 6. Additional Exploration (AI-Assisted) | checked dates, distributions, correlations, statistical significance, and wrote a reusable data quality function |

## Key Findings

1. **Most used platform:** Instagram (~40% of campaigns), then YouTube (30%), TikTok (20%) and Twitter (10%).
2. **Best performers:** none. Average sales are around 2,500 for every platform, category and campaign type,
   and a statistical test (ANOVA, all p-values > 0.4) shows the small differences are random.
3. **Data quality:** some values are unusual start dates go up to the year 2432, there is one campaign per day,
   and about 5% of campaigns have more engagements than reach. Sales are spread evenly and show no relationship
   with engagement. This suggests the data may be simulated, so it is better suited for practice than for
   real marketing decisions.
<img width="635" height="374" alt="image" src="https://github.com/user-attachments/assets/b2df0714-380d-4063-8390-9f8acba885a0" />
<img width="628" height="393" alt="image" src="https://github.com/user-attachments/assets/a1693eeb-dc04-400d-980e-85d065d9d499" />


## What I Learned

- Loading and exploring a dataset using pandas
- Checking data quality (missing values, duplicates, unusual values)
- Grouping data and calculating summary statistics
- Creating visualizations with Matplotlib
- Using a statistical test to evaluate differences
- Interpreting results and recognizing the limitations of a dataset
- Structuring a notebook with Markdown
- Using an AI assistant (Claude) to explore the data in more depth

## How to Run

1. Open `influencer_marketing_analysis.ipynb` in Google Colab.
2. Run all cells (Runtime → Run all) — the dataset is loaded directly from this repository.
