# 🌍 DS5110 – Global Meteorite Landings  

## **☄️ Spatial Distribution and Composition Analysis of Global Meteorite Landings**  

**Authors:** Isha Pargaonkar, Shreya Chaudhary, Anjali Singh  

---

## **📌 Project Overview**  

The universe is vast and constantly evolving, and meteorites offer a rare opportunity to study its history. These extraterrestrial fragments provide valuable insights into the composition and processes of our solar system.  

This project explores the question:  
**How have the frequency and composition of meteorite discoveries changed over time, and how do these patterns vary across geographic regions?**  

Using the NASA Meteorite Landings dataset, which contains over 45,000 records, we analyze how factors such as geology, climate, human exploration, and scientific advancements have influenced meteorite discoveries over the past two centuries.  

---

## **📊 Data & Methodology**  

### **🗂️ Data Source**  
- NASA Meteorite Landings Dataset  

### **🧹 Preprocessing**  
- Removed records with missing or invalid:
  - Geographic coordinates  
  - Year  
  - Classification labels  
- Categorized meteorites into:
  - **Stone**
  - **Iron**
  - **Stony-Iron**  

### **⏳ Temporal Segmentation**  
To analyze historical trends, the data is divided into:  
- **1800–1949:** Early Period  
- **1950–1979:** Mid-Century  
- **1980–2013:** Modern Era  

---

## **📈 Analysis Approach**  

### **📍 Visual Analysis**  
We use multiple visualization techniques to uncover patterns:  
- Faceted world maps  
- Stacked bar charts  
- Density plots  

These help identify spatial and temporal trends in meteorite distribution and composition.  

### **📐 Statistical & Modeling Techniques**  
- Regression analysis to study:
  - Meteorite discovery trends  
  - Mass distribution (log-transformed)  
- Statistical testing to evaluate:
  - Differences across time periods  
  - Regional variations  

---

## **⚠️ Challenges**  

- Missing or inconsistent data  
- Bias in historical records  
- Uneven geographic sampling due to accessibility and search efforts  

These challenges are addressed through careful data cleaning and normalization techniques.  

---

## **🎯 Key Goals**  

This project aims to:  
- Identify long-term trends in meteorite discoveries  
- Understand regional differences in meteorite distribution  
- Analyze how composition varies across time and space  

By combining visualization and statistical analysis, we provide a comprehensive view of meteorite patterns across the globe.  

---

## **📚 References**  

[1] NASA Open Data Portal – Meteorite Landings Dataset  
https://data.nasa.gov/dataset/meteorite-landings  
