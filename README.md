# Temperature Data Analysis (OOP & Modularity)

![MICROSOFT](https://img.shields.io/badge/MICROSOFT-blue?style=for-the-badge&logo=microsoft)
![PYTHON DEVELOPMENT](https://img.shields.io/badge/PYTHON_DEVELOPMENT-3776AB?style=for-the-badge&logo=python&logoColor=white)

This repository contains a technical implementation for processing thermal sensor data, focusing on **modularity** and object-oriented design principles as part of the **Microsoft Python Development certification**.


## 🎯 Project Goal

The primary goal of this project was to transform a procedural workflow into a **modular** system. The `TemperatureData` class was designed to centralize analysis logic, allowing each sensor instance to manage its own readings and calculations independently.


## 💡 Key Skills Demonstrated

* **Modular Design (Encapsulation):** The class acts as a self-contained module that groups both data (readings) and behavior (analytical methods).
* **Object Instance Management:** Ability to manage multiple sensor objects, each maintaining a unique state and data context.
* **Data Processing:** Implementation of algorithms to derive key statistical insights from raw data:
    * **Average Calculation:** Uses the formula $$Average = \frac{\sum Readings}{n}$$
    * **Extreme Value Identification:** Dynamic detection of maximum and minimum values through `max()` and `min()` methods.
    * **Range Analysis:** Internalized logic to determine thermal variability directly from the object's state.

  
## 📂 Files Info:

* `temperature_data_analysis.ipynb` — The main Jupyter Notebook containing the complete code and execution output.
