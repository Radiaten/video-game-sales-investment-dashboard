# Video Game Sales Investment Dashboard

## Overview
An interactive Tableau dashboard analysing 64,000+ video game sales records (1980-2024) to answer investment-relevant questions about genre performance, critical reception, sales trends, and regional publisher dominance. This dashbaord was built for a business-development investor persona.

## Approach
Design decisions were grounded in visualisation theory rather than Tableau's defaults. The chart types were chosen and justified against Mackinlay (1986), Bertin's semiology of graphics, Few's time-series principles, and Shneiderman's visual information-seeking mantra, following a paper-landscape design phase before any implementation.

## Key Findings
- Sports and Action dominate global sales, but regional composition varies sharply by genre (e.g. Role-Playing games over-index in Japan).
- Critic score explains only ~3% of sales variance (R² = 0.03), a weak commercial predictor, challenging a naive investment assumption.
- Sales peaked 2007-2009 (Wii/DS boom); post-2010 decline likely reflects a shift to digital distribution, not market contraction.
- Publisher-console dominance differs by region. The top performers in North America aren't the same as in Japan or Europe.

## Interactivity
A Dashboard Filter Action connects the genre sales chart to a publisher-console heatmap; a region parameter lets the analyst switch between NA/JP/PAL views live.

## Dashboard
<img width="1920" height="1080" alt="Dashboard_Overview" src="https://github.com/user-attachments/assets/3ada6c26-91b6-4184-bbce-1a58938da17b" />

## Tools
Tableau Desktop, R

## Files
- `Data Analysis/Dataset_Clean.Rmd` - R File which contains code for cleaning the dataset
- `Report/Report.pdf` — full design rationale and walkthrough
- `Dashboard/Dashboard.twbx` — Tableau workbook
- `Images` - Screenshots of all the individual dashboard images

## Data Source
[Video Game Sales & Industry Data, 1980–2024 (Kaggle)](https://www.kaggle.com/datasets/bhushandivekar/video-game-sales-and-industry-data-1980-2024)
