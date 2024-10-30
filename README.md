This analysis is based on a comprehensive global energy dataset covering the years 2000 to 2020. 

The dataset covers areas including (clean)
energy and economic factors, along with geographic and demographic data for countries. 

This project focuses on examining global energy
trends, with an emphasis on identifying disparities and opportunities for future investments. The analysis addresses three key research
questions: 

1. How has access to electricity and clean cooking fuels evolved from 2000 to 2020 across selected categories? And what is the
potential for these access to grow by categories? To answer this, time-series data on energy access was analyzed across selected (transformed)
features. Feature engineering and visualization techniques were used to provide insights into the regions with the greatest disparities in access
and those making the most progress, helping to inform policy and investment priorities.

2. How does electricity composition vary across
regions? Can additional features help cluster countries into meaningful categories? Focusing on electricity composition across regions, KMeans
clustering was applied using additional features such as electricity sources, CO2 emissions, GDP growth, and geographic factors. The clustering
analysis identified distinct country groups with common opportunities and challenges.

3. How have developing countries that receive financial
aid for renewable energy development performed? The analysis assessed the situation of receiving countries, investigating the impact of past
financial aid on renewable energy growth using OLS regression while considering GDP per capita and energy intensity. In addition, Lasso and
Random Forest models were employed to predict future renewable energy shares, capturing both linear and non-linear patterns in the data.

This project is organized into three parts: Part 1 provides an introduction which outlines the research questions, Part 2 presents the code and
detailed analysis, and Part 3 concludes by summarizing the key findings and insights drawn from the analysis.

Please note, in the preview mode, my "Average Energy Access by Region, Land Area, and Population Density Cluster (2020)" spectrum blue heatmap, at the section 2.3.1B Investment Potential, is not displaying the colors correctly. I have also attached a screenshot of my blue heatmap called "Blue Heatmap.JPG" for reference.
