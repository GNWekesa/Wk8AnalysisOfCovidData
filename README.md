# Wk8AnalysisOfCovidData

# COVID-19 Data Analysis: Vaccination and Case Trends  

## Project Description  
This project analyzes global COVID-19 data to vaccination progress, case density trends, and the impact of government policies across three countries: 
**Kenya, the United States, and India**. It includes visualizations of case/death trends, vaccination coverage, and a choropleth map for case density.  

## Objectives  
1. **Data Collection**: Acquire and load a reliable COVID-19 dataset.  
2. **Data Cleaning**: Handle missing values, filter key countries, and prepare data for analysis.  
3. **Exploratory Analysis**: Visualize trends in cases, deaths, and vaccination rates.  
4. **Vaccination Insights**: Compare rollout efficiency and population coverage.  
5. **Geospatial Visualization**: Create a choropleth map for case density.  


## Tools & Libraries  
- **Python** (Pandas, NumPy)  
- **Data Visualization**: Matplotlib, Seaborn, Plotly Express  
- **Data Source**: https://www.kaggle.com/datasets/caesarmario/our-world-in-data-covid19-dataset   


## How to Run/View the Project  
1. **Prerequisites**:  
   - Python 3.x  
   - Jupyter Notebook (recommended)  
   - Install dependencies:  
     ```  
     pip install pandas matplotlib seaborn plotly jupyter  
     ```  

2. **Steps**:  
   - Download the dataset from Kaggle and place `owid-covid-data.csv` in your working directory.
   - create a new folder, in it create a virtual environment
   - run pip install notebook
   - run pip install pandas
   - run pip install matlplotlib
   - run pip install seaborn
   - Run the Jupyter notebook on vs code after installing required components or on cmd then open a local hosted web page jupyter notebook GabiAnalysisOfCovidData.ipynb: 
   - Execute cells sequentially to generate visualizations.  

3. **Outputs**:  
   - Interactive choropleth maps (Plotly).  
   - Line/bar charts for trends in cases, deaths, and vaccinations.  
   - Pie charts showing vaccinated vs. unvaccinated populations.  

---

## 🔍 Key Insights  
My narrative and explanations Key Insights from the Data Fastest Vaccine
Roll-out: Here is a look at how the vaccine roll-out unfolded around the world: United States
The United States had the fastest roll out. While there were problems with vaccine distribution the
world over, the U.S. managed to get vaccines into millions of people at a rate that far outstripped
other nations. India, despite seeming to get off to a slow start, has gradually accelerated its vaccination
and is improving its coverage. Anomalies in Vaccination Coverage in Kenya: There was an
aberration in Kenya where the pace of the vaccination roll-out was slower than could be expected
given their population size and healthcare infrastructure. There was a huge increase in vaccination
rates later however, perhaps because of outside assistance and tie-ups with global health groups.
The difference may be related to logistics, vaccine supply and public-health campaigns aimed at
more remote areas. High case density in populous Areas: Both India and the United States are
characterized by high case density (cases per million people) reflecting their large and dense populations.
This trend demonstrates the close correlation between population density and number ofcases, and how bigger 
cities usually have more cases despite whatever public health measures are implemented. Smaller countries, 
especially in Africa, recorded lower case densities, which doesn’t
necessarily translate to infection rates since smaller countries may have under-counted cases due to
limited testing. Government Policy and the Influence on Vaccination: The faster, more widespread
vaccination was in contrast to nations that instituted strict government measures, like the United
States and Israel. Whereas in countries with milder rules or political problems, such as Kenya,
vaccine roll-outs lagged far behind. Additionally, it would be valuable to monitor vaccine coverage
and policy decisions which might help to reveal the success of various approaches. Regional Variations
in Total Cases: Africa for example (e.g., Kenya) reported a total less than other countries,
a combination of lower testing, much higher population immunity due to previous exposure, or a
different reporting standard than in Western nations. Although this might indicate low case numbers,
the effects on public health measures and economic consequences might still be substantial –
particularly if health care systems are under-resourced. 


## 💡 Reflections  
- **Challenges**: Handling large datasets (~88MB) and missing values required careful cleaning. Also, trying to run streamlit online was a big issue, I shall try on my local PC's terminal
- **Improvements**: Incorporating real-time data or expanding the country comparison set.  
- **Impact**: Visualizations highlight disparities in vaccine access and the role of governance in pandemic response.  
