# Hi, I'm Aminat Adewuyi 👋
### Data Analyst | Business Intelligence Specialist

Welcome to my data portfolio! I specialize in turning raw data into actionable insights using advanced Excel modeling, data transformation, and dynamic dashboard design.

📬 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/aminatadewuyi) | [Email](mailto:aminatabdulwasiu88@gmail.com)

---

## 🚀 Featured Data Projects

---
## 📈 Case Study 1: Sales & Revenue Performance Intelligence Engine (Dual Excel & Python Project)
**Domain:** Commercial Retail Analytics & Business Intelligence  
**Core Technologies:** Python (Pandas) | Jupyter Notebook | Advanced Excel | Dynamic Slicers | Pivot Tables  

### 🖥️ Dashboard Visualization
![Sales Performance Dashboard](sales_dashboard_v1.JPG)
![Sales Performance Dashboard](sales_dashboard_v2.JPG)

### 📝 Project Overview
I built this comprehensive project during my training with Cyperdevs Technologies, the World Bank Group, and the Federal Ministry of Nigeria. To showcase my full analytical versatility, I approached this raw retail transaction dataset from two angles: I used **Python (Pandas)** in a Jupyter Notebook to programmatically ingest, clean, and run mathematical data transformations, and then I built an interactive **Excel Dashboard** with dynamic slicers for high-level stakeholder reporting.

🔗 **[View My Live Python Code & Jupyter Notebook on GitHub](https://github.com/aminat-aa/Sales-data-analysis-project/blob/main/sales_analysis.ipynb)**

### 🔍 My Analytical Insights & Project Breakdown
* **Programmatic Feature Engineering:** Using Python, I loaded the raw Excel files and engineered new calculated columns to establish financial metrics. I wrote logic to dynamically compute row-level costs and ultimate profitability by subtracting total expenses from revenue streams:
  `df['profit'] = df['Total_Revenue'] - df['Total_Cost']`
* **Product Revenue vs. Volume:** When I analyzed the product categories, I found that **Phones generate 55% of my total revenue**. Looking closer at consumer behavior, this makes sense because customers tend to upgrade their devices every 2 to 3 years. However, when looking at unit volume, **Accessories sold the most items overall**. This showed me that while phones bring in the large cash amounts, accessories act as a high-volume checkout attachment.
* **Quarterly Sales Trends:** I mapped out the profit and loss by quarter and noticed a major trend: **sales peaked sharply in Q2 but dropped significantly by Q4**. My revenue chart confirmed this, showing an increase in Q2 followed by a steady decrease starting in Q3. This taught me that the business is highly seasonal, meaning inventory needs to be managed carefully ahead of the Q4 dip.
* **Algorithmic Staff Performance Profiling:** Instead of just guessing who the top salesperson was, I used Python's aggregate grouping functions to sum up the net returns for every single staff member and isolate the absolute maximum earner:
  `top_Sales_Person = df.groupby('Sales_Person')['profit'].sum().idxmax()`
  The script successfully isolated **Hamilton** as the top-performing sales agent based on total profit, matching my visual Excel dashboard findings exactly.
* **Regional Performance & Slicers:** By tracking sales by location, I discovered that **Lagos State saw the highest sales increase**. Because of the massive population density in Lagos, there was a constant, heavy demand for phone accessories like chargers and screen protectors. I integrated **Dynamic Slicers** into the Excel side of this dashboard so that anyone viewing it can click through different regions or quarters to see the charts update instantly.

---

## 🛡️ Project 2: Fintech Customer Experience & Fraud Risk Analytics (Capstone)
**Core Technologies Used:** Power BI | DAX Formulas | Power Query | Customer Segmentation  

### 🖥️ Dashboard Visualization
![Fintech Capstone Dashboard](capstone.JPG)

### 📝 Project Overview
For my Capstone Project, I worked with a financial transactions dataset containing **2,512 entries and 16 different attributes**. I built this Power BI dashboard entirely from scratch to do two things: segment bank customers by their age and behaviors, and create an operational risk view to flag potential security threats and fraud indicators.

### 🔍 My Analytical Insights & Project Breakdown
* **ATM vs. Digital Usage:** I broke down transaction channel usage across ATM, Online, and POS options. My charts clearly revealed that **the physical ATM is the most popular transaction method** for this customer base. This insight is important because a heavy reliance on cash means higher physical infrastructure and card maintenance costs for the bank.
* **Age Group Segmentation:** I divided the customers into specific age cohorts and noticed clear behavioral patterns:
  * **Ages 18–30:** They make a high volume of frequent, lower-value transactions, mostly covering daily lifestyle expenses. However, I also spotted **unusually high-value transaction outliers** in this young adult group, which means their accounts need closer monitoring for sudden credit risks or fraud.
  * **Ages 30–50:** This group exhibited much higher average transaction amounts, which I tie to career growth, family management, and major bill payments.
* **Flagging Security Risks:** I wanted my dashboard to actively find security vulnerabilities, so I built logic to isolate **accounts with more than 3 failed login attempts**. This allows the security team to separate standard user forgetfulness from active brute-force hacking attempts. I also mapped out geographic data and found that **Colorado Springs was the most common transaction location** in the dataset.
* **My Recommendations:** Based on my findings, I recommended implementing automated alerts for transactions exceeding 3 standard deviations from a user's normal baseline. I also recommended creating targeted online cashback promotions to gently nudge the younger 18-30 demographic away from physical ATMs and onto digital banking channels.

---

## 📦 Project 3: Supply Chain & Supplier Performance Optimization
**Core Technologies Used:** Advanced Excel | Dynamic Slicers | Operational Quality Auditing  

### 🖥️ Dashboard Visualization
![Suppliers Performance Dashboard](suppliers_performance.PNG)

### 📝 Project Overview
I designed this Supply Chain Performance dashboard to help procurement teams audit their vendor networks. When a company relies on outside vendors, delays and bad parts cost money. I built this tool to track exactly which suppliers are delivering on time, which ones are sending defective parts, and where our supply chain risks are located.

### 🔍 My Analytical Insights & Project Breakdown
* **Delivery & Lead Time Latency:** When I calculated the **Average Lead Time by Supplier**, the data showed a massive split. While some vendors consistently hit their deadlines, others had chronic, recurring delays. I traced these delays back and found they were heavily linked to specific geographical regions and complex material orders. 
* **Manufacturing Quality Issues:** I looked at the **Average Defect Rate by Supplier** to see who was delivering clean work. The charts revealed that certain suppliers have unacceptably high defect rates, which are also concentrated in specific manufacturing regions. This drains company margins because of return shipping costs and production downtime.
* **Interactive Design & Slicers:** Just like my sales project, I built this in Excel using **Dynamic Slicers** so that managers can instantly filter the supplier data by region, defect level, or lead time to see who our best and worst partners are.
* **My Recommendations:** I recommended creating a supplier tiering matrix to route more orders to our reliable "Tier A" vendors. I also recommended adding strict delivery agreements into future vendor contracts and holding a "buffer stock" of critical raw materials so a supplier delay doesn't stop our entire operation.

---

## 🎓 Project 4: 2024 JAMB Performance Analysis Dashboard
**Core Technologies Used:** Power BI | DAX Formulas | Public Sector Education Modeling  

### 🖥️ Dashboard Visualization
![JAMB Performance Dashboard](jamb_performance_2024_v1.jpg)
![JAMB Performance Dashboard](jamb_performance_2024_v2.jpg)

### 📝 Project Overview
In this public sector project, I analyzed a dataset containing **5,000 national student examination records for JAMB**. I wanted to move away from commercial business metrics and look at social data. I built this Power BI dashboard to find the exact socio-economic, school-level, and study habits that determine whether a student succeeds or struggles on high-stakes national exams.

### 🔍 My Analytical Insights & Project Breakdown
* **The Location and Income Gap:** When I looked at regional performance, the data showed that **students in urban areas achieved the highest maximum scores**. This clearly points to regional inequalities and a severe lack of resources or facilities in rural areas. Furthermore, when comparing family backgrounds, students from high socio-economic statuses had a **50.39% average score**, while low socio-economic students averaged **49.61%**. This 0.78% difference proves how heavily household income levels impact a student's preparation.
* **Isolating What Actually Makes Students Succeed:** I wanted to see what drivers actually help students cross the elite 300-point mark. My analysis found that **50% of the students who scored above 300 points had direct access to extra tutorials**. Additionally, students who committed to **26 hours or more of independent study per week** routinely scored over 300. 
* **School Type & Teacher Influence:** When I checked the types of schools, I found that private schools have drastically higher access to learning materials than public ones. More importantly, my charts showed a direct link between teacher ratings and student scores—low-quality teacher ratings severely dragged down student performance averages.
* **My Recommendations:** I used these insights to write actionable recommendations for education policymakers. I proposed that the government subsidize modern learning materials for disadvantaged schools in rural areas, establish free remedial tutorial programs for lower-income students, and create mandatory training programs to upskill poorly-rated teachers.
