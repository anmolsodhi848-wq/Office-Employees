# Office-Employees

## Project Objective

Build an interactive dashboard using the HR dataset to analyze workforce demographics, compensation, and attrition trends for data-driven decision-making.

## Dataset
https://github.com/anmolsodhi848-wq/Office-Employees/blob/main/Employee%20Data.csv

## 📊 Key Performance Indicators (KPIs)

1. Total Employees
2. New Hires
3. Employees Exited / Attrition Count
4. Attrition Rate
5. Average Age
6. Average Salary
7. Average Bonus %
8. Headcount by Department
9. Headcount by Gender
10. Headcount by Ethnicity
11. Average Tenure (years)

## Process

1. **Data Import & Cleaning:** Loaded the Excel HR dataset into Tableau and performed basic cleaning such as renaming fields, correcting data types, and handling missing values.
2. **Data Preparation:** Created calculated fields (e.g., age bins, salary bins, attrition indicators) and organized dimensions and measures for analysis.
3. **Dashboard Development:** Built interactive charts and KPIs to visualize demographics, salary distribution, department-wise headcount, and attrition trends.
4. **Final Dashboard Design:** Combined all visuals into a user-friendly, interactive dashboard with filters to enable easy exploration of workforce insights.

## Dashboards

1. **Employee Demographics**
   <img width="1825" height="717" alt="image" src="https://github.com/user-attachments/assets/05ada5aa-732f-43e9-b9d4-df65beaa9bc7" />

2. **Role Composition Overview**
   <img width="1810" height="716" alt="image" src="https://github.com/user-attachments/assets/b4ef1209-6e92-43a5-afeb-1234017a0855" />

3. **Employee Salary Analysis**
   <img width="1822" height="732" alt="image" src="https://github.com/user-attachments/assets/ec1dec06-7233-492d-bfff-3330b92f950d" />

4. **Compensation and Bonus Overview**
   <img width="1827" height="737" alt="image" src="https://github.com/user-attachments/assets/a1933662-bdb2-4f6a-9e8c-8cc615302380" />

5. **Employee Diversity and Inclusion**
   <img width="1606" height="722" alt="image" src="https://github.com/user-attachments/assets/a37fba27-dd8e-4ced-a70e-9dda993c97a9" />

6.**Age and Experience Distribution**
   <img width="1857" height="950" alt="image" src="https://github.com/user-attachments/assets/e6693769-d36b-4e5d-8953-340edeace23b" />

7. **Hiring Trends**
   <img width="1838" height="728" alt="image" src="https://github.com/user-attachments/assets/f79a053d-2b12-418b-a30a-dcd54451f978" />

8.  **Attrition Overview**
   <img width="1828" height="732" alt="image" src="https://github.com/user-attachments/assets/6793c1ad-902b-428b-97b4-ae22b97a3bed" />


## Project Insights

🌎 **Employee Demographics & Distribution**

   1. **Total Headcount and Salary:** The company has a total of 911 employees with an Average Salary of 124,278.
   2. **Gender Ratio:** The Male to Female Ratio is 0.93, indicating a slightly higher number of female employees (495 Female vs. 460 Male, as seen in Images 2, 3, 4, 5, 6, 7, 8).
   3. **Country Origin:** The majority of employees are in the United States (599), followed by China (214) and Brazil (98).
   4. **Top Departments:** The largest departments by headcount are IT (238), Engineering (158), and Sales (140).
   5. **Top Business Units:** The largest business units are Manufacturing (261), Speciality Products (256), and Corporate (229).

📈 **Hiring and Attrition**

   1. **Hiring Trend:** There is a clear upward trend in the number of hires, with a significant increase in the later years. The number of hires jumped from 17 in 2017 to a peak of 50 in 2021.
   2. **Department Hiring:** IT has the highest number of overall hires, significantly surpassing other departments.
   3. **Exit Trend:** Employee exits have also generally trended upward, peaking at 20 exits in 2020 and decreasing slightly to 7 in 2022.
   4. **Attrition by Department/Business Unit:**
      1. Marketing has the highest number of total exits (14), followed by Engineering (11) and IT (11).
      2. Exits are distributed across Business Units, with Research & Development and Speciality Products frequently appearing alongside Corporate and Manufacturing for most departments. Marketing, in particular, shows 6 exits in R&D and 4 in Corporate.

💰 **Salary, Bonus, and Role Composition**

   1. **Overall Average Salary:** The average annual salary is 124,278.
   2. **Salary by Department:**
      1. Accounting has the highest average annual salary (123,147).
      2. IT has the lowest average annual salary (97,790).
   3. **Bonus by Department:**
      1. IT has the highest average bonus percentage (0.12425).
      2. Accounting has the lowest average bonus percentage (0.07165).
   4. **Business Unit Average Salary**: Corporate has the highest average annual salary (120,776).
   5. Employee Positions: The company structure is top-heavy, with the highest number of employees in senior roles: Director (120), Sr. Manager (109), and Vice President (104).

🧑‍🤝‍🧑 **Age, Gender, and Ethnicity Distribution** 

   1. **Gender Distribution:** The workforce is relatively balanced: 495 Female and 460 Male.
   2. **Ethnicity Distribution:** The largest ethnic groups are Asian (388) and Caucasian (264), followed by Latino (246).
   3. **Age Distribution:** The two largest age cohorts are 45 (151 employees) and 55 (126 employees), suggesting a predominantly middle-aged and experienced workforce.
   4. **Department Average Age:** Engineering has the highest average employee age (45.671), while Marketing has the lowest (43.217).


## Conclusions

1. **Experienced and Growing Workforce:** The company has a mature, experienced employee base (high counts in senior roles/older age cohorts) and is in a rapid growth phase, with IT being the largest department and the focus of recent significant hiring.
2. **Varied Compensation Strategy:** A clear inverse relationship exists between base salary and bonus: Accounting has the highest average salary but lowest bonus, while IT has the lowest salary but the highest bonus, indicating differing compensation philosophies by department.
3. **Moderate Attrition Risk:** While overall growth is high, exits have trended up, peaking recently. Marketing shows the highest number of total exits, warranting focused retention efforts.


## Future Scope

1. **Develop Predictive Attrition Models:**
   1. **Action:** Leverage the existing Attrition Overview data to build a predictive model that identifies employees "at risk" of leaving (especially in Marketing, Engineering, and IT).
   2. **Goal:** Shift from reacting to exits to proactive intervention (e.g., targeted engagement surveys, mentorship, or compensation reviews) before a resignation occurs.

2. **Integrate Performance and Compensation Data:**
   1. Action: Overlay salary and bonus data with individual performance ratings, customer satisfaction scores, or sales data (e.g., Revenue per Employee).
   2. Goal: Determine the ROI of Compensation and validate the current inverse salary/bonus structure to ensure high performers in high-turnover areas (like IT) are being adequately rewarded relative to their business impact.

3. **Conduct Strategic Workforce Planning for Senior Roles:**
   1. **Action:** Given the high concentration of employees in the 45 and 55 age cohorts and senior roles (Director/VP), create "what-if" scenarios to forecast organizational structure and skill gaps over the next 5-10 years.
   2. **Goal:** Proactively identify key roles facing retirement risk and initiate succession planning, targeted upskilling programs, or external recruiting strategies to secure the next generation of leadership.

4. **Deepen Diversity, Equity, and Inclusion (DEI) Analysis:**
   1. **Action:** Drill down into the existing Gender/Ethnicity data by role and salary band (e.g., "Pay Equity Analysis").
   2. **Goal:** Identify any pay or promotion disparities across departments or roles for different gender and ethnic groups, ensuring the company's commitment to DEI is measurable and actionable across all levels of the experienced workforce.


## Recommendations

1. **Address Compensation Discrepancies and IT Retention:**
   1. **Action:** Review the compensation structure, specifically focusing on the low base salary in IT ($97,790), despite its high average bonus and high hiring volume. Conduct a market rate comparison for IT roles.
   2. **Goal:** Rebalance the pay mix to increase the base salary for IT staff to remain competitive, reducing reliance solely on variable bonuses, which can be a retention risk for a critical, high-growth department.

2. **Implement Targeted Retention Program for Marketing and Engineering:**
   1. **Action:** Launch immediate, department-specific engagement and retention initiatives for Marketing (highest total exits) and Engineering (highest average age). This could include stay interviews, leadership development, or flexible work policies.
   2. **Goal:** Stabilize the turnover rate in Marketing and leverage the high average experience in Engineering through mentorship programs to transfer institutional knowledge before potential senior-level attrition.

3. **Develop a Strategic Succession and Talent Pipeline:**
   1. **Action:** Formalize a succession planning process focusing on the large cohorts of experienced employees (ages 45 & 55) and high-level roles (Director, Sr. Manager, VP).
   2. **Goal:** Mitigate future organizational risk from a high rate of senior retirements. This ensures a healthy pipeline by identifying and developing the next generation of leaders from the younger, growing cohorts.

4. **Optimize Global and Unit-Specific Resource Allocation:**
   1. **Action:** Analyze the performance and efficiency (e.g., revenue per employee) of the largest Business Units (Manufacturing, Specialty Products) and the secondary geographic locations (China, Brazil) compared to the US.
   2. **Goal:** Ensure that resource allocation (headcount, capital investment) is aligned with the highest-performing and most strategically important business units and geographic regions for the company's long-term global strategy.
