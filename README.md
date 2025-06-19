# 📊 Excel to HTML Converter (Arabic Real Estate Listings)

This is a **Streamlit web application** that allows you to upload an Excel sheet and convert it into a fully styled, interactive HTML table — perfect for **real estate listings in Arabic** with support for **location** and **image buttons**.

---

## ✅ Features

- 📥 Upload `.xlsx` Excel files
- 🌐 RTL (right-to-left) Arabic layout with Tahoma font
- 📍 Detects `الموقع` hyperlinks and displays a **"📍 الموقع"** button
- 📷 Detects `صور` hyperlinks and displays a **"📷 صور"** button
- 🔎 Interactive DataTable with search, sort, and pagination
- 💾 Download the result as a complete `HTML` file

---

## 📁 Project Structure
├── app.py # Streamlit application
├── template_corrected.html # HTML template (styled with Arabic layout)
├── requirements.txt # Python dependencies
└── excel_to_html.ipynb # Optional Jupyter notebook for dev/testing


---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Osama4Alfaifi/Excel-to-HTML.git
cd Excel-to-HTML
```
pip install -r requirements.txt

python -m streamlit run app.py


📝 Excel Format Instructions
Your Excel file should meet these criteria:

Header row must be in the first row

16 columns only

Columns named الموقع or صور with hyperlinks will be converted into buttons

Empty rows are skipped automatically
