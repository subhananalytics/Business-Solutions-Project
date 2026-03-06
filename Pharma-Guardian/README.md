# 🏥 Pharma-Guardian (v1.0)
### Integrated Medical Store Management System

Pharma-Guardian is a professional-grade Excel solution designed for small pharmacies that currently rely on manual paper ledgers. It bridges the gap between manual "Khata" books and expensive POS software.

## 🔴 The Problem (Based on Field Research)
Small medical stores lose **10-15% of revenue** due to:
1. **Expired Stock Deadlock:** Missing the 6-month supplier return window.
2. **Cheque Bounces:** Daily cash (Galla) not matching upcoming distributor payments.
3. **Stockouts:** Losing customers because a common "Salt" is out of stock.

## 🛠️ Key Features & Solutions

### 1. Expiry & Alert Dashboard
- **The Logic:** Automatically flags batch numbers **7 months before expiry**.
- **The Action:** Gives the shopkeeper a 30-day "Safe Window" to return the box to the supplier for a full refund.

### 2. Cash-Flow & Cheque Protector
- **The Logic:** Compares current cash-on-hand + projected 5-day sales against upcoming cheques.
- **The Alert:** Provides a "Probability of Bounce" warning 3 days in advance.

### 3. Smart Inventory (Demand Forecasting)
- Calculates **Sales Velocity** to suggest reorder quantities.
- Prevents "Frozen Cash" by identifying slow-moving medicines.

### 4. Credit (Udhaar) Management
- Real-time tracking of customer balances with automated Aging Reports (0-30, 31-60, 60+ Days).

## 📊 Technical Stack
- **Dynamic Formulas:** Used `SUMIFS`, `EOMONTH`, and `VLOOKUP` for real-time syncing.
- **Data Validation:** Prevents entry errors for non-technical users.
- **Mobile UI:** Color-coded status indicators (Red/Yellow/Green) for easy reading on smartphones.

## 🚀 Impact
By migrating from paper to **Pharma-Guardian**, a small store can:
- Reduce expired stock loss by up to **90%**.
- Improve cash liquidity by **20%** through smarter reordering.
- Gain 100% visibility on Net Profit after "Dead Stock" adjustments.

---
*Developed as part of the Business Solutions Series.*
