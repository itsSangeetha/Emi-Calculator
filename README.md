# 💰 EMI Calculator (HTML, CSS, JavaScript)

A responsive and interactive EMI (Equated Monthly Installment) Calculator built using **vanilla HTML, CSS, and JavaScript**.

This tool calculates:

- 📌 EMI (Equated Monthly Installment)
- 💵 Total Payment
- 📊 Total Interest Payable
- 📅 Complete Amortization Schedule
- 📥 Export Schedule as CSV

---

## 🧮 EMI Formula Used

EMI is calculated using the standard formula:

EMI = P × R × (1 + R)^N / ((1 + R)^N - 1)

Where:

- **P** = Principal Loan Amount  
- **R** = Periodic Interest Rate (Annual Rate / Payments Per Year / 100)  
- **N** = Total Number of Payments  

If interest rate = 0:

EMI = P / N

---

## ✨ Features

- Responsive modern UI
- Supports:
  - Monthly payments (12)
  - Quarterly payments (4)
  - Yearly payments (1)
- Full amortization schedule
- Automatic rounding protection
- Final payment precision adjustment
- CSV download option
- No external libraries used

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom properties & responsive grid)
- Vanilla JavaScript (No frameworks)

---

## 📂 Project Structure
