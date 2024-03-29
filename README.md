# Water Loss Reduction Analysis
This is a data analysis project that contributes to the identification of the factors causing pipe failures and leakage in water supply systems and utilizes Python for the analysis. The water supply system of the city of Pforzheim, Germany, is used as a case study.
## Objective
The project objective is to increase the efficiency of the planning process for the rehabilitation of water supply systems as well as defining the risk of new pipe failures. The results of the analysis are expected to enable faster and more efficient identification of the factors causing pipe failures and leakage in water supply systems, and thus, to improve the current operational practice of the water utilities.
## Key Questions
* Explore the risk factors for the occurrence of the pipe failures
* Which risk factor is the dominant one?
* Which pipe material is the most apron to failure and under which conditions?
* Spatial distribution of the pipe failures
* Is there any seasonably pattern in the occurrence of the pipe leakage?
* Forecast failures occurrence over time
## Data
1.	**Data Sourcing:**
The data were obtained by request from the municipal utility for the city of Pforzheim, Germany as a part of the research project AWaRe at the Karlsruhe Institute of Technology (KIT) and can be used only for academic or educational purposes. 
2.	**Data Contents:**
* dataset "pipelines" (originally named "leitungen.xlsx") provides essential details about the water supply pipelines, including specific characteristics like the material of the pipes, their diameter, age, and information about the environmental factors affecting the pipelines. This environmental data includes details about traffic loading, the level of groundwater, and the type of soil (considering soil aggressiveness and settlement).
* dataset "failures" (originally named "schaeden.xlsx") provides fundamental information about the pipe failures that have occurred within the water supply network. This dataset includes details about the specific pipe where the failures took place, the date when the failure was reported, and the cause or reason for the damage.
* dataset "Schadensdaten_geo" provides fundamental information about the water supply network in Pforzheim, including details such as coordinates for reported water pipe failures and the corresponding street addresses where these failures occurred.
## Tools
For this project, the following python libraries were used:
+ pandas - for data analysis
+ NumPy - mathematical library that supports a variety of operations, a dependency of pandas
+ seaborn - for visualization
+ matplotlib - a plotting library and a dependency for seaborn
+ scipy - a fundamental Python library necessary for visualizations
+ folium -  a Python library used for creating interactive leaflet maps within web applications
+ geopandas - an extension of the pandas library that provides support for geographic data types and operations
+ pyproj - is a Python interface to the PROJ library, which is used for cartographic projections and coordinate transformations
+ sklearn - is a machine learning library in Python that provides simple and efficient tools for data analysis and modeling
+ statsmodels - a Python library for estimating and testing statistical models, providing classes and functions for statistical analysis

The code is available as jupyter notebooks, under /[scripts](https://github.com/SanjaIlinSpirovska/WATER-LOSS-PROJECT_Python/tree/main/02%20Scripts)/.

## Key Competencies
1. **Data Wrangling:** This involves tasks like dropping unnecessary columns, renaming columns for clarity, and adjusting variable data types. It ensures that the data is well-organized and suitable for analysis.
2. **Data Consistency Checks:**  Identifying and rectifying mixed or incorrect data types, managing missing values, and addressing duplicates. Ensuring data quality and integrity is crucial for reliable analyses.
3. **Exploratory Analysis:** During exploratory analysis, relationships within the data are investigated. This includes employing tools like correlation matrices, heatmaps, scatterplots, as well as creating pair and categorical plots to gain insights into the underlying patterns and trends.
4. **Geographical Visualizations:** Utilizing libraries like geopandas, folium and pyproj to create various types of maps, including map with clustered markers, heatmap that and a marker map.
5. **Supervised Machine Learning:** In order to test the hypothesis, several analytical techniques were employed, including Binary Logistic Regression Analysis, implementation of the Random Forest Algorithm, and utilization of the XGBoost Algorithm.
6. **Unsupervised Machine Learning:** In testing the hypothesis, the analysis involved the application of both K-Means clustering and Agglomerative Clustering techniques.
7. **Analyzing and Forecasting Time Series Data:** The analyzing phase involves decomposing the time series, testing for stationarity, and conducting autocorrelation analysis. The forecasting phase includes defining model parameters, data splitting, model fitting, and iterative refinement for improved accuracy.

Visualizations for this project can be found on Tableau [here](https://public.tableau.com/views/WaterLossProject/WaterLoss?:language=en-US&:display_count=n&:origin=viz_share_link).
