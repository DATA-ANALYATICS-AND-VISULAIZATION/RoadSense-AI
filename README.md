# 🚦 RoadSense.ai – Road Accident Analysis and Safety Insights

### A Data Analytics and Visualization Project

RoadSense.ai is a data analytics project focused on exploring road accident information across India using available 2022 data. The project uses data collection, cleaning, analysis and visualization techniques to identify patterns in accident cases, injuries and deaths.

The project presents insights through Python-based analytics, visualizations and an interactive Power BI dashboard.

---

## 📌 1. Project Overview

Road accidents are a major public safety concern. Analyzing available accident data can help identify patterns, understand the distribution of accidents and support road-safety awareness.

RoadSense.ai aims to organize and analyze available road accident information across Indian States/UTs and districts and present the findings in an understandable format.

## 🎯 2. Project Objectives

- Collect available road accident data for the 2022 reference year.
- Clean and organize the collected dataset.
- Analyze accident cases, injuries and deaths.
- Explore State/UT-wise and district-level patterns where data is available.
- Visualize important findings using charts.
- Develop an interactive Power BI dashboard.
- Highlight data coverage and quality limitations.

## ❗ 3. Problem Statement

Road accident information can be difficult to interpret when it is distributed across different sources and geographic levels. Inconsistent formats and differences in data availability can make analysis challenging.

RoadSense.ai addresses this problem by organizing the available information, performing data analysis and presenting insights through visualizations and a dashboard.

## 💡 4. Proposed Solution

The project follows a structured data analytics workflow:

1. Data Collection
2. Data Cleaning
3. Data Analytics
4. Data Visualization
5. Interactive Dashboard Development

The results help users explore accident-related information and understand patterns within the available dataset.

## ⚙️ 5. Project Workflow

| Task | Description | Main Deliverable |
|---|---|---|
| Task 1 | Project Proposal | Project proposal document |
| Task 2 | Data Collection | Raw accident dataset |
| Task 3 | Data Cleaning | Python cleaning script and cleaned CSV |
| Task 4 | Data Analytics | Python analysis and analytical outputs |
| Task 5 | Data Visualization | Charts and visualization outputs |
| Task 6 | Interactive Dashboard | Power BI dashboard |

## 📊 6. Dataset Description

The project uses available road accident information for the 2022 reference year.

Important dataset fields include:

- Record ID
- Year
- State/UT
- District
- Accident Cases
- Injured
- Died
- Data Status
- Source
- Data Quality Note

**Note:** The dataset is a working dataset. Data coverage and verification vary across States/UTs and districts. Therefore, calculated totals should not be interpreted as independently verified national accident statistics.

Railway accident records are excluded from the project's road accident analysis.

## 🧹 7. Data Cleaning

Python and Pandas are used to prepare the dataset.

The cleaning process includes:

- Standardizing text values.
- Converting numerical fields into appropriate data types.
- Checking for duplicate records.
- Reviewing missing values.
- Adding data quality notes.
- Saving the cleaned dataset as a CSV file.

## 📈 8. Data Analytics

The analytics stage explores:

- Accident record distribution.
- State/UT-wise record counts.
- Data source and verification status.
- Estimated district-level records.
- District-level data availability.
- Data quality and source verification.

The analysis considers differences in source quality and geographic coverage.

## 📉 9. Data Visualization

The visualization stage presents selected findings through charts, including:

- Accident cases by State/UT.
- Deaths by State/UT.
- Injuries by State/UT.
- Accident cases by data status.
- Cases and injuries comparison.

The visualizations help users understand patterns in the available information.

## 📊 10. Power BI Dashboard

The interactive Power BI dashboard provides a visual interface for exploring the dataset.

### Dashboard Features

- Total accident cases KPI.
- Total injured KPI.
- Total deaths KPI.
- State/UT-wise accident comparison.
- State/UT-wise deaths comparison.
- Injuries and deaths comparison.
- Top 10 accident-prone districts based on the working dataset.
- Data source status visualization.
- State/UT filter and interactive slicer.

The dashboard contains two main pages:

1. **Exploratory Analysis**
2. **Overview Dashboard**

**Data interpretation:** Dashboard KPI values are calculated from the working dataset, which contains records with different data statuses. They should not be treated as verified national totals.

## 🛠️ 11. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and analytics |
| Pandas | Data cleaning and manipulation |
| Microsoft Excel | Dataset inspection |
| Power BI | Interactive dashboard |
| GitHub | Version control and project collaboration |

## 📁 12. Repository Structure

```text
RoadSense-AI/
│
├── README.md
├── LICENSE
│
├── Task_1_Project_Proposal/
│   ├── README.md
│   └── RoadSense_AI_Project_Proposal.docx
│
├── Task_2_Data_Collection/
│   ├── README.md
│   └── RoadSense_AI_Road_Accident_Data_2022_Dataset.csv
│
├── Task_3_Data_Cleaning/
│   ├── README.md
│   ├── data_cleaning.py
│   └── Cleaned_Dataset.csv
│
├── Task_4_Data_Analytics/
│   ├── README.md
│   └── Data_Analytics.py
│
├── Task_5_Data_Visualization/
│   ├── README.md
│   ├── Data_Visualization.py
│   └── Charts/
│
├── Task_6_PowerBI_Dashboard/
│   ├── README.md
│   └── RoadSense_AI_Dashboard.pbix
│
└── Final_Documents/
    ├── README.md
    ├── Project_Report.docx
    └── Project_Presentation.pptx
```

*The structure above describes the planned organization of the repository. File names may vary slightly from the actual uploaded versions.*

## ⚠️ 13. Limitations

- District-level data is not uniformly available across all States/UTs.
- Some records are estimated rather than independently verified.
- Data sources and verification statuses vary.
- The analysis uses 2022 reference-year data and does not provide a multi-year trend.
- Dashboard totals reflect the available working dataset, not verified national totals.
- Findings should be interpreted with the dataset's limitations in mind.

## 🚀 14. Future Scope

- Integrate more recent road accident datasets.
- Improve district-level data coverage.
- Add geographic accident hotspot maps.
- Develop more advanced accident pattern analysis.
- Explore machine learning techniques for accident-risk analysis.
- Expand dashboard functionality.

## 👥 15. Project Team

| Team Member | Roll Number |
|---|---|
| R. Anvika | 2503A52338 |
| R. Shivani | 2503A52350 |
| G. Sai Kiran | 2603A52L01 |

**Programme:** B.Tech – Computer Science and Engineering (AI/ML)  
**Subject:** Data Analytics and Visualization  
**Academic Year:** 2026–2027

## 🏁 16. Conclusion

RoadSense.ai demonstrates how data analytics and visualization can be used to explore available road accident information.

By combining Python, Pandas and Power BI, the project transforms a working dataset into structured analytical outputs and interactive visual insights.

The project also emphasizes the importance of data quality, source verification and responsible interpretation when working with real-world accident information.

---

### ⭐ RoadSense.ai
**Turning Road Accident Data into Meaningful Safety Insights.**
