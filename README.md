# 🚗 Weather vs Wheels: Do the Skies Shape NYC Accidents? 🌦️

## 📌 Project Overview
This project analyzes the impact of **weather conditions on motor vehicle collisions in New York City**. By leveraging datasets on traffic accidents and weather patterns, we aim to uncover correlations between adverse weather and collision trends, helping to improve road safety and inform city planning.

## 🏆 Project Goals
- Analyze the relationship between **weather conditions and traffic accidents** in NYC.
- Identify **high-risk locations and time periods** for accidents.
- Provide **data-driven recommendations** for policymakers to enhance road safety.
- Utilize statistical and machine learning techniques to assess accident severity trends.

## 📊 Dataset
We used **NYC Open Data** for motor vehicle collisions and weather data from **NOAA** (or another relevant source). The datasets include:
- **Collision Data**: Date, time, location, contributing factors, number of persons injured, etc.
- **Weather Data**: Temperature, precipitation, wind speed, visibility, and more.

## 🛠️ Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook** for analysis and visualization
- **SQL** for data querying

## 📈 Key Findings
1. **Weather Impact on Collisions**
   - Adverse weather conditions, such as **rain, snow, and fog**, significantly increase accident frequency.
   - The highest number of accidents occurred under **light rain conditions**, followed by snow and fog.

2. **Collision Severity Trends**
   - Accidents in poor weather conditions result in a higher **average injury and fatality rate**.
   - **Snow and fog** have the highest **fatality rates per accident**, despite fewer total collisions than rainy conditions.

3. **Temporal and Location Insights**
   - Collisions peak during **rush hours (8 AM - 9 AM & 5 PM - 7 PM)** in adverse weather.
   - Boroughs like **Brooklyn and Queens** experience more severe weather-related collisions than other areas.

## 📊 Example Visualizations
Below are some example visualizations from our analysis:

### 🚦 Collision Frequency by Weather Category
This bar chart shows the top weather conditions contributing to the highest number of collisions.

![Collision Frequency](results/collision_frequency.png)

### ⚠️ Severity of Accidents in Different Weather Conditions
A comparative view of the average injuries and fatalities per collision under different weather conditions.

![Collision Severity](results/collision_severity.png)

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Weather-vs-Wheels.git
   cd Weather-vs-Wheels
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Explore the analysis and results.

## 📌 Authors
This project was developed by:
- **Sukhad**
- **Biswadip**
- **Mihir**
- **Vaibhav**

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

Let me know if you’d like any refinements or additional details! 🚀
