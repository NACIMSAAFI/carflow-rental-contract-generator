# 🚗 Carflow Rental Contract Generator

A web-based application to instantly generate **professional car rental contracts** with support for driver details, vehicle information, accessories checklist, and automatic PDF export.  

This project is designed as a practical tool for **small car rental agencies** that often rely on paper contracts, where human errors (incorrect details, missing fields, unreadable handwriting) are common.  

With Carflow Rental, contracts are **digitized, standardized, and error-free**, while still keeping the traditional **car diagram** for marking damages with a pen when the contract is printed. The contract structure also follows the **Tunisian rental car regulations**, making it directly usable for agencies in Tunisia.  

---

## 💡 Background & Motivation

While working in a rental car agency, I observed frequent problems with **manual paper contracts**:  
- Details were sometimes missing or written incorrectly.  
- Handwritten contracts slowed down the process and looked unprofessional.  

**Carflow Rental** was built as a solution to these issues:  
- Automate the creation of rental contracts.  
- Align with the **Tunisian legal framework** for car rental agreements.  
- Keep the process familiar for agencies but **reduce errors** and improve efficiency.  

---

## ✨ Features

- 📄 **Generate rental contracts in PDF** with one click  
- 🧑‍🤝‍🧑 Support for **primary and secondary drivers**  
- 🚘 **Vehicle details** (make, registration, mileage, etc.)  
- 📋 **Accessories checklist** (radio, spare wheel, jack, etc.)  
- 📝 **Condition notes** (before and after rental)  
- 🖼️ **Upload car diagram** (before and after rental)  
  - The diagram acts as a **visual template** of the vehicle.  
  - When the PDF contract is printed, users can **mark damages manually with a pen**, just like traditional rental contracts.  
- 💵 **Automatic calculation of rental price** (days × daily rate + extras)  
- 💳 **Payment details** (method, currency, guarantee amount)  
- ✍️ **Signature section** for client and agency  
- 🌐 **Bilingual output (French / Arabic)**  

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / JavaScript**  
- [jsPDF](https://github.com/parallax/jsPDF) – PDF generation  
- [html2canvas](https://github.com/niklasvh/html2canvas) – Capture DOM elements as images  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/carflow-rental.git
cd carflow-rental
```

### 2. Open in browser
Just open the Carflow_rental.html file in any modern browser.

## 📂 Project Structure
```bash
carflow-rental/
│── Carflow_rental.html   # Main application file
│── Car-image.jpg         # Vehicle diagram template
│── README.md             # Project documentation
```

## 💡 Possible Improvements
Add a backend (Flask/Node.js) to store contracts in a database

Export in DOCX/Excel formats

Add multi-user authentication

Enhance mobile responsiveness

Implement a drawing tool on top of the car diagram so damages can be marked digitally before PDF export

## 👨‍💻 Author
Developed by *Nacim Saâfi*
📍 Tunis, Tunisia

## 📜 License
This project is licensed under the MIT License – feel free to use and adapt it.