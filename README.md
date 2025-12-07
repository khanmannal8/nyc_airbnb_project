Here is the same professional README — **with zero emojis** and a clean academic tone.

You can paste this directly into your `README.md`.

---

# **Exploring and Visualizing the NYC Airbnb Market**

*CISC 4900 Project — Fall 2025*
**Student:** Mannal Khan

**Supervisor:** Prof. Samanta (Brooklyn College)

---

## **Project Overview**

This project analyzes the NYC Airbnb market through data cleaning, exploratory data analysis, and visualization.
The objective is to understand how pricing, availability, neighborhood characteristics, and host behavior relate to revenue and return on investment (ROI).

Using the Inside Airbnb dataset, this project follows a full data analysis workflow:

1. Data acquisition
2. Data cleaning and preprocessing
3. Exploratory data analysis (EDA)
4. Visualization (static and interactive)
5. Interpretation and insight generation

The final deliverables include a structured analysis pipeline, interactive visualizations, documentation, and a demo video that summarizes the findings.

---

## **Repository Structure**

```
nyc_airbnb_project/
│
├── data/                      # Raw and cleaned datasets
│   ├── raw/                  
│   └── cleaned/
│
├── notebooks/                 # Jupyter notebooks for each project stage
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_visualizations.ipynb
│   └── 99_experiments.ipynb
│
├── src/                       # Python modules for reusable functions
│   ├── cleaning_pipeline.py
│   ├── visualization_helpers.py
│   └── stats_utils.py
│
├── figures/                   # Visualization outputs
│   ├── maps/
│   ├── plots/
│   ├── dashboards/
│   └── interactive_figures/
│
├── docs/                      # Documentation, logs, diagrams
│   ├── methodology.md
│   ├── milestone_log.md
│   └── project_overview.md
│
├── README.md                  # Project overview and documentation
└── .gitignore
```

This structure is designed for clarity, reproducibility, and scalability.

---

## **Data Source**

**Inside Airbnb — NYC Listings Dataset**

The dataset includes:

* Listing prices
* Room types
* Availability
* Host information
* Review data
* Neighborhood classifications
* Geographic coordinates
* Minimum nights
* Indicators related to estimated revenue

Dataset link: [https://insideairbnb.com/get-the-data.html](https://insideairbnb.com/get-the-data.html)

---

## **Tools and Technologies**

**Programming and Analysis**

* Python 3
* pandas
* numpy
* matplotlib
* seaborn
* plotly
* scipy

**Environment**

* Jupyter Notebook / Google Colab
* Git and GitHub
* macOS development environment

**Visualization Tools**

* Plotly (interactive graphics)
* Matplotlib and Seaborn (static plots)
* Geospatial visualizations

---

## **Objectives**

**Primary Goals**

* Clean and prepare the raw NYC Airbnb data
* Conduct thorough exploratory data analysis
* Investigate relationships among price, availability, and occupancy
* Identify patterns that indicate high-yield neighborhoods
* Build interactive dashboards and maps
* Produce a polished final report and project presentation

**Deliverables**

* Jupyter notebooks
* Modular Python code in `/src`
* Static and interactive visualizations in `/figures`
* Documentation in `/docs`
* Final demo video and capstone report

---

## **Research Questions**

* Which NYC neighborhoods have the highest ROI for Airbnb hosting?
* How does availability correlate with revenue and occupancy?
* Do specific room types consistently outperform others?
* Where are the most underpriced and overpriced listings?
* Can neighborhoods be categorized into yield tiers using analytical models?

---

## **Methodology Summary**

1. **Data Acquisition**
2. **Cleaning and Preprocessing**

   * Handle missing values
   * Convert datatypes
   * Remove outliers
   * Engineer metrics (revenue, ROI, occupancy categories)
3. **Exploratory Data Analysis**

   * Summary statistics
   * Pairwise relationships
   * Neighborhood-level analysis
4. **Visualization**

   * Scatter plots, histograms, box plots
   * 3D visualizations
   * Geographic maps
5. **Insight Generation**

   * Identify market patterns
   * Evaluate investment potential across locations

---

## **Documentation**

See the `/docs` folder for:

* `methodology.md` — Detailed explanation of analytical process
* `milestone_log.md` — Timeline and progress tracking
* `project_overview.md` — Summary of goals and outcomes

---

## **Final Deliverables**

* Final written report
* Interactive visualizations
* Slide presentation
* Demo video
* Completed GitHub repository

---

## **Author**

**Mannal Khan**
Brooklyn College, Department of Computer Science
Fall 2025
Email: mannal.khan52@bcmail.cuny.edu

