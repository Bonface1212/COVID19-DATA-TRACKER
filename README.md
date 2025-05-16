# 🌍 COVID-19 Global Data Tracker

This project is a data analysis and visualization notebook that tracks global COVID-19 trends using real-world data. It analyzes confirmed cases, deaths, recoveries, and vaccination progress over time across selected countries.

---

## 📌 Project Objectives

- ✅ Import and clean COVID-19 global data
- ✅ Analyze time trends (cases, deaths, vaccinations)
- ✅ Compare metrics across countries
- ✅ Visualize trends with charts and interactive maps
- ✅ Communicate insights through a structured report

---

## 🗂️ Project Structure
covid-global-tracker/
│
├── owid-covid-data.csv # Dataset from Our World In Data
├── covid_tracker.ipynb # Jupyter Notebook with full analysis
├── README.md # Project documentation


---

## 🔢 Data Source

- [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/covid-deaths)
- Format: CSV (`owid-covid-data.csv`)

---

## 🚀 Technologies Used

- **Python 3**
- **pandas** – data manipulation
- **matplotlib / seaborn** – visualizations
- **plotly** *(optional)* – interactive choropleth maps
- **Jupyter Notebook** – development & reporting environment

---

## 🔍 Key Features

- 🧹 Data Cleaning: Handles missing values and filters target countries.
- 📈 Trend Analysis: Line plots for total cases, deaths, and new daily cases.
- 💉 Vaccination Tracking: Cumulative vaccination progress across countries.
- 📊 Death Rate Evaluation: Calculates and visualizes fatality rates.
- 🗺️ Choropleth Map *(optional)*: World map visualization of case counts.
- 📝 Insight Summary: Markdown-formatted narrative reporting key findings.

---

## 🌐 Countries Analyzed

- 🇰🇪 Kenya
- 🇺🇸 United States
- 🇮🇳 India

---

## 📄 Example Insights

- The US had the highest number of total cases and vaccinations.
- India's vaccination campaign ramped up significantly after mid-2021.
- Kenya's death rate stayed relatively low, possibly due to younger population demographics.
- Vaccine distribution remains unequal across regions.

---

## 🧰 How to Run

1. Clone the repo or download files.
2. Ensure `owid-covid-data.csv` is in the same directory.
3. Open the `covid_tracker.ipynb` file in Jupyter Notebook or VS Code with the Jupyter extension.
4. Run each cell in order.
5. (Optional) Export notebook as PDF: `File > Download as > PDF`.

---

## 📃 License

This project is licensed under the MIT License. Feel free to use, modify, and share.

---

## 🤝 Credits

- Data: [Our World in Data](https://ourworldindata.org/)
- Developed with 💻 by [BONFACE MAMBOLEO]
