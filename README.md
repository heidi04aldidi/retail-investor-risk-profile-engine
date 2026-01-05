# Investor Risk Profiling using Machine Learning
> **Unsupervised Machine Learning Project | K-Means Clustering | Python | Data Analysis**

## Project Summary
Developed a **machine learning–based investor segmentation system** that classifies investors into **Conservative, Moderate, and Aggressive risk profiles** using **K-Means clustering**.  
The project simulates realistic portfolio data, engineers financial risk metrics, and visualizes investor behavior to support data-driven investment decisions.

---
## Tech Stack
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---
## Features & Workflow

### Data Simulation
- Generated portfolio data for **50 investors**
- Each investor holds **5 stocks** with varying returns & volatility

### Feature Engineering
Calculated key investment metrics:
- **Portfolio Return**
- **Portfolio Volatility**
- **Maximum Drawdown**
- **Beta (Market Sensitivity)**
- **Diversification Index**

### Machine Learning
- Applied **StandardScaler** for normalization
- Implemented **K-Means clustering (k = 3)**
- Clustered investors based on risk characteristics

### Risk Classification
Mapped clusters to meaningful risk labels:
-  Conservative – Low volatility
-  Moderate – Medium volatility
-  Aggressive – High volatility

### Visualization
- Scatter plot of **Portfolio Volatility vs Portfolio Return**
- Color-coded by investor risk profile

---
## Output
Final classified dataset: investor_risk_profiles.csv


Each investor is tagged with a clear **risk profile**

---
## Future Improvements
-  Integrate real-time market data APIs
-  Apply Elbow Method to optimize cluster selectio
-  Add risk-adjusted metrics like Sharpe Ratio
-  Deploy as a Streamlit dashboard

