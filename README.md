# 🌱 AI Based Crop Health Monitoring Capstone Project 🚜

> **"Helping farmers see what their eyes can't!"**  
> *-- Built by an aspiring AI Student 🤖🎓*

---

## 👋 Hello World!
Welcome to my **Capstone Project**! I'm an AI student learning how to use Machine Learning to solve real-world problems. This project is all about **Precision Agriculture**. 

I realized that keeping plants healthy is hard work, so I built an AI model to look at spectral data (basically, colors we can't always see) to tell if a crop is **Healthy** or **Stressed**. Ideally, this helps farmers save water, fertilizer, and time! 🌍💧

---

## 🧐 What is this?
This is a Machine Learning application that analyzes **Multispectral Data** from farm fields. By looking at vegetation indices like **NDVI** (Normalized Difference Vegetation Index), my model can predict the health status of crops without needing someone to walk to every single plant.

### 🎯 Key Objectives:
*   **Analyze Data:** Understand index values like NDVI, GNDVI, SAVI, and EVI.
*   **Train a Brain:** Teach a `RandomForestClassifier` to spot the difference between healthy and stressed plants. 🧠
*   **Visualize:** Create cool heatmaps of the field to show exactly where the problem areas are. 🗺️
*   **Act:** Suggest precision strategies (like where to water more!).

---

## 🛠️ The Tech Stack (My Toolkit)
Here is what I used to build this:
*   **Python** 🐍 (The language of AI!)
*   **Pandas & NumPy** 🐼 (For crunching the numbers)
*   **Matplotlib & Seaborn** 🎨 (For making pretty charts)
*   **Scikit-Learn** 🤖 (The ML brain power)
*   **Jupyter Notebook** 📓 (Where the magic happens)

---

## 🚀 How to Run "My First AI Agronomist"

1.  **Clone this repo** (Get the code on your machine).
2.  **Install dependencies**:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Open the Notebook**:
    Launch `AI Based Crop Health Capstone.ipynb` in Jupyter.
4.  **Run the Cells**:
    Watch as the data loads, the model learns, and the maps are generated! 

> *Note: Make sure `main.csv` is in the same folder, or the code will get confused! 📁*

---

## 📊 My Results
After training my model (and ensuring I didn't overfit! 😅), here is what I achieved:
*   **Accuracy:** ~92% (Not bad for a student, right?!)
*   **Precision/Recall:** High scores for both "Healthy" and "Stressed" classes.
*   **Visuals:** Generated a side-by-side heatmap showing the actual NDVI values vs. what my model predicted.

---

## 🤖 Future Learning
I'm still learning, but here is what I want to add in **Version 2.0**:
*   ❌ **No more clouds:** Figure out how to handle cloudy satellite images.
*   📸 **Drone Power:** Integrate real drone imagery instead of just CSV data.
*   📈 **Time Travel:** Use Time-Series data to track plant growth over weeks!

---

*Thanks for checking out my project! If you have any feedback, let me know! I'm constantly "optimizing my weights" to be better!* 😉

**Status:** `Completed` ✅  
**Mood:** `Excited` 🤩
