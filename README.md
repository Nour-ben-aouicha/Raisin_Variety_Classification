# Raisin_Variety_Classification

## Project Description
🔍 In this project, we utilized data cleaning and analysis tools for data preprocessing and AI models for classifying raisin data points.
## Data Insights
🍇 The dataset identifies two raisin classes (Kecimen and Besni) with 6 features:
<br><br>
Area, Perimeter, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, Extent.
Also includes a 'Class' feature denoting the raisin variety.
<br><br>
**Data exploration:** 📊<br><br> 
![5](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/4b6d3914-d854-402a-999d-3ce266964422)

<br><br>**Data Visualization:** 🖼️<br><br>
![image](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/6c338000-3d5b-41e3-a5e3-0347da4ca19a)
<br><br>
## Data Preprocessing
🛠️ After imputation and confirming non-normal data distribution through the Shapiro-Wilk test, we proceeded with modality, correlation tests, and PCA analysis.<br><br>
### PCA Components: 📈 
![7](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/fdbcbc52-8c83-4282-8635-b8687bb60ba1)
![image (1)](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/78a945e3-52a0-4b21-a940-ee8fdbe8d901)
<br><br>
## Modeling
🧮 Utilizing GLM for the classification task:<br><br>
![15](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/c4a61268-d372-4d0a-8802-e9ac6305fce1)
### Conclusion:
📊 The model suggests that MinorAxisLength is significantly influenced by Area, MajorAxisLength, Eccentricity, ConvexArea, Extent, and Perimeter of the data points. These variables collectively contribute to explaining the variation in MinorAxisLength, with strong statistical significance indicated by their low p-values and large t-values.
