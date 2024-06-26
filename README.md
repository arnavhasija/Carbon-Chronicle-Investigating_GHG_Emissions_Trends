# Carbon-Chronicle-Investigating_GHG_Emissions_Trends
The objective of this project is to analyze trends in CO2 and greenhouse gas emissions worldwide by creating data visualizations using the dataset provided by Our World in Data

<h2>Introduction</h2>

Climate change is one of the most pressing challenges of our time, and understanding global greenhouse gas emissions trends is crucial for developing effective mitigation strategies. Our World in Data provides a comprehensive dataset on CO2 and greenhouse gas emissions, encompassing various metrics such as annual emissions, per capita emissions, and cumulative emissions. This project aims to analyze this dataset to gain insights into global emissions patterns, identify key contributors to emissions, and assess the impact of emissions on climate change.

<h2>Objective</h2>

The primary objective of this project is to analyze trends in CO2 and greenhouse gas emissions worldwide using the dataset provided by Our World in Data. Specific objectives include:

- Examining trends in annual CO2 emissions and assessing the factors driving these trends.
- Analyzing per capita emissions to understand the distribution of emissions across different countries.
- Investigating cumulative emissions to assess historical contributions to the global carbon budget.
- Exploring the relationship between emissions and other socio-economic factors such as population, GDP, and energy consumption.
- Assessing the impact of emissions on global temperature change and climate variability.

<h2>Approach</h2>

<b>Data Acquisition:</b> The dataset used for this analysis is sourced from Our World in Data, providing comprehensive data on CO2 emissions, other greenhouse gases, and related metrics across various countries and years.

<b>Data Exploration with SQL Queries:</b> SQL queries are utilized to explore and manipulate the dataset, enabling me to calculate aggregate metrics, extract relevant subsets of data, and perform calculations such as cumulative emissions over specific time periods. This approach allows for efficient data processing and enables us to derive meaningful insights from the dataset.

<b>Data Visualization:</b> The processed data is visualized using Matplotlib to create insightful charts and graphs. Visualizations such as time series plots, bar charts, and heatmaps are employed to illustrate emission trends, compare emissions across countries, and visualize historical contributions to the global carbon budget. These visualizations provide a clear and intuitive representation of the data, facilitating easier interpretation and understanding of the trends.

<b>Analysis and Interpretation:</b> Through the combination of SQL queries and data visualizations, I will analyze the trends in annual CO2 emissions, assess factors driving these trends, and explore variations in emissions across different countries and regions. Additionally, I will investigate historical contributions to the global carbon budget, identifying countries with the highest cumulative emissions over specific time periods.

<h2>Exploratory Data Analysis</h2>

The graph below shows the trend of CO2 emissions from 1920 to slightly beyond 2020. Overall there has been a significant increase in emission levels over the last century. In addition, there is a noticeable increase in emissions starting around the year 1960, which correlates with the post-industrial era, characterized by rapid industrialization and increased use of fossil fuels. It is important to understand the underlying factors contributing to the rise in emissions which could involve exploring the impact of economic growth, energy consumption patterns, and technological advancements on CO2 emissions.

<p align="center">
  <br>
  <img src="/images/img3.JPG">
</p>

Next, I also looked at the total CO2 emissions by country and emission type as shown in the chart below. The USA and China dominate the emissions landscape, with the USA’s consumption-based emissions standing out in orange. The energy-intensive industries like steel, cement, and chemicals in the US, emit substantial CO2 during production. China on the other hand, is the world’s largest manufacturing hub, producing goods for global markets. Its production-based emissions stem from industrial processes, including steel, cement, and textiles. Russia’s vast land area and natural resource wealth contribute to its production of oil, gas, and metals.

<p align="center">
  <br>
  <img src="/images/img2.JPG">
</p>

The donut chart below illustrates the contribution of various sources to the total CO2 emissions. Consumption is the largest contributor, accounting for 34% of the emissions. This category likely includes emissions from everyday activities, such as transportation, household energy use, and industrial processes. Areas with higher population density tend to have more consumption-related emissions due to increased energy demand. Coal follows closely, contributing 31%. Coal-fired power plants and industrial processes are major sources of CO2 emissions in this category. Countries heavily reliant on coal-based power plants have higher coal-related emissions, and industries like steel and cement rely on coal for production. Oil accounts for 22%, primarily from transportation (gasoline and diesel), industrial processes, and petrochemicals and refineries that rely on oil. Natural gas contributes 10% and is used for electricity generation, heating, and industrial applications. Cement production and flaring make up smaller portions, while trade-related emissions are also present.

<p align="center">
  <br>
  <img src="/images/img4.JPG">
</p>
