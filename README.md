# 📊 Portfolio Optimization using Genetic Algorithm (GA)

## 🧠 Overview
This project implements a **Portfolio Optimization** model using a **Genetic Algorithm (GA)**.  
It identifies the optimal allocation of assets in a portfolio to **maximize return** and **minimize risk** under realistic investment constraints.

The notebook (`portfolio_optimization.ipynb`) automates stock data loading, log-return computation, GA-based optimization using DEAP, and visualization of results.

---

## 🚀 Features
✅ **Automatic CSV Data Loading** — Reads all stock price files from the `Stocks_Data/` folder.  
✅ **Realistic Log Returns** — Uses logarithmic returns for stability and accuracy.  
✅ **Long-only Constraint** — No short selling (weights ≥ 0).  
✅ **Max Allocation Limit** — Caps maximum allocation per stock at 40%.  
✅ **DEAP-based GA Optimization** — Modular, efficient, and customizable.  
✅ **Rich Visualizations:**  
- Portfolio Allocation (Pie Chart)  
- Efficient Frontier (Return vs Volatility)  
- GA Convergence Curve (Sharpe improvement over generations)  
✅ **Performance Comparison** — Compares Optimized vs Equal-Weight portfolio.  
✅ **Markdown Summary** — Auto-generated professional report at the end.

---

## 🧩 Project Structure
```
Portfolio_Optimization/
│
├── portfolio_optimization.ipynb   # Main Jupyter notebook
├── Stocks_Data/                   # Folder with stock CSV files
│   ├── hdfc.csv
│   ├── itc.csv
│   ├── l&t.csv
│   ├── m&m.csv
│   ├── sunpha.csv
│   └── tcs.csv
└── README.md                      # This documentation
```

---

## ⚙️ Requirements
Install required Python libraries (preferably in a virtual environment):
```bash
pip install numpy pandas matplotlib deap ipykernel
```

---

## 🧾 Workflow Summary
1. **Load stock price data** from CSV files.  
2. **Compute daily log returns** and **annualized mean & covariance matrix**.  
3. **Configure GA parameters** (population, generations, mutation, crossover).  
4. **Run Genetic Algorithm** to maximize the Sharpe Ratio.  
5. **Apply constraints:**  
   - No short selling  
   - Maximum 40% allocation per stock  
6. **Visualize results:**  
   - Pie chart (allocation)  
   - Efficient frontier (return vs volatility)  
   - GA convergence curve  
7. **Compare Optimized vs Equal-Weight portfolios.**  
8. **Generate Final Markdown Summary.**

---

## 📈 Key Outputs
- **Expected Annual Return (%)**  
- **Annual Volatility (%)**  
- **Sharpe Ratio**  
- **Top 3 Holdings**  
- **Comparison Table:** Optimized vs Equal-weight portfolio  

---

## 🧠 Insights
- The **optimized portfolio** provides better **risk-adjusted returns** than equal-weight allocation.  
- The **Genetic Algorithm** effectively enforces diversification constraints.  
- Using **log returns** prevents unrealistic compounding errors and improves accuracy.  

---

## 💡 Future Enhancements
- Add **risk preference (λ)** parameter for dynamic risk-return balancing.  
- Integrate **interactive sliders** using `ipywidgets`.  
- Extend to **multi-objective optimization** for Pareto-efficient portfolios.  

---

## 👩‍💻 Authors  

### **1. Ritu Pal**
📧 **Email:** [ritupal1626@gmail.com](mailto:ritupal1626@gmail.com)  
🌐 **GitHub:** [ritup04](https://github.com/ritup04)   


### **2. Priyanshi Solanki**
📧 **Email:** [priyanshissolanki7@gmail.com](mailto:priyanshissolanki7@gmail.com)  
🌐 **GitHub:** [Priyanshi-Solanki](https://github.com/Priyanshi-Solanki)  