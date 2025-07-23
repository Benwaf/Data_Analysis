# Data_Analysis

# COVID-19 Global Tracker

A real-time, interactive COVID-19 tracker built using Python and Jupyter Notebook. This tool provides up-to-date statistics and visualizations for global and country-specific COVID-19 data using live data from the [disease.sh API](https://disease.sh/).


## Objectives

- Fetch and display real-time global COVID-19 statistics
- Provide country-wise breakdowns of cases, deaths, and recoveries
- Enable interactive time-series analysis for any selected country
- Visualize trends using dynamic charts
- Build a clean, fully functional notebook for data analysis

---

## Tools and Libraries Used

- **Python** — Core programming language
- **Jupyter Notebook** — Interactive development and visualization
- **pandas** — Data manipulation and transformation
- **requests** — API calls to fetch live data
- **plotly** — Interactive time-series visualizations
- **ipywidgets** — UI components like dropdowns for interactivity
- *(optional)* `matplotlib` or `tabulate` can be added for extra visualization or tabular output

## How to Run the Project

1. **Clone or download the notebook** into your local machine:
    ```bash
    git clone https://github.com/yourusername/covid19-tracker.git
    ```

2. **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook covid19_tracker.ipynb
    ```

3. **Install dependencies** (run in the first notebook cell):
    ```python
    !pip install pandas plotly requests ipywidgets
    ```

4. **Run each cell sequentially** and interact with the dropdown to explore different countries.

> Make sure you're connected to the internet, as it fetches **live data** from the API.

##Insights and Reflections

- The COVID-19 pandemic varies greatly by region; this tracker highlights those disparities through interactive visuals.
- Time-series trends can show the effectiveness of policy decisions, spikes in infections, or recovery plateaus.
- Using a live API like `disease.sh` makes the tool current and reduces the need for data maintenance.
- Python notebooks are a powerful and accessible way to combine data, visuals, and interactivity for both technical and non-technical users.
