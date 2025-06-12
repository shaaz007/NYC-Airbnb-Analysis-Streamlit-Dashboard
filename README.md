# NYC-Airbnb-Analysis-Streamlit-Dashboard

This project explores the **Airbnb listings in New York City** using Python and presents the insights via an interactive **Streamlit dashboard**. It involves data cleaning, exploratory data analysis (EDA), and building a simple but powerful front-end visualization.

## 📁 Project Structure

```

├── AirBnB\_NYC\_2019.csv
├── CA2\_ExploratoryDataAnalysis(EDA)24300262.ipynb
├── CA2\_Streamlit\_Python\_Script(24300262).ipynb
├── README.md

````

## 📊 Dataset

- **Source**: [Inside Airbnb](http://insideairbnb.com/)
- **File**: `AirBnB_NYC_2019.csv`
- **Size**: ~49,000 listings
- **Features**: Includes host ID, neighbourhood group, room type, price, number of reviews, availability, etc.

## 🔍 Exploratory Data Analysis (EDA)

The EDA notebook (`CA2_ExploratoryDataAnalysis(EDA)24300262.ipynb`) includes:

- Data cleaning and handling missing values
- Distribution of listings across boroughs
- Price distribution by room type and location
- Correlation analysis of features
- Visualizations using matplotlib and seaborn

Key insights:

- **Manhattan** has the highest average prices
- **Private rooms** dominate in the **Bronx**
- Listings with more availability generally have higher prices

## 🧠 Streamlit Web App

The Streamlit script (`CA2_Streamlit_Python_Script(24300262).ipynb`) allows users to:

- Filter listings by neighbourhood group and room type
- View interactive maps with listing locations
- Visualize price trends and listing density
- Compare average prices by borough and room type

## 🚀 How to Run the App Locally

1. **Install Dependencies**:
   ```bash
   pip install pandas numpy streamlit matplotlib seaborn
````

2. **Run Streamlit**:

   ```bash
   streamlit run CA2_Streamlit_Python_Script(24300262).ipynb
   ```

3. **Open in Browser**: Navigate to `http://localhost:8501`




