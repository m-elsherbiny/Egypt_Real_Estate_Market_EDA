## 🏡 Egypt Real Estate Markert EDA  
This project is an Exploratory Data Analysis (EDA) of a real estate dataset containing over **19,000 property listings** across Egypt.  
The goal is to clean, process, and visualize the data to understand **market patterns, pricing behavior, property characteristics**, and **regional differences** across governorates and cities.

---

## 📂 Dataset  
The dataset includes detailed information for each property, such as:

- Price  
- Size (sqm)  
- Bedrooms & Bathrooms  
- Full Location (compound, city, governorate)  
- Property Type (Apartment, Chalet, Villa, etc.)  
- Payment Method  
- Additional features (e.g., maid room)

---

## 📚 Libraries  
The analysis was performed in Python using the following libraries:

## Data Manipulation & Cleaning:
- Pandas  
- NumPy  

## Data Visualization:
- Matplotlib  
- Seaborn  
- Missingno  

---

## 🔍 Key Analysis Steps  
- Checked dataset structure, shape, and summary statistics  
- Handled missing values using targeted strategies  
- Cleaned complex columns (e.g., parsing `"1,023 sqft / 95 sqm"` into **95 sqm**)  
- Parsed full locations into: `compound`, `city`, and `governorate`  
- Standardized property types (e.g., merging **iVilla → Villa**)  
- Created engineered features:
  - `price_per_sqm`
  - `size_bin` (Small, Medium, Large, Extra Large)
  - `maid_room` extraction  
- Visualized property distribution across regions, types, and size categories  
- Explored relationships between price and key features (type, size, governorate, bedrooms, etc.)  

---

## 💡 Insights (High-Level)  
- **Apartments dominate** the dataset, representing the largest share of listings  
- **Villas** have the highest total prices and form the luxury segment  
- **Coastal areas** like North Coast and Red Sea show the **highest price per sqm**  
- **Sharkia and Asyut** appear as the most affordable governorates  
- **Most properties fall into the 90–170 sqm range**, indicating typical family-size demand  
- **Price per sqm** proved to be the most reliable indicator of market segmentation  

---

## 🛠️ Tech Stack  
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📄 Reports  
This project includes:

- **Full multi-page PDF report** summarizing analysis & insights  
- **EDA visuals and segmentation plots**  
- **Location parsing and feature engineering steps**  

---

## 📌 Next Steps  
- Build a regression model to predict property prices  
- Perform feature importance analysis  
- Deploy an interactive dashboard for real estate insights  

---

If you’d like to explore the notebook or reports, feel free to reach out!
