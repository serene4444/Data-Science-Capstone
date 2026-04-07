# Applied Data Science Capstone 🚀

**Course**: Coursera - *Applied Data Science Capstone* (IBM)

**Certificate**: IBM Data Science Professional Certificate

**Winning Space Race with Data Science**: https://myunt-my.sharepoint.com/:p:/r/personal/sereneplummer_my_unt_edu/Documents/ds-capstone-template-coursera.pptx?d=wf03bfce4d9f74dffb209e3fe5736554b&csf=1&web=1&e=MQNLgM

**Completed**: July 2025

**Created by**: Serene Plummer




----
## 🎯 Project Overview

This capstone project mimics real-world data science workflows: collecting data, cleaning and wrangling records, visualizing trends, building models, and reporting results.
The goal is to **predict whether SpaceX's Falcon 9 first stage will land successfully**, enabling smarter decisions on launch reuse.

---
## 📁 Data & Project Assets

The repository includes the raw and transformed datasets used throughout the project:

- **`Labs/Data Collection/dataset_part_1.csv`** and **`Labs/Data Collection/spacex_web_scraped.csv`** — launch records collected from the SpaceX API and web scraping work.
- **`Labs/Data Wrangling/dataset_part_2.csv`** — the cleaned and consolidated launch dataset used for analysis.
- **`Labs/EDA with Visual/dataset_part_3.csv`** — the prepared analysis dataset for exploratory visualizations.
- **`Interactive Visual Analytics/Analysis with Folium/spacex_launch_geo.csv`** — launch-site latitude and longitude data for geospatial mapping.
- **`Interactive Visual Analytics/Ploty Dash/spacex_launch_dash.csv`** — the dashboard dataset used by the Plotly Dash app.

The modeling notebook also works with engineered features such as payload mass, flight count, grid fins, reused status, legs, booster block, reused count, orbit, launch site, landing pad, and booster serial. The target is the binary landing outcome.

---
## 🧰 Tools & Technologies

- **Languages**: Python  
- **Development Environment**: Jupyter Notebook / JupyterLab, Git & GitHub, IBM Watson Studio  
- **Libraries & Frameworks**:
  - `pandas`, `NumPy`, `SciPy` — for data wrangling and manipulation  
  - `scikit-learn` — for classification modeling (Logistic Regression, SVM, Decision Trees)  
  - `Matplotlib`, `Seaborn` — for exploratory visual analysis  
  - `Folium` — for geospatial mapping and interactive launch-site visualization  
  - `Plotly Dash` — for building interactive dashboards  
  - `ipython-sql` — to run SQL queries against Db2  
  - **Web scraping tools**: `requests`, `BeautifulSoup`  
- **Database**: IBM Db2 on IBM Cloud  
- **APIs**: SpaceX REST API

---
## 🔍 Project Workflow & Learnings

### 1. **Data Collection**
### 2. **Data Wrangling**
### 3. **Exploratory Data Analysis (EDA)**
### 4. **Interactive Mapping**
### 5. **Dashboard Development**
### 6. **Machine Learning Modeling**
- Prepared data: train/test split, normalization  
- Built classification models on the landing-success target:
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
  - **Decision Tree Classifier**
- Performed **hyperparameter tuning** via `GridSearchCV`  
- Evaluated models using accuracy, precision/recall, F1‑score; selected best performer for prediction tasks

---
## 🗺️ Interactive Deliverables

- The Folium notebook maps SpaceX launch sites and compares site-level landing patterns.
- The Plotly Dash app provides an interactive dashboard with a launch-site dropdown, a payload range slider, a pie chart for success/failure counts, and a scatter plot of payload versus launch success.
- The launch sites represented in the data include **CCAFS SLC-40**, **KSC LC 39A**, and **VAFB SLC 4E**.

---
