
# 🛒 Supermarket Billing System

A simple Supermarket Billing System built in Python using Jupyter Notebook.  
It allows users to enter item names and quantities, fetches prices from a predefined price list, applies discounts, calculates totals, and generates an itemized receipt.

## 🚀 Features
- Predefined price list for items.
- Enter only item name + quantity (price is auto-fetched).
- Subtotal, discount, and final bill calculation.
- Discounts:
  - 5% if bill ≥ ₹200
  - 10% if bill ≥ ₹500
- Itemized receipt display.

## 📂 Project Files
- `Supermarket_Billing_System.ipynb` → Jupyter Notebook with code & explanations
- `README.md` → Documentation file

## ⚡ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/AkshaySolanki-DA/Supermarket-Billing-System-Python
  2. Install Jupyter Notebook
     pip install notebook
3. Open the notebook
   jupyter notebook Supermarket_Billing_System.ipynb


🖥️ Example Output

**========== ITEMIZED BILL ==========
Item            Quantity        Price/Unit   Total
-------------------------------------------------------
Rice            5.0 kg          50.00        250.00
Milk            2.0 litre       30.00        60.00
Apple           1.5 kg          120.00       180.00
-------------------------------------------------------
Subtotal:                              490.00
Discount:                              24.50
Final Total:                           465.50
**

===================================
Thank you for shopping with us!
