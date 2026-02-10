# Day 2 – Understanding Descriptive Statistics & Measures of Spread

**What I worked on today:**  
- Basics of statistics for data analytics  
- Descriptive statistics: **mean, median, mode**  
- Measures of spread: **variance, standard deviation, interquartile range (IQR)**  
- Worked through a small dataset by hand to understand these concepts  

---

## Example Dataset (Hospital stays in days)
Data set: 1, 2, 2, 3, 5, 7, 20

### Step 1: Median (Q2)
- Middle value = 4th number = **3**

### Step 2: Split lower and upper halves
- **Lower half** (1, 2, 2) → Q1 = 2  
- **Upper half** (5, 7, 20) → Q3 = 7  

### Step 3: Interquartile Range (IQR)
- **IQR = Q3 − Q1 = 7 − 2 = 5**

### Step 4: Outlier Check
- Q3 + 1.5×IQR = 7 + 7.5 = 14.5 → 20 > 14.5 → **20 is an outlier**  

---

## Key Takeaways
- **Mean** can be influenced by extreme values; **median** shows the “typical” value  
- **IQR** captures the middle 50% of the data and is robust to outliers  
- Use **mean + SD** when data is fairly symmetrical and has no extreme values  
- Use **median + IQR** when data is skewed or has outliers  
- Working through the calculations by hand helped me **see why these measures matter** before using any tools  

---

## Reflection
> Doing this manually made me realize that **numbers alone don’t tell the story**-how data is spread matters just as much as the center. Understanding this foundation makes me feel more confident moving into tools and real datasets.
