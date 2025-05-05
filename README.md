# Billing-Software-with-PDF-Invoice-Generation-using-Python-Tkinter-ReportLab-
This is a desktop-based billing system developed in Python using Tkinter for the GUI and ReportLab for generating professional GST-compliant PDF invoices. It is suitable for small shops or service providers needing quick and reliable invoice creation.

## 🧰 Features

- User-friendly GUI built with Tkinter
- Dynamic item entry with support for HSN codes, batch numbers, expiry dates, and more
- SGST, CGST, and IGST tax fields
- Automatic invoice numbering
- PDF invoice generation in landscape mode
- Total amount rounding off
- Amount in words included in the invoice
- Saves invoices to a local `Bills/` directory

## 🛠️ Technologies Used

- Python 3
- Tkinter (GUI)
- ReportLab (PDF generation)
- OS and Math (for file handling and rounding)

## 📂 Project Structure

```

.
├── billing\_Software.py       # Main GUI application
├── Bills/                    # Folder where generated invoices are saved

````

## ▶️ Getting Started

### Prerequisites

Install Python 3 and the following library:

```bash
pip install reportlab
````

### How to Run

```bash
python billing_Software.py
```

## 📄 Invoice Output

The generated PDF invoice includes:

* Shop details and branding
* Customer information and GST details
* Itemized billing with tax columns
* Footer with terms and conditions

## 👨‍💻 Author

**Venkata Taraka Nadh Nanduri**
📧 [tarakanadh99@gmail.com](mailto:tarakanadh99@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/venkata-taraka-nadh-nanduri-39a069294/)
💻 [GitHub](https://github.com/tarakanadhnanduri99)

