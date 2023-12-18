# Raisin_Variety_Classification

## Project Description
In this project, we used data cleaning and analysis tools to preprocess our data and AI models to classify the data points. <br><br>
## Data Insights
The Raisin dataset will be used in identifying two different classes of raisin (Kecimen and besni). <br><br>
It contains 6 features:<br>
* Area: the number of pixels within the boundaries of the raisin.
* Perimeter: measures the environment by calculating the distance between the boundaries of the raisin and the pixels around it.
* MajorAxisLength: the length of the main axis, which is the longest line that can be drawn on the raisin.
* MinorAxisLength: the length of the small axis, which is the shortest line that can be drawn on the raisin.
* Eccentricity: measure of the eccentricity of the ellipse, which has the same moments as raisins.
* ConvexArea: the number of pixels of the smallest convex shell of the region formed by the raisin.
* Extent: the ratio of the region formed by the raisin to the total pixels in the bounding box.
* Class : Kecimen and Besni raisin.
<br><br>
**Data overview:** <br><br>
![0](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/552025e9-b6d8-4f73-ac53-97041101a2fe)
![5](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/4b6d3914-d854-402a-999d-3ce266964422)

<br><br>**Data Visualization:** <br><br>
![image](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/6c338000-3d5b-41e3-a5e3-0347da4ca19a)
<br><br>
## Data Preprocessing
First step is the data imputation; we relaced the missing values with the KNN values then we performed the Shapiro-Wilk test to test the normality of our data distribution for each feature; we find that the data is not normally distributed in neither of the features. We then proceed to the modality then we run the correlation tests and perform the PCA. Here are the components obtained:<br><br>
![image (1)](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/78a945e3-52a0-4b21-a940-ee8fdbe8d901)
<br><br>
## Modeling
In this section, we will use GLM to perform the classification task.<br><br>
![15](https://github.com/Nour-ben-aouicha/Raisin_Variety_Classification/assets/92543024/c4a61268-d372-4d0a-8802-e9ac6305fce1)
