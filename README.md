# A-Data-Analysis-of-Your-Own
Deaths in Armed Conflicts on territory of Ex-Yugoslavia (1991-1995 &amp; 1998-1999)

This project analyzes deaths in armed conflicts in Bosnia and Herzegovina, Croatia, Serbia, Montenegro, and Kosovo, focusing on the periods 1991–1995 and 1998–1999. The analysis uses data from Our World in Data and Python libraries to explore death tolls by country and over time.

## Dataset

Source: [Our World in Data - War and Peace](https://ourworldindata.org/war-and-peace)

If the dataset is not included in the repository, it can be downloaded directly from the source link above.

## How to run the analysis

1. Open `https://colab.research.google.com/drive/1G2QzkAWxuW-w6OWNyqe1vxUfCnfYXqTI?usp=sharing` using **Google Colab**.
2. Run the cells step by step to reproduce the analysis and visualizations.
3. If you want to se all visualizations you just need to copy/paste link for google colab and upload CSV file.
4. You are able to download csv file on this link: (https://ourworldindata.org/war-and-peace)
## Project workflow

1. Load and inspect dataset
2. Filter data for selected countries (Bosnia and Herzegovina, Croatia, Serbia, Montenegro, Kosovo)
3. Filter by years of interest: 1991–1995 and 1998–1999
4. Group deaths per country and time period
5. Create visualizations:
   - Bar chart comparing total deaths per country for both time periods
   - Choropleth map showing total deaths by country
   - Line plot showing deaths per year by country
6. Interpret key findings

## Libraries used

- pandas
- numpy
- matplotlib
- seaborn
- plotly

## Key findings

- Bosnia and Herzegovina had the highest death toll in 1991–1995 (65,122 deaths)
- Croatia had 4,781 deaths in the same period
- Kosovo and Serbia had the highest death counts in 1998–1999
- Deaths in the second period were more geographically concentrated in Kosovo and Serbia
- Choropleth map highlighted Bosnia’s disproportionate death toll in the early 1990s

## New technique learned

As part of this project, I learned how to create a **choropleth map using Plotly Express**.  
I followed official documentation and tutorials to implement this technique, which helped me visualize deaths geographically in a clear and intuitive way.

## Author

Milos Sarenac
