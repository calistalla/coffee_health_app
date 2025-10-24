# ☕ Global Coffee & Health Dashboard

This interactive **Streamlit dashboard** explores the relationship between **coffee consumption** and various **health metrics** such as BMI, heart rate, and sleep hours.  
Users can filter by age, country, gender, and smoking status to dynamically view data, correlations, and statistical comparisons.

---

##  Features

###  Sidebar Filters
 1. **Age range selector** — filter participants by age.  
 2. **Country multiselect** — compare across selected countries.  
 3. **Gender filter** — focus on male, female, or all participants.  
 4. **Smoker filter** — restrict data to smokers only.

###  Problem A: Coffee vs. Health Metrics
 Scatter plots showing:
   1. **Coffee intake vs. BMI**
   2. **Coffee intake vs. Heart Rate**
 Pearson correlation table for `Coffee_Intake`, `BMI`, `Heart_Rate`, and `Sleep_Hours`.

###  Problem B: Group Differences
 1. Bar plot of **average coffee intake by country**.  
 2. Histogram of **sleep hours distribution**.  
 3. Summary statistics table by country.  
 **ANOVA test** comparing coffee intake between countries.

---

##  Insights Example

1. Higher coffee intake shows **moderate correlation** with **BMI** and **Heart Rate**.  
2. Sleep duration tends to **slightly decrease** with higher coffee intake.  
3. Significant **cross-country differences** exist in coffee consumption patterns.  

---

##  Dataset
The app reads from an csv file named `synthetic_coffee_health_10000.csv`.

---

## How to run this app
open<https://coffeehealthapp-aqna9vvkgqj5r6rljnrmvr.streamlit.app/#average-coffee-intake-by-country>
