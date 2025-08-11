# 🛒 Store Payment System (Tkinter + Python)

A **store payment system** built with **Python Tkinter** that simulates adding items to a shopping cart and paying via multiple methods — **Cash**, **Credit Card**, or **Online Payment (Gcash/Paymaya)**.

---

## 📦 Features
- **Item Selection**:
  - Click buttons to add products to the cart.
- **Cart Management**:
  - Remove selected items from the cart.
  - Reset the entire cart.
- **Payment Methods**:
  - **Cash Payment**: Calculates change based on the amount entered.
  - **Credit Card Payment**: Validates card number, expiry, and CVV before approval.
  - **Online Payment**: Displays a QR code for scanning and confirming payment.
- **Dynamic Total**: Automatically updates when items are added or removed.

---

## 📂 Project Structure

- main.py # Main Tkinter application
- qr.png # QR code image for online payment (optional)
- README.md # Documentation file


> **Note:** If `qr.png` is missing, the system will display "[QR Code Missing]" in the online payment window.

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- **Python 3.x** installed on your system.
- Required dependency:
```bash
pip install pillow
python3 main.py
```
---
## 🖥️ How to Use
1. **Choose Items**: Click the buttons on the left to add products to your cart.

2. **Check Cart**: Review your cart contents and total in the middle section.

3. Choose Payment Method:
- * Cash → Enter the paid amount → Get change.
- * Credit Card → Enter card details → Simulated approval.
- * Online Payment → Scan QR code → Confirm.
4. **Complete Transaction**: Upon successful payment, the cart resets.

---

## 🖼️ Example Screenshot

---

## 📝 Notes
- If `qr.png` is missing, a placeholder message will be shown instead of the QR image.
- This application is for **demonstration purposes only** — no real transactions are processed.
- GUI is designed for basic use and may require adjustments for smaller screens.

---

## 👨‍💻 Author
**Creator:** Paul Mendoza   
**Created on:** August 11, 2025    
**Connect with Me:**  
* Facebook: [Paul Mendoza](https://www.facebook.com/mypaulmendoza/)
* Instagram: [Paul Mendoza](https://www.instagram.com/mypaulmendoza/)

---
## 📜 License
- This project is licensed under the MIT License — feel free to use, modify, and share.
  
---

Do you want me to also **generate a working `qr.png` file** so that the online payment simulation actually shows a QR code instead of the "[QR Code Missing]" warning? That would make your repo run perfectly without extra setup.
