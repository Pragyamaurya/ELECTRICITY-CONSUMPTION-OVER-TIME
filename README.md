# 🔌 Electricity Consumption Analysis 📊

## 📁 Project Overview

This project focuses on analyzing a household's electricity consumption using time-series data collected over several months. By leveraging features like **active power, reactive power, voltage, and sub-metered energy usage**, we uncover patterns, detect anomalies, and explore seasonal trends in electricity usage.

---

## 🧠 Problem Statement

The dataset captures daily readings of various electrical parameters including:
- `Global_active_power` (kilowatts)
- `Global_reactive_power` (kilowatts)
- `Voltage` (volts)
- `Global_intensity` (amperes)
- `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3` (watt-hours for different areas)

🔍 The goal is to:
- Understand the **seasonal variation in electricity usage**
- Investigate the **missing values in `Voltage`**, possibly due to **power cuts**
- Analyze energy consumption trends and their relationship with voltage and intensity
- Identify usage spikes or unusual consumption behavior

---

## 📊 Key Insights

- **Voltage readings** decrease from **January to April**, and start increasing from **May onward**.
- This may be linked to the **rainy season**, where reduced natural light increases the use of electric lighting.
- **Sub-metering** helps reveal which household areas consume the most energy over time.
- Missing values in `Voltage` suggest probable **power interruptions** or **sensor issues**.

---

## 📈 Features Explored

| Column Name            | Description                                     |
|------------------------|-------------------------------------------------|
| `Date` & `Time`        | Timestamp of each reading                       |
| `Global_active_power`  | Active power used (in kW)                       |
| `Global_reactive_power`| Reactive power used (in kW)                     |
| `Voltage`              | Voltage level (in volts)                        |
| `Global_intensity`     | Current (in amperes)                            |
| `Sub_metering_1`       | Energy usage in Kitchen (e.g., dishwasher)      |
| `Sub_metering_2`       | Energy usage in Laundry room                    |
| `Sub_metering_3`       | Energy usage for Heating/AC/water heater       |

---

## 🛠️ Tools & Technologies

- **Python** 🐍
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for interactive analysis

---

## 📅 Future Enhancements

- Forecasting electricity usage using Time Series models (ARIMA, LSTM)
- Interactive dashboard (using Plotly or Power BI)
- Automated anomaly detection using ML

---

## 📌 Conclusion

This project provides valuable insights into energy consumption patterns and highlights the importance of analyzing voltage behavior, especially during seasonal changes. The findings can help in **optimizing energy use**, **detecting outages**, and **planning power distribution** more efficiently.

---

## 📎 Dataset

> The dataset used contains records of minute-by-minute measurements of household electric power consumption over a period of time.

---

## 📬 Contact

Made with 💡 by **Pragya**  
