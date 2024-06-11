# 🎧 Taylor Swift Ph Spotify Charts Analysis 🎧

Deck summary in [Canva](https://www.canva.com/design/DAGFcSED0tk/1Bd-V55FyC5EL3pwMvCT-g/view?utm_content=DAGFcSED0tk&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## ✍️ Overview
This repository contains code and documentation for an analysis project on Taylor Swift's Spotify Charts behavior on the artist's news and announcements.
Case Study: Carmi, a devoted fan of Taylor Swift, embarked on a data analysis project to investigate the impact of Taylor Swift's actions and announcements on streaming activities. 

## 📂 Project Structure
- `analysis/`: Contains the files used for Analysis.
- `excel files/`: Contains the raw and summarized files for Taylor Swift's Spotify Charts.
- `notebooks/`: Contains the .ipynb files used for summarizing the tables and analysis.
- `README.md`: This files, provides an overview of the project.
  
## 🎯 Objectives
- Analyze streaming activity data to discern patterns and correlations with Taylor Swift's actions and announcements.
- Evaluate the influence of Taylor Swift's activities on streaming behavior.

##  📃 Data Collection
- Source: JC Peralta on [Kaggle](https://www.kaggle.com/datasets/jcacperalta/spotify-daily-top-200-ph?resource=download)
- Scope:
    - Spotify Daily Top 200 Tracks in the Philippines
    - January 01, 2017 to October 15, 2023
- Tool(s): Tableau, Google Colaboratory, Microsoft Excel
- Language(s): Python

## 🪜 Methodology
  1. Exploratory Data Analysis (EDA):
        -   Investigate the distribution and characteristics of the streaming activity data.
        -   Explore correlations between Taylor Swift's actions/announcements and streaming trends.
        -   Can be seen in `notebooks/01 initial table analysis` and `notebooks/02 eda cleaning`
  2. External Research: Conduct a research on the announcements and news on Taylor Swift
  3. Dashboard: Create charts and dashboards on the total streams and counts for better visual presentation.
  4. Statistical Analysis:
        -   Conduct statistical tests to quantify the relationship between Taylor Swift's activities and streaming behavior.
        -   Can be seen in the MS Excel file named `analysis/streams analysis excel`

## 🔎 Results and Conclusion
- Dashboard (Public Tableau Dashboard link [here](https://public.tableau.com/app/profile/ybeth.gladys.gonzaga/viz/TaylorSwiftinPHSpotifyTop200/StreamsDashboard))
- Taylor Swift is a record holder of multiple achievements in Spotify (including the most streamed artist ever) and the Philippines is no stranger to this legend who never left the PH Top 200 charts since April 26 2019.
- Top 10 Percent Change in Daily Streams:
| Top | Date       | Total Streams | % Change in Streams | Number of Songs in Top 200 | Category             | Detail                    |
|-----|------------|---------------|---------------------|----------------------------|----------------------|---------------------------|
| 1   | Jul 24 2020| "5,019,956"   | 3173.8              | 25                         | Album Release        | Folklore                  |
| 2   | Dec 11 2020| "2,989,691"   | 1425.2              | 22                         | Album Release        | Evermore                  |
| 3   | Nov 12 2021| "8,476,377"   | 1053.8              | 47                         | Album Release        | "Red (Taylor's Version)" |
| 4   | Oct 10 2022| "12,926,945"  | 955.45              | 36                         | Album Release        | Midnights                 |
| 5   | Apr 09 2021| "4,476,141"   | 924.49              | 30                         | Album Release        | "Fearless (Taylor's Version)" |
| 6   | Aug 23 2019| "2,188,177"   | 501.19              | 18                         | Album Release        | Lover                     |
| 7   | Feb 12 2021| "880,686"     | 482.66              | 10                         | Album Announcement   | "Fearless (Taylor's Version)" |
| 8   | Sep 17 2021| "324,344"     | 315.48              | 4                          | Single Release       | Wildest Dreams (Taylor's Version) |
| 9   | Jul 07 2023| "20,159,438"  | 294.69              | 56                         | Album Release        | "Speak Now (Taylor's Version)" |
| 10  | Jun 19 2021| "327,582"     | 234.58              | 10                         | Album Announcement  | "Red (Taylor's Version)"  |
  - Majority of the increases in streams are attributed to new music releases.

Almost all Taylor Swift-related news and announcements gathered had a positive relationship on her streams in the Top 200 with an average of 81.83% increase.  Among the categories, album announcements had the highest increase in streams averaging at 179.16% increase.

