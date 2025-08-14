# 🚗 Electric Vehicle Data Analysis & Insights

## 📌 Project Overview
This project analyzes a dataset of electric vehicles (EVs) to uncover meaningful insights, test hypotheses, and provide actionable recommendations.  
The dataset contains detailed specifications such as **electric range**, **energy consumption**, **price**, and other technical attributes.  

The goal is to:
- Conduct thorough data analysis.
- Perform hypothesis testing.
- Build an **EV recommendation system**.
- Present actionable recommendations for customers and stakeholders.

---

## 📂 Dataset
**File:** `FEV-data-Excel.xlsx`

**Key Columns:**
- **Car full name** – Complete designation (make, model, variant).
- **Make** – Manufacturer/brand of the car.
- **Model** – Specific car model.
- **Minimal price (gross) [PLN]** – Minimum retail price in Polish złoty.
- **Engine power [KM]** – Engine output in horsepower.
- **Maximum torque [Nm]** – Peak torque in Newton-meters.
- **Type of brakes** – Braking system type (e.g., disc, drum).
- **Drive type** – Drivetrain (FWD, RWD, AWD).
- **Battery capacity [kWh]** – Total battery capacity.
- **Range (WLTP) [km]** – Driving range under WLTP standards.
- **Wheelbase [cm]**, **Length [cm]**, **Width [cm]**, **Height [cm]** – Vehicle dimensions.
- **Minimal empty weight [kg]**, **Permissible gross weight [kg]**, **Maximum load capacity [kg]** – Vehicle weight specifications.
- **Number of seats**, **Number of doors** – Passenger configuration.
- **Tire size [in]** – Tire diameter in inches.
- **Maximum speed [kph]** – Top speed.
- **Boot capacity (VDA) [l]** – Cargo space.
- **Acceleration 0-100 kph [s]** – Acceleration time.
- **Maximum DC charging power [kW]** – Fast charging capability.
- **Mean - Energy consumption [kWh/100 km]** – Average energy use per 100 km.

---

## 🛠 Tools & Libraries
- **Python**  
- **Libraries:**
  - pandas, numpy → Data processing
  - matplotlib, seaborn → Data visualization
  - scipy.stats → Hypothesis testing
- **Environment:** Jupyter Notebook

---

## 📦 Tasks & Deliverables

### **Task 1 – EV Filtering & Grouping**
**Objective:** Help a customer with a **budget of 350,000 PLN** and a **minimum range of 400 km**.
1. Filter EVs meeting the criteria. *(2 Marks)*
2. Group the filtered EVs by manufacturer (**Make**). *(6 Marks)*
3. Calculate the **average battery capacity** for each manufacturer. **

---

### **Task 2 – Outlier Detection**
- Identify EVs with unusually **high or low energy consumption** (`Mean - Energy consumption [kWh/100 km]`). **

---

### **Task 3 – Relationship Analysis**
- **a)** Create a plot showing the relationship between **Battery Capacity** and **Range (WLTP)**. *(8 Marks)*  
- **b)** Highlight insights from the visualization. *(8 Marks)*

---

### **Task 4 – EV Recommendation System**
- Build a **class-based recommendation system** that:
  1. Accepts **budget**, **desired range**, and **battery capacity** as inputs.
  2. Returns the **top 3 EVs** matching the criteria. **

---

### **Task 5 – Hypothesis Testing**
**Objective:** Determine if there’s a **significant difference** in **average engine power (KM)** between **Tesla** and **Audi**.
- Perform a **two-sample t-test** using `ttest_ind` from `scipy.stats`. **
- Draw insights from the results.

---

## 📊 Recommendations & Conclusion
- Summarize findings from the analysis.
- Provide **customer-oriented recommendations** for EV selection.
- Suggest **manufacturer strategies** for improving competitiveness.


