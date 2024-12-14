# **Predictive Modeling: Height and Weight Analysis**

## **Overview**
This project focuses on developing a predictive model to estimate a person's weight based on their height and gender using a regression analysis approach. The project involves data cleaning, data visualization, model training, evaluation, and result interpretation.

The dataset used in this project contains the following attributes:
- `Height_in_inchies`: Height of individuals in inches.
- `Weight_in_pound`: Weight of individuals in pounds.
- `Gender`: Gender of individuals (Male or Female).

## **Objectives**
- Train a predictive model to estimate weight from height and gender.
- Evaluate model performance using metrics such as Mean Squared Error (MSE) and R-squared.
- Visualize predicted vs. actual values and residuals to assess the model.

---

## **Setup Instructions**
To replicate this project, follow these steps:

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/Project3_PredictiveModel.git
cd Project3_PredictiveModel
```

### **2. Install Required Packages**
Ensure you have R installed on your system. Install the necessary libraries by running:
```r
install.packages(c("tidyverse", "caret", "rmarkdown"))
```

### **3. Run the Analysis**
Open the RMarkdown file `Project3_PredictiveModel.Rmd` in RStudio and click the **Knit** button to generate the analysis.

---

## **Key Results**

### **Model Performance**
- **Mean Squared Error (MSE):** _Calculated value (from R output)_.
- **R-squared:** _Calculated value (from R output)_.

### **Visualizations**
#### 1. Predicted vs. Actual Weight
This graph shows the predicted weight against the actual weight to evaluate the accuracy of the model.

![Predicted vs Actual Weight](graphs/predicted_vs_actual.png)

#### 2. Residual Plot
The residual plot helps identify patterns in the residuals, indicating potential areas of model improvement.

![Residual Plot](graphs/residual_plot.png)

---

## **Directory Structure**
The repository is organized as follows:
```
Project3_PredictiveModel/
│
├── data/
│   └── cleaned_height_weight_data.csv   # Processed dataset used in the analysis
│
├── graphs/
│   ├── predicted_vs_actual.png          # Visualization: Predicted vs Actual
│   └── residual_plot.png                # Visualization: Residual Plot
│
├── Project3_PredictiveModel.Rmd         # RMarkdown file for analysis
├── README.md                            # Project documentation
├── output.html                          # Rendered analysis in HTML
└── LICENSE                              # License file for the repository
```

---

## **How to Contribute**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of the changes.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**
Special thanks to Faith Adeyemi Allen for curating the dataset and implementing the predictive model.

---
