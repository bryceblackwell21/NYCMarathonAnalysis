# 🏃‍♂️ TCS 2024 NYC Marathon Analysis

An analysis of runner data from the 2024 TCS NYC Marathon, focusing on split times, demographics, and course challenges. This project combines web scraping techniques with data visualization to uncover insights about runner performance across different sections of the course.

## Project Goal
To analyze split data from the 2024 NYC Marathon, identifying key trends across runner demographics and course sections. This analysis also highlights insights such as the impact of "the wall" at mile 18 and identifies the most challenging parts of the course. This project holds personal significance as I ran the 2024 TCS NYC Marathon with Fred's Team to support my mother in her fight against breast cancer. You can read more about my fundraising efforts and support the cause [here](http://mskcc.convio.net/goto/bryceb-marathon). My bib number was 45520 if anyone wants to compare runs. 😃

## Insights
- **Runner Demographics**: Trends in performance based on age, gender, and pace groups.
- **Course Challenges**: Analysis of split times reveals difficult sections like "the wall" at mile 18 but also the uplifting impact of the charity mile and the finish.
- **Wave and Borough Analysis**: Visualization of how runners in the earlier waves did not always translate to faster finishes as well as what was the fastest borough (spoiler - it was Brooklyn).

## Data Set
- **Source**: Data scraped from the New York Road Runners website using Beautiful Soup and Selenium.
- **Sample Size**: Due to scraping constraints, data for 10,000 runners was collected, focusing on key demographics and split times.
- **Privacy Note**: All runner names were intentionally excluded, with data organized by bib number for privacy. Names can still be searched for on New York Road Runners for cross-reference.

## Tech & Skills

| Tool            | Description of Use                                                                                    | Skills Demonstrated                       |
|-----------------|-------------------------------------------------------------------------------------------------------|-------------------------------------------|
| Python (Beautiful Soup) | Extracted HTML content to retrieve runner information, split times, and demographics from the website. | Web scraping, data extraction             |
| Python (Selenium)       | Automated browser interactions to handle dynamic page loading and capture runner data.                 | Web automation, handling dynamic content  |
| Tableau                 | (nycmarathonviz - To be added) Visualized split trends and course analysis to uncover insights.        | Data visualization, trend analysis        |

## Files in This Repository
- **NYC-Marathon-Scraper.ipynb**: Jupyter notebook for scraping runner data from New York Road Runners using Beautiful Soup and Selenium.
- **ny_marathon_results.csv**: CSV file containing the scraped and processed runner data.
- **nycmarathonviz**: Tableau workbook file for data visualization (to be added).

## Analysis & Visualizations
The final analysis and visualizations focus on:
1. **Split Time Trends**: Visual comparisons of split times across demographics.
2. **Course Difficulty**: Identification of challenging course segments, including the effects of “the wall” at mile 18.
3. **Runner Insights**: Additional observations on runner performance and pace fluctuations.

This project highlights both the technical and analytical aspects of gathering and interpreting marathon data, making it a meaningful exploration for both personal reflection and public insights.
