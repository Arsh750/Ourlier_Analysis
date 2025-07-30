# Health Insurance Data: Outlier & Statistical Analysis

This project focuses on identifying and analyzing outliers in a US Health Insurance dataset using statistical techniques like IQR and Z-score. It also explores data distribution characteristics using skewness and kurtosis.

## 📁 Dataset
The dataset contains fields like:
- Age
- BMI
- Charges
- Smoker
- Region
- Children

## 🧰 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Project Steps

1. **Importing Libraries**  
   Loaded essential libraries including numpy, pandas, matplotlib, and seaborn.

2. **Loading the Dataset**  
   Imported the CSV file into a pandas DataFrame.

3. **Outlier Detection Using IQR**  
   Identified outliers in `charges`, `BMI`, etc. using the Interquartile Range (IQR) method and visualized with box plots.

4. **Visualization of Outliers**  
   Plotted boxplots and histograms to visually confirm the presence of outliers.

5. **Outlier Detection Using Z-Score**  
   Applied Z-score technique to compare and validate outlier detection.

6. **Skewness & Kurtosis Analysis**  
   Calculated skewness and kurtosis for features like charges and BMI to understand distribution asymmetry and peakedness.

7. **Final Observations**  
   Summarized how outliers might affect the dataset and the importance of treating them before building any predictive model.

## 📌 Key Takeaways
- Outliers are present in insurance charges and BMI.
- Z-score and IQR both confirm significant deviations in certain records.
- Distributions are right-skewed, especially for charges.

---

## ✅ Author
Krishna Malviya  
For collaboration or feedback, feel free to connect!
