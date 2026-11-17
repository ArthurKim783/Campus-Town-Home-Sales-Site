# Home prices in college towns

This site compares median home sale prices across 18 U.S. college towns for people interested in housing costs near a university campus.

## Live site

https://arthurkim783.github.io/Campus-Town-Home-Sales-Site/

## Data notes

The page reads `data/college_town_home_sales.csv` and groups completed sales by city and state. It excludes 40 sales priced below $10,000, leaving 35,402 sales across 18 cities. The chart and table show each city's median `sale_price`, rounded to the nearest whole U.S. dollar; half-dollar medians round up. No other sale rows are excluded. The cutoff addresses the implausible low prices described in the data description sheet; all values are as reported by the collection source.

## Tools we used

OpenAI Codex assisted with the data analysis and page implementation. The site uses plain HTML, CSS and JavaScript, with no external libraries. GitHub Pages hosts the site.

## Citation

College-town home sales dataset, version 1.0 (2026). University of Illinois-Deloitte Foundation Center for Business Emerging Technologies. Data collected March 2026.

## Who did what

Arthur Kim chose the question, reviewed the work and confirmed the live page. Codex read the project instructions and data description sheet, calculated the city medians from the CSV, and implemented the chart and table.
