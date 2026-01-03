# 📊 Financial Data Analysis Project (Python & Power BI)

## 📝 Project Overview
هذا المشروع يقدم تحليلاً شاملاً لبيانات مالية (وهمية) تهدف لمراقبة الميزانية والإنفاق الفعلي للأقسام المختلفة. تم استخدام **Python** كأداة أساسية لمعالجة البيانات وحساب المؤشرات المالية، و **Power BI** لعرض النتائج بشكل تفاعلي.

## 🛠️ Tech Stack
- **Python**: (Pandas, Numpy) لعمليات الـ ETL (استخراج، تحويل، تحميل).
- **Power BI**: لتصميم لوحة التحكم (Dashboard).
- **Google Colab**: كبيئة عمل لتطوير الأكواد.

## 🚀 Key Features (ما تم إنجازه)
- **Data Cleaning**: تنظيف البيانات من القيم المفقودة والتكرارات.
- **Feature Engineering**: إضافة أعمدة حسابية متقدمة باستخدام Python بدلاً من DAX (مثل Variance و Spending Ratio).
- **Financial Status**: تصنيف تلقائي للأقسام إلى (Over Budget) أو (Within Budget).

## 📂 Project Structure
- `Scripts/`: يحتوي على كود Python الكامل للمعالجة.
- `Data/`: يحتوي على ملف `PowerBI_Final_Project.csv` الجاهز للتحليل.
- `Screenshots/`: صور للوحة التحكم التفاعلية.

## 💡 How to use
1. قم بتشغيل كود البايثون في مجلد `Scripts`.
2. استورد الملف الناتج في برنامج Power BI.
3. استخدم الأعمدة الجاهزة (`Status`, `Variance`) لبناء الرسوم البيانية فوراً.

4. # 📊 Financial Budget & Spending Analysis Dashboard

## 📝 Project Overview
This project focuses on analyzing financial data to monitor budget compliance across various departments. By leveraging **Python** for data processing and **Power BI** for visualization, this dashboard provides actionable insights into spending patterns, variances, and department performance.

## 🛠️ Tech Stack
- **Python**: Used for data generation, cleaning, and feature engineering (Pandas, Numpy).
- **Power BI**: Used for creating an interactive visual dashboard.
- **Google Colab**: Environment used for developing the Python processing script.

## 🚀 Data Processing (Python Side)
Since Power BI can be limited on certain systems (like macOS), I handled all the complex business logic in Python. This includes:
- **Data Cleaning**: Handled missing values and removed duplicates.
- **Feature Engineering**: Created custom metrics like:
  - `Variance`: Budget - Actual Spending.
  - `Spending_Ratio_%`: (Actual Spending / Budget) * 100.
  - `Status`: Categorizing departments as **'Over Budget'** or **'Within Budget'**.
- **Time Analysis**: Extracted months and years for dynamic filtering.

## 📊 Key Insights from Dashboard
- Identification of departments consistently exceeding their budget.
- Monthly trends of actual spending vs. planned budget.
- Percentage distribution of budget status across the organization.

## 📂 Repository Structure
- `data/`: Contains the final processed CSV file.
- `scripts/`: Python notebook/script for data preparation.
- `screenshots/`: Visuals of the Power BI dashboard.
- `README.md`: Project documentation.

## 💡 How to Run
1. Run the Python script in the `scripts/` folder to generate the latest `PowerBI_Final_Project.csv`.
2. Open the CSV file in **Power BI**.
3. Use the pre-calculated columns (`Status`, `Variance`, `Spending_Ratio_%`) to build visuals instantly.
