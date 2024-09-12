# 𝐇𝐑 𝐚𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐟𝐨𝐜𝐮𝐬𝐢𝐧𝐠 𝐨𝐧 𝐄𝐦𝐩𝐥𝐨𝐲𝐞𝐞𝐬 𝐀𝐭𝐭𝐫𝐢𝐭𝐢𝐨𝐧

This is an End-to-End Power BI project I completed by following tutorial on YouTube. It helped me gain a deeper understanding of using DAX, creating measures, and adding calculated columns to meet the specific needs of the analysis. This project allowed me to practice and sharpen my Power BI skills effectively.

## About project

This HR Analytical Dashboard provides an in-depth analysis of employee attrition across multiple dimensions such as job role, education field, salary, age, tenure, and gender.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an Excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution" & "column quality".
- Step 3 : Checked the datatype and change it according to the columns. Also, renamed some of the columns.
- Step 4 : Next, using the conditional column - added 3 columns,i.e., 
1. Attrition_count
2. Age group
3. Salary slab
- Step 5 : After tranforming the data, closed the Power query editor by applying the changes made.
- Step 6 : Added the theme and selected the background image which was made with the help of Powerpoint.
- Step 7 : To highlight the KPI's (Empolyee count, Avg Age, Attrition, Attrition rate, Avg salary, Avg Working year and Avg years at company), used the Card visuals. And to calculate the Attrition rate, used the measures and DAX functions,i.e., 
    
        Attrition_rate = SUM(Worksheet[Attrition_count])/SUM(Worksheet[EmployeeCount])
- Step 8 : Added the other visuals to the dashboard which are as foloowed - 
        
        1. Filter visual representing "Department"
        2. Area chart visual representing Attrition by Years at company
        3. Stacked column chart visual representing Attrition by Working years
        4. Donut chart visual representing Attrition by Education Field
        5. Pie chart visual representing Attrition by Gender
        6. Stacked bar chart visual representing Attrition by Salary slab & Age group 
        7. Matrix visual representing Attrition by Jobe role & Job satisfaction 

- Step 9 - Doing the formatting of the visuals- using the format painter to apply them to the other visuals.
- Step 10- Once the dashboard was ready the next step was to publish it on the Power Bi service.

### Dashboard Link :https://app.powerbi.com/view?r=eyJrIjoiNTI3MjY2NmYtOTRkZi00NWQ2LThlYjctMTE4NWFmMmQyYTViIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

# Insights
The company has a total of 1,470 employees with an average age of 37 years and an average tenure of 11 years. The overall attrition rate stands at 16.12%, with significant attrition observed in the Sales and Laboratory Technician roles, and among employees in the early stages of their careers or with lower salaries. Life Sciences and younger employees (26-35 years) also exhibit higher attrition rates. 

Here are the detailed key insights: 💡

    1. Attrition by Job Role: 👨🏻🔧
        ▪ Highest attrition in Laboratory Technician (62 employees) and Sales Executive (57 employees)
        ▪ Least attrition in Research Director (2 employees) and Human Resources (12 employees).

    2. Attrition by Education Field: 📝
        ▪ Life Sciences has the highest attrition (63 employees).
        ▪ Technical Degree and Medical fields have relatively lower attrition.

    3. Attrition by Salary: 💸
        ▪ Majority of the attrition occurs in the salary slab of up to 5k (914 employees).
        ▪ Attrition significantly drops in higher salary slabs.

    4. Attrition by Age: 📊
        ▪ Highest attrition in the age group 26-35 years (606 employees).
        ▪ Lowest attrition in the age group above 46 years (17 employees).

    5. Attrition by Years at Company: ➕
        ▪ Most employees who leave have been with the company for around 1 year.
        ▪ Attrition drops significantly for employees with more than 3 years at the company.

    6. Attrition by Working Years: 📈
        ▪ Highest attrition for employees with 1 working year (125 employees).
        ▪ A notable attrition spike for employees with 9 years of working experience (81 employees).

    7. Attrition by Gender: 👫
        ▪ Males have a higher attrition count (150) compared to females (87).



