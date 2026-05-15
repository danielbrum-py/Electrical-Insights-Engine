# ⚡ Industrial Electrical Anomaly Engine

---

## 🧾 About the Project

This project focuses on the analytical processing of industrial electrical data to identify operational risks. Using Python, the system transforms raw inspection logs from Excel/CSV files into professional diagnostic PDF reports.

The main goal is to bridge the gap between complex electrical metrics (current, voltage, power) and actionable maintenance insights, highlighting critical equipment that requires immediate intervention.

---

## 🎯 Analysis Objectives

- **Identify Overload Patterns:** Detect equipment operating above nominal capacity.
- **Current Deviation Analysis:** Compare measured vs. expected currents to find phase imbalances or leakages.
- **Risk Categorization:** Classify equipment status into **CRITICAL**, **WARNING**, and **NORMAL**.
- **Power Monitoring:** Evaluate the power distribution across different industrial assets.
- **Automated Reporting:** Generate a structured PDF document with executive summaries and technical charts.

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Pandas:** For data wrangling and cleaning.
- **Matplotlib:** For technical plotting and dashboard assembly.
- **Matplotlib (PdfPages):** For multi-page PDF report generation.

---

## 🧱 Project Stages

### 1. 📥 Data Extraction
- Multi-source data loading (Excel sheets and CSV exports).
- Handling datasets for **Overload**, **High Voltage**, and **Abnormal Current**.

### 2. 🧹 Data Cleaning & Wrangling
- Filtering null values and removing inconsistent entries.
- Logic-based categorization of status (Critical/Warning/Normal).
- Conversion of electrical units for standardized reporting.

### 3. 📊 Technical Data Analysis
- Calculation of **Overload Percentages** using nominal vs. measured current.
- **Power Analysis** calculation for different equipment types.
- Absolute value adjustment for negative deviations (operational margin analysis).

### 4. 📈 Visualization & Dashboarding
- **Bar Charts:** Equipment status distribution.
- **Pie Charts:** Percentage of assets requiring attention.
- **Comparative Plots:** Nominal Current vs. Measured Current.
- **Horizontal Bar Charts:** Power consumption and overload levels by asset.

### 5. 📄 Automated PDF Reporting
- Creation of a **Technical Title Page**.
- **Executive Summary:** Automated text reflecting real-time data counts.
- **Visual Appendix:** Integration of all generated plots.
- **Data Table:** Final diagnostic table attached to the report.

---

## 📷 Visualizations & Results

### 📄 Final Technical Report (Sample)
The script outputs a multi-page PDF (`final_technical_report.pdf`) ready for stakeholder review.

---

## 🔍 Key Insights

- **Prioritized Maintenance:** The system automatically highlights "Motor 2" and "Industrial Lighting" as high-priority risks based on overload percentages.
- **Operational Safety:** By identifying current deviations, the engine detects potential failures (like short circuits or insulation loss) before they cause downtime.
- **Data Clarity:** Converting raw numbers into a color-coded PDF (Red/Green) allows non-technical managers to understand the plant's health instantly.

---

## 🚀 Future Roadmap (V2.0)

- **GUI Integration:** Adding a **Tkinter** interface to allow users to select files dynamically.
- **Interactive Dashboards:** Moving from static PDFs to interactive web panels using **Streamlit**.
- **Predictive Maintenance:** Implementing Machine Learning to predict the next equipment failure based on historical trends.
- **Real-time Alerts:** Automating email or WhatsApp notifications for "CRITICAL" status detection.

---

## 👨‍💻 Author

Project developed by **Daniel Brum** as part of a series focusing on Industrial Data Automation and Technical Analytics.
