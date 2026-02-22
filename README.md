# Netflix Content Portfolio Analysis: Mix, Genres, and Release Timing

## Overview
This project analyzes Netflix’s public catalog metadata to identify strategic shifts in content mix (Movies vs TV Shows), genre concentration, and release timing (lag between release and platform addition). The goal is to translate descriptive EDA into actionable portfolio insights for content strategy and acquisition teams.

## Key Findings (Highlights)
- TV Shows account for a growing share of new additions in recent years, indicating a retention-driven portfolio shift.
- A small number of genres dominate annual additions, increasing concentration risk.
- Release lag varies materially by type and genre, reflecting mixed sourcing strategies (near-release vs back-catalog licensing).

## Recommendations
- Prioritize near-release acquisition for serialized content and time-sensitive genres.
- Maintain core genre investment while incubating emerging categories to diversify portfolio risk.
- Periodically reassess ROI on long-lag licensed content in saturated genres.

## Methods
- Data cleaning and feature engineering in Python (pandas, matplotlib).
- Normalized multi-label fields (genres, countries).
- Time-series analysis of annual additions and portfolio mix.
- Release lag estimated using release year as a proxy (Jan 1 assumption).

## Limitations
- No engagement, viewership, or revenue data.
- Release dates approximated.
- Public metadata quality varies by region and time period.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/netflix_analysis.ipynb
