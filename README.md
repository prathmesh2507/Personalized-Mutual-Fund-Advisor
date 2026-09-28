# 💰 Personalized Mutual Fund Advisor

<div align="center">

## AI-Powered Mutual Fund Recommendation & Wealth Planning Platform

A guided investment planning platform that analyzes an investor's **goals, investment capacity, time horizon, and risk tolerance** to generate a personalized mutual fund strategy, portfolio allocation, fund recommendations, and long-term wealth projections.

[🚀 Live Demo](https://personalized-mutual-fund-advisor-mrbtzxaa2xfunen6tc9tme.streamlit.app/)


![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge\&logo=streamlit)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-blueviolet?style=for-the-badge\&logo=plotly)
![Pandas](https://img.shields.io/badge/Pandas-Analytics-black?style=for-the-badge\&logo=pandas)
![Finance](https://img.shields.io/badge/Finance-Mutual%20Funds-green?style=for-the-badge)

</div>

---

# 🎯 Project Overview

Choosing mutual funds manually can be difficult because investors need to consider **risk, investment goals, time horizon, SIP capacity, fund quality, returns, and costs** together.

This project builds an interactive **Mutual Fund Recommendation Engine** that transforms investor inputs and fund-level data into a structured investment plan.

The platform follows a guided journey:

**Investor Profile → Goal → Investment Capacity → Risk Assessment → Review → Personalized Plan**

The system then generates:

* Personalized risk profile
* Goal-based asset allocation
* Recommended mutual funds
* SIP allocation
* Portfolio quality analysis
* Wealth projections
* Target corpus tracking
* Fund exploration and filtering

The calculation logic is separated into the recommendation engine so that the interface focuses on presentation while the underlying financial calculations remain centralized.

---

# 🚀 Key Features

## 🧠 Personalized Risk Assessment

The application evaluates investor behavior through structured questions covering:

* Reaction to market losses
* Investment priorities
* Investment experience
* Income stability
* Comfort with market fluctuations
* Primary investment priority

These inputs are converted into a risk score and corresponding risk profile.

---

## 🎯 Goal-Based Investment Planning

Choose from multiple financial goals:

* 🏖️ Retirement
* 💰 Wealth Creation
* 🎓 Child Education
* 🏠 House Purchase
* 🛡️ Emergency / Short-Term
* 🎯 Other Goal

The selected goal and investment horizon are used to determine the strategic portfolio allocation.

---

## 💵 Investment Capacity Analysis

Users can specify:

* Monthly SIP
* Initial Lumpsum
* Target corpus
* Target age

The platform calculates the investment horizon and uses the available investment capacity when constructing the portfolio.

---

## 📊 Personalized Portfolio Allocation

The recommendation engine builds an allocation across:

* Equity
* Hybrid
* Debt

The allocation is first determined from the investment goal and horizon and then adjusted according to the investor's risk level.

---

## 🏆 Mutual Fund Recommendations

Recommended funds are evaluated using multiple factors instead of relying only on historical returns.

Key metrics include:

* Risk Score
* Risk Match
* Fund Quality
* 3-Year Returns
* Sharpe Ratio
* Sortino Ratio
* Expense Ratio
* Portfolio Score
* Asset Allocation

Funds are screened for risk compatibility and then ranked using risk-adjusted quality and cost-related metrics.

---

## 📈 Wealth Projection

Visualize potential portfolio growth through:

* Conservative scenario
* Expected scenario
* Optimistic scenario
* Amount invested
* Estimated gains
* Age-wise corpus growth

The dashboard also provides a target-corpus progress view when a financial target is specified.

> **Note:** Wealth projections are illustrative scenarios and are not guaranteed returns.

---

## 🔎 Fund Explorer

Explore the available mutual fund universe using filters such as:

* Asset Class
* Fund Category
* Maximum Monthly SIP

The explorer displays important fund metrics including risk, returns, Sharpe, Sortino, expense ratio, and fund quality score.

---

## 💡 Portfolio Intelligence

The system explains why funds were selected using factors such as:

* Risk compatibility
* Risk-adjusted quality
* Category-relative returns
* Cost awareness

This makes the recommendation process more transparent rather than presenting fund names without context.

---

# 🧠 Business Questions Answered

This platform helps answer:

* What is my investment risk profile?
* Which investment strategy fits my financial goal?
* How should I divide my SIP across asset classes?
* Which mutual funds match my risk profile?
* How much should I invest monthly?
* What could my portfolio potentially grow to?
* How close am I to my target corpus?
* Which funds meet my SIP budget?
* How do funds compare on risk-adjusted performance and cost?

---

# 📂 Project Structure

```text
Personalized-Mutual-Fund-Advisor/
│
├── data/
│   └── mutual_funds_dataset.csv
│
├── app.py
├── mf_engine.py
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── dashboard.png
    ├── risk-profile.png
    ├── recommendations.png
    └── wealth-projection.png
```

> Update the filenames inside the structure if your GitHub repository uses different names.

---

# 📊 Dataset Information

| Attribute       | Details                           |
| --------------- | --------------------------------- |
| Data Type       | Mutual Fund Data                  |
| Asset Classes   | Equity, Hybrid, Debt              |
| Format          | CSV                               |
| Key Metrics     | Risk, Returns, Sharpe, Sortino    |
| Fund Metrics    | Expense Ratio, Fund Quality       |
| Investor Inputs | Goal, SIP, Lumpsum, Horizon, Risk |
| Recommendation  | Risk & Goal Based                 |

The application loads the fund dataset through the recommendation engine and uses it to construct and rank portfolios.

---

# 🛠️ Tech Stack

| Technology           | Purpose                          |
| -------------------- | -------------------------------- |
| Python               | Core Development                 |
| Pandas               | Data Processing                  |
| NumPy                | Numerical Analysis               |
| Streamlit            | Web Application                  |
| Plotly               | Interactive Visualizations       |
| Custom Python Engine | Recommendation & Financial Logic |
| CSS                  | Custom UI/UX                     |
| CSV                  | Fund Dataset                     |

The dashboard uses Streamlit for the application layer and Plotly for interactive financial visualizations.

---

# 🎨 Dashboard Experience

The application uses a modern financial dashboard interface featuring:

* Premium dark theme
* Purple / blue / green glassmorphism
* Interactive KPI cards
* Multi-step investor journey
* Risk gauge
* Interactive portfolio charts
* Fund recommendation cards
* Responsive layouts
* Interactive Plotly visualizations

The UI is specifically designed around a consistent dark financial-dashboard visual language.

---

# 📸 Dashboard Preview

## 👤 Investor Journey

![Investor Journey](screenshots/dashboard.png)

---

## 🧠 Risk Assessment & Personalized Plan

![Risk Profile](screenshots/risk-profile.png)

---

## 🏆 Mutual Fund Recommendations

![Recommendations](screenshots/recommendations.png)

---

## 📈 Wealth Projection

![Wealth Projection](screenshots/wealth-projection.png)

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/prathmesh2507/Personalized-Mutual-Fund-Advisor.git
```

### Move into Project

```bash
cd Personalized-Mutual-Fund-Advisor
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python -m streamlit run app.py
```

The application will open locally in your browser.

---

# 🔥 Future Improvements

* Real-time mutual fund data integration
* Live NAV tracking
* AMFI/API integration
* Portfolio performance tracking
* Market/news sentiment analysis
* AI-powered financial explanations
* Goal-based SIP optimization
* Portfolio rebalancing alerts
* User portfolio history
* Authentication and personalized dashboards

---

# 👨‍💻 About Me

**Prathmesh Bhoyar**

Passionate about:

* Data Science
* Data Analytics
* Financial Intelligence
* Machine Learning
* Python Development
* Interactive Dashboard Design
* AI-Powered Applications
* Building User-Centric Analytics Products

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the project
💬 Share your feedback

---

## 💰 Built to turn investor goals and risk preferences into data-driven mutual fund insights.
