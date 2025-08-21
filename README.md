# 📊 PDF Report Generator with Charts

This project generates a **stylized PDF report** using:
- **pandas** → data handling & KPIs  
- **matplotlib** → charts & visualizations  
- **reportlab** → PDF formatting & export  

The final PDF contains:
- Cover with title & subtitle  
- Key performance metrics (KPIs)  
- Line, bar, and pie charts  
- A sample data table  

---

## 🚀 Features
- Automatically creates KPIs like total revenue, units, average price, active days  
- Generates three charts:
  - **Daily Revenue Trend** (line chart)  
  - **Revenue by Category** (bar chart)  
  - **Category Contribution** (pie chart)  
- Exports everything into a clean, professional **multi-page PDF**

---

## 📂 Project Structure
├── report_generator.py # Main Python script
├── requirements.txt # Dependencies
├── sample_data.csv # Example dataset (optional)
├── output/
│ ├── Analytics_Report.pdf
│ ├── trend_line.png
│ ├── category_bar.png
│ └── category_pie.png
└── README.md


---

##  Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/pdf-report-generator.git
cd pdf-report-generator

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
