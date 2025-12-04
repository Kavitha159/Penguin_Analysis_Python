# **Penguins Data Analysis**

This project performs Exploratory Data Analysis (EDA) on the Penguins dataset to understand species characteristics, relationships between numerical features, and distribution across different islands.

### **1. Project Objective**

- Analyze dataset structure and quality <br>
- Explore relationships between penguin measurements <br>
- Understand species-level differences <br>
- Prepare

### **2. Dataset Information**

The Penguins dataset includes physical measurements and categorical details about penguins observed in Antarctica.

| Column Name       | Type     | Description                                      |
|-------------------|----------|--------------------------------------------------|
| species           | Category | Penguin species: Adelie, Chinstrap, Gentoo       |
| island            | Category | Geographic location: Biscoe, Dream, Torgersen    |
| bill_length_mm    | Float64    | Length of bill (mm)                              |
| bill_depth_mm     | Float64    | Depth of bill (mm)                               |
| flipper_length_mm | Float64  | Length of flipper (mm)                             |
| body_mass_g       | Float64  | Body mass (g)                                      |
| sex               | Category | Male or Female                                   |


### **3. Data Preprocessing Summary**

- Missing values identified in sex and some numerical columns.

- No duplicate records were found.

- Numerical values fall within expected biological ranges.

- The dataset does not require scaling unless used for ML models later.

### **4. Exploratory Data Analysis**
   
#### **4.1 Univariate Analysis**

- Adelie penguins represent the largest portion of the dataset.

- Gentoo penguins have the highest body mass on average.

- Sex distribution is nearly balanced but includes missing values.

#### **4.2 Numerical Feature Distributions**

- body_mass_g and flipper_length_mm show larger variation compared to bill dimensions.

- Distributions appear unimodal with slight skewness depending on species.

### **5. Bivariate and Multivariate Observations**

- A strong positive correlation exists between:

- Body Mass and Flipper Length

- Bill Length and Bill Depth

- Scatterplots with species hue show clear clusters, indicating measurable biological differences.

When using species for color grouping:

- Gentoo penguins are generally larger in body mass and flipper length.

- Adelie penguins are typically smaller with shorter flippers and lower body mass.

- Chinstrap penguins fall between Adelie and Gentoo in most measurements.

When grouping by island:

- Clustering remains visible, but differences largely reflect species rather than island location.

### **6. Key Findings**

- Species can be visually separated using numerical measurements.

- The dataset is suitable for classification-based ML tasks.

- Physical attributes display strong internal consistency and biological logic.

- Island and sex show secondary but relevant influences on trait variation.

### **7. Conclusion**

The Penguins dataset demonstrates meaningful variability across penguin species, with clear measurable distinctions based on physical traits. The dataset is clean, interpretable, and well-suited for predictive modeling, statistical analysis, and clustering.


