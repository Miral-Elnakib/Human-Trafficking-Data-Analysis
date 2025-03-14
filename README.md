## 🔍 Human Trafficking Data Analysis

### 📌 Overview
This project analyzes a comprehensive dataset on human trafficking to uncover patterns, trends, and insights into this global issue. By leveraging data science techniques, we explore key aspects such as victim demographics, types of exploitation, and geographic distributions. The goal is to provide meaningful visualizations and statistics to raise awareness and support further research or policy-making efforts.

---

### 🚀 Key Features
- **🛠️ Data Cleaning**: Handles missing values, duplicates, and inconsistent data for reliable analysis.
- **📊 Exploratory Data Analysis (EDA)**: Summarizes victim age groups, exploitation types, and citizenship patterns.
- **📈 Visualizations**: Includes interactive pie charts and heatmaps to illustrate findings effectively.
- **🌍 Geographic Mapping**: Converts country codes to names and visualizes victim distributions globally.
- **🔬 Custom Analysis**: Breaks down exploitation types by age groups with styled tables.

---

### 📂 Dataset
The dataset ([Global Human Trafficking Dataset](https://www.unodc.org/unodc/en/data-and-analysis/glotip.html)) contains **48,801 records** with **63 columns**, including:

- 🗓️ **yearOfRegistration**: Year the case was registered (2002–2019).
- 👤 **gender, ageBroad**: Demographic details of victims.
- 🌎 **citizenship**: Country of origin (ISO Alpha-2 codes).
- ⚖️ **typeOfExploitConcatenated**: Types of exploitation (e.g., sexual exploitation, forced labor).
- 👥 **RecruiterRelationship**: Relationship of the recruiter to the victim.

🔹 *Note: Sensitive or incomplete columns were dropped to ensure meaningful insights.*

---

### 🛠️ Tools & Libraries
- 🐍 **Python 3.9+**
- 📦 **pandas**: Data manipulation and cleaning.
- 🔢 **NumPy**: Numerical operations.
- 🎨 **Seaborn**: Heatmap visualizations.
- 📊 **Plotly**: Interactive charts (e.g., pie charts for exploitation types).
- 🌍 **pycountry_convert**: Country code conversions.

---

### 📥 Installation
#### 🖥️ Clone the Repository:
```bash
 git clone https://github.com/your-username/human-trafficking-analysis.git
 cd human-trafficking-analysis
```

#### 📦 Install Dependencies:
```bash
 pip install -r requirements.txt
```

#### 📑 Requirements File (create `requirements.txt`):
```
pandas
numpy
seaborn
plotly
pycountry_convert
```

#### ▶️ Run the Notebook:
1️⃣ Open `human_trafficking_analysis.ipynb` in Jupyter Notebook or any compatible IDE.
2️⃣ Ensure `human_trafficking.csv` is in the project directory.

---

### 📊 Usage
- ✅ **Data Preprocessing**: Execute cells 1–11 to clean the data (remove duplicates, handle missing values, etc.).
- 🌍 **Geographic Analysis**: Run cells 12–13 to map victim citizenships.
- 📈 **Visualizations**:
  - 📊 Cell 14: Pie chart of sexual exploitation types.
  - 🔥 Cell 29: Heatmap of exploitation types by age group.
- 🧐 **Explore Results**: Interact with the outputs or modify the code for custom analyses.

---

### 🔍 Key Findings
🔹 **Sexual Exploitation**:
- Dominates across age groups, peaking at ages **9–17** (*1,224 cases*) and **18–20** (*1,022 cases*).
- Pie chart shows **"Prostitution"** as the most common type (*2,119 cases*), with **"unknown"** types significant (*5,644 cases*).

🔹 **Forced Labor**:
- Highest among **30–38** age group (*575 cases*), followed by **39–47** (*320 cases*).
- Less prevalent among younger victims (*e.g., 37 cases for 0–8*).

🔹 **Age Distribution**:
- Victims aged **9–17** and **18–20** are most affected by sexual exploitation.
- Older age groups (**30–47**) face higher rates of forced labor.

🔹 **Geographic Insights**:
- Citizenship data mapped to countries reveals global patterns (*e.g., "CO" = Colombia*).

---

### 📌 Visualizations
#### 📊 **Distribution of Sexual Exploitation Types**
📍 *Interactive pie chart showing breakdown of sexual exploitation types.*

#### 🔥 **Exploitation Types by Age Group**
📍 *Heatmap highlighting exploitation prevalence across age ranges.*

(*Replace placeholders with actual image paths after generating and uploading visuals to your repo.*)

---

### 🚀 Future Enhancements
🔹 Add **time-series analysis** for trends over years.
🔹 Incorporate **more detailed geographic visualizations** (*e.g., choropleth maps*).
🔹 Expand to include **recruiter relationship patterns**.
🔹 Integrate **machine learning** for predictive insights.

---

### 🤝 Contributing
Contributions are welcome! Please:
1️⃣ **Fork the repository**.
2️⃣ **Create a feature branch** (`git checkout -b feature/new-analysis`).
3️⃣ **Commit changes** (`git commit -m "Add new analysis"`).
4️⃣ **Push to the branch** (`git push origin feature/new-analysis`).
5️⃣ **Open a pull request**.

---

### 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

### 💡 Acknowledgments
🔹 **Dataset Source**: [Global Human Trafficking Dataset](https://www.unodc.org/unodc/en/data-and-analysis/glotip.html)
🔹 **Built with ❤️ using open-source tools.**
