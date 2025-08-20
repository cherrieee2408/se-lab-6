# 🌦️ Weather Modeling – Quadratic Equation in Different Development Models  

This project demonstrates **temperature prediction** using a **quadratic equation** applied in three different software development approaches: **Waterfall, Iterative, and Agile**.  
It runs directly in **Google Colab** or any Python environment.  

---

## 📌 Quadratic Model Formula  

We use the equation:

T(t) = at² + bt + c

Where:  
- `T(t)` → Predicted temperature (°C)  
- `t` → Time (hours)  
- `a, b, c` → Coefficients of the quadratic model  

In this program:  
a = -0.2, b = 1.5, c = 24

---

## 📂 Files  

* **`weather_model_exp2.py`** – Python script (Waterfall, Iterative, Agile).  
* **`weather_model_exp2.ipynb`** – Jupyter/Colab notebook version.  

---

## ⚙️ Requirements  

Only Python 3 is required.  
(Optional) Install Matplotlib if you want to extend with plots:  

```bash
pip install matplotlib
=== WATERFALL MODE ===
Time: 0 hrs  -> Predicted Temp: 24.00°C
Time: 6 hrs  -> Predicted Temp: 28.40°C
Time: 12 hrs -> Predicted Temp: 28.80°C
Time: 18 hrs -> Predicted Temp: 25.20°C
Time: 24 hrs -> Predicted Temp: 17.60°C
=== ITERATIVE MODE ===
Iteration 1:
Time: 0 hrs  -> Temp: 24.00°C
Time: 12 hrs -> Temp: 28.80°C
Time: 24 hrs -> Temp: 17.60°C
---
Iteration 2:
Time: 0 hrs  -> Temp: 24.00°C
Time: 12 hrs -> Temp: 28.80°C
Time: 24 hrs -> Temp: 17.60°C
---
Iteration 3:
Time: 0 hrs  -> Temp: 24.00°C
Time: 12 hrs -> Temp: 28.80°C
Time: 24 hrs -> Temp: 17.60°C
=== AGILE MODE ===
Sprint 1:
Time: 0 hrs  -> Temp: 24.00°C
Time: 6 hrs  -> Temp: 28.40°C
Time: 12 hrs -> Temp: 28.80°C
Time: 18 hrs -> Temp: 25.20°C
Time: 24 hrs -> Temp: 17.60°C
---
Sprint 2:
Time: 0 hrs  -> Temp: 24.00°C
Time: 6 hrs  -> Temp: 28.40°C
Time: 12 hrs -> Temp: 28.80°C
Time: 18 hrs -> Temp: 25.20°C
Time: 24 hrs -> Temp: 17.60°C
