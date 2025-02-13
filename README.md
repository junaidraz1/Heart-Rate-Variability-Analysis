# Heart Rate & Heart Rate Variability Analysis  

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)  
[![NumPy](https://img.shields.io/badge/Library-NumPy-orange.svg)](https://numpy.org/)  
[![SciPy](https://img.shields.io/badge/Library-SciPy-lightgrey.svg)](https://scipy.org/)  
[![Pandas](https://img.shields.io/badge/Library-Pandas-green.svg)](https://pandas.pydata.org/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

## 📌 Project Description  
This project performs **heart rate (HR) and heart rate variability (HRV) analysis** using **ECG and PPG signals**. It includes signal preprocessing, peak detection, HR estimation, and HRV analysis using Pointcare and Lorentz plots.  

## 📂 Features  
✅ **Preprocess ECG signals** for peak detection, including T-wave suppression  
✅ **Implement peak detection** to find local maxima in ECG and PPG  
✅ **Compute heart rate** and remove physiologically impossible beats  
✅ **Estimate heart rate variability (HRV)** using Pointcare and Lorentz plots  
✅ **Calculate average time delay** between ECG R-peak and PPG foot (onset)  

## 📝 Methodology  
1️⃣ **Preprocessing & Filtering:**  
   - Apply signal conditioning before peak detection  
   - Implement a **derivative filter** for **T-wave suppression**  

2️⃣ **Peak Detection:**  
   - Identify **local maxima** in ECG and PPG signals  
   - Detect **R-peaks in ECG** and **foot points in PPG**  

3️⃣ **Heart Rate Calculation:**  
   - Compute **beat-to-beat intervals**  
   - Filter out **non-physiological beats**  

4️⃣ **Heart Rate Variability (HRV) Analysis:**  
   - Generate **Pointcare plots**  
   - Generate **Lorentz plots**  

5️⃣ **ECG-to-PPG Delay Estimation:**  
   - Measure **time delay between ECG R-peak and PPG foot onset**  

## 📊 Visualization  
- **ECG & PPG signals with detected peaks**  
- **Heart rate over time**  
- **HRV plots (Pointcare & Lorentz)**  
- **ECG-to-PPG delay distribution**  
