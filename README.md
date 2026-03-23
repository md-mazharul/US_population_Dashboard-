# 🏂 US Population Dashboard

An interactive web dashboard built with **Streamlit** that visualizes US state population data from 2010 to 2019. Explore population trends, migration patterns, and state-level comparisons through dynamic charts and maps.

---

## 📊 Features

- **Choropleth Map** – Visual representation of population distribution across all US states for a selected year
- **Heatmap** – Year-over-year population comparison across all states (2010–2019)
- **Gains/Losses Panel** – Highlights the states with the highest and lowest population changes compared to the previous year
- **States Migration** – Donut charts showing the percentage of states with significant inbound and outbound migration (>50,000)
- **Top States Table** – Ranked list of states by population with a progress bar visualization
- **Year & Color Theme Selector** – Sidebar controls to filter by year and customize the color scheme

---

## 🗂️ Project Structure

```
US_population_Dashboard-/
│
├── HW2.py                                  # Main Streamlit application
├── requirements.txt                        # Python dependencies
├── us-population-2010-2019-reshaped.csv    # Dataset (US Census Bureau)
└── .devcontainer/                          # Dev container configuration
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/md-mazharul/US_population_Dashboard-.git
   cd US_population_Dashboard-
   ```

2. **Create and activate a virtual environment** *(recommended)*
   ```bash
   python -m venv venv

   # Windows
   venv\Scripts\activate

   # Mac/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```bash
   streamlit run HW2.py
   ```

5. **Open in browser**

   The app will automatically open at `http://localhost:8501`

---

## 🛠️ Built With

| Library | Purpose |
|---|---|
| [Streamlit](https://streamlit.io/) | Web app framework |
| [Pandas](https://pandas.pydata.org/) | Data manipulation |
| [Altair](https://altair-viz.github.io/) | Heatmap & donut charts |
| [Plotly Express](https://plotly.com/python/plotly-express/) | Choropleth map |

---

## 📁 Data Source

Population data sourced from the [U.S. Census Bureau](https://www.census.gov/data/datasets/time-series/demo/popest/2010s-state-total.html) — State Population Totals: 2010–2019.

---

## 📌 Usage

- Use the **sidebar** to select a year (2010–2019) and a color theme for the visualizations
- The **Gains/Losses** panel updates to show the top gaining and top losing state for the selected year
- The **States Migration** section shows what percentage of states had significant population movement compared to the prior year
- The **choropleth map** and **heatmap** update dynamically based on your selections

---

## 🙏 Acknowledgements

- Dashboard layout inspired by [Streamlit community examples](https://streamlit.io/gallery)
- Data provided by the U.S. Census Bureau
