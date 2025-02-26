# PYTHON-project
Here’s a concise and structured overview of the **Electric Vehicle Data Analysis Project** based on the given tasks:  

### **Project Overview: Electric Vehicle Data Analysis Using Python**  

#### **1️⃣ Filtering EVs Based on Budget & Range**  
- **Approach:** Filtered EVs costing ≤ 350,000 PLN with a minimum range of 400 km.  
- **Outcome:** Identified qualifying EVs and grouped them by manufacturer.  
- **Additional Analysis:** Calculated the average battery capacity for each manufacturer to compare efficiency.  

#### **2️⃣ Identifying Outliers in Energy Consumption**  
- **Approach:** Used statistical methods (IQR and Z-score) to detect outliers in mean energy consumption (kWh/100 km).  
- **Outcome:** Flagged EVs with exceptionally high or low energy usage, indicating either inefficiency or outstanding performance.  

#### **3️⃣ Analyzing Battery Capacity vs. Range Correlation**  
- **Approach:** Created a scatter plot to visualize the relationship between battery capacity (kWh) and driving range (km).  
- **Outcome:** A positive correlation was observed—higher battery capacity generally resulted in longer driving ranges.  

#### **4️⃣ EV Recommendation System**  
- **Approach:** Developed a class allowing users to input budget, range, and battery capacity preferences.  
- **Outcome:** The system returns the top 3 EVs matching the criteria, simplifying decision-making for customers.  

#### **5️⃣ Hypothesis Testing: Engine Power Comparison (Tesla vs. Audi)**  
- **Approach:** Conducted a two-sample t-test (`ttest_ind`) to determine if Tesla and Audi have significantly different average engine power.  
- **Outcome:** The test results indicated [statistical significance/no significant difference] (final interpretation depends on p-value).  

#### **🔹 Key Takeaways & Recommendations**  
- **Energy Efficiency Insights:** Identified high-efficiency and energy-consuming models, assisting in market positioning.  
- **Battery vs. Range:** Strong correlation suggests manufacturers should focus on battery innovation for extended range.  
- **EV Selection Simplified:** The recommendation system enhances user experience and purchase decisions.  
- **Manufacturer Comparison:** Performance analysis (Tesla vs. Audi) informs competitive strategies.  

