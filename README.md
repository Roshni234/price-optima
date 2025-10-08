# 🚗 PriceOptima — AI-Powered Dynamic Pricing System

RideOptima is an intelligent **dynamic pricing platform** built for ride-hailing services.  
It leverages **machine learning** to recommend optimal ride prices in real time — balancing profitability, fairness, and customer satisfaction.

## 🧩 Problem Statement

Ride-hailing platforms often struggle to set **optimal prices** dynamically due to fluctuating demand, driver availability, and competition.  
Without adaptive pricing:

- **Underpricing** → Loss of potential revenue  
- **Overpricing** → Increased cancellations  
- **Delayed response** → Reduced competitiveness  

## 💡 Proposed Solution

RideOptima automatically adjusts fares using ML insights to achieve **fair, data-driven pricing**.

### Key Features
1. **Test Single Record (Personalized Recommendation)**  
   - Users can input ride details manually.  
   - The system predicts the completion probability and recommends the optimal price instantly.

2. **Upload Batch CSV (Bulk Prediction & KPI Dashboard)**  
   - Upload a CSV file with multiple ride records.  
   - The backend performs batch predictions and computes key performance indicators (KPIs) such as:
     - Revenue (baseline vs scenario)
     - Gross Margin
     - Cancellation Rate
     - Price Change Rate  
   - Interactive charts built with **Recharts** visualize the pricing outcomes.

## ⚙️ Tech Stack

| Layer | Technology | Description |
|-------|-------------|-------------|
| **Frontend** | React.js | Interactive dashboard for testing single/batch predictions and visualizing results. |
| **Backend** | FastAPI | Handles API requests, integrates ML model, and manages batch processing. |
| **Model Development** | Python (Scikit-learn) | Gradient Boosting model used for completion probability and price optimization. |
| **Visualization** | Recharts | Line and bar charts for visual insights. |
| **Utilities** | Pandas, NumPy, Joblib | Data preprocessing, feature handling, and model serialization. |


## 🧰 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Roshni234/price-optima.git
cd price-optima
