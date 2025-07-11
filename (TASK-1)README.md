# ✈️ Big Data Analysis on Airline Delays (2019)

This project uses **PySpark** to analyze large-scale flight delay data for 2019. It focuses on identifying patterns in delays based on **weather conditions**, **airline carriers**, **airports**, and **flight distance**, demonstrating the power of scalable data processing.

---

## 📦 Dataset

- **Source**: Kaggle — *2019 Airline Delays with Weather and Airport Detail*
- **Size**: Large dataset with millions of records
- **Key Fields**:
  - `DEP_DEL15` – Delay status (1 = delayed ≥15 min, 0 = on time)
  - `CARRIER_NAME` – Airline
  - `DEPARTING_AIRPORT` – Origin airport
  - `PRCP`, `SNOW`, `SNWD`, `TMAX`, `AWND` – Weather indicators
  - `DISTANCE_GROUP` – Flight distance category

---

## 🛠️ Tools & Technologies

- **PySpark** – Scalable data processing  
- **Pandas** – For sampling and summary operations  
- **Seaborn & Matplotlib** – Visualizations  

---

## 📊 Highlights & Insights

- ✈️ **Airports like LaGuardia and Chicago O’Hare** showed higher average delay rates.
- 🌧️ **Rain, snow, and wind** were significantly linked to increased delays.
- 🧊 **Cold temperatures** were associated with more frequent delays.
- 📏 **Short-distance flights** had more delays compared to long-haul routes.
- 🏢 **Southwest, American, and Delta** operated the most flights overall.

---

## 📁 Project Structure
.
├── notebook/         # Jupyter notebook for full analysis
├── data/             # Sample data files used in the notebook
├── scripts/          # Optional PySpark scripts (if modularized)
└── README.md         # Project documentation
## ▶️ How to Run

```bash
pip install -r requirements.txt
Or open the notebook directly in Jupyter or Google Colab.
