# Black-Litterman-Model-and-the-Lediot-Wolf-Shrinkage-Estimation-Methodology


This project analyzes optimal portfolio allocation using two methodologies:

### 🔹 Assets Considered

* **ACWX** – MSCI ACWI ex-USA
* **AGG** – Bloomberg U.S. Aggregate Bond Index
* **BNDX** – Vanguard Total International Bond ETF
* **TLT** – iShares 20+ Year Treasury Bond ETF
* **GSPC** – S\&P 500 Index

**Frequency:** Daily
**Time Span:** Jan 1, 2017 – Oct 1, 2024
*Covers a full business cycle, two U.S. presidential terms, and the COVID crisis.*

---

### 📈 Market Capitalizations (in Trillion \$)

| Asset | Market Cap |
| ----- | ---------- |
| GSPC  | 43         |
| ACWX  | 86.23      |
| AGG   | 42.5       |
| TLT   | 8.625      |
| BNDX  | 128.3      |

---

### 📊 Ledoit-Wolf Shrinkage Estimation (Mean-Variance Optimization)

| Asset | Weight (%) |
| ----- | ---------- |
| ACWX  | 20.00      |
| AGG   | 17.31      |
| BNDX  | 40.00      |
| TLT   | 2.00       |
| GSPC  | 38.68      |

* **Annualized Expected Return:** 6.45%
* **Annualized Volatility:** 8.27%

---

### 🧠 Black-Litterman Model

* **Views based on Trump-era returns (2017–2021)**
* **Risk aversion parameter (delta):** 2.5
* **Uncertainty (omega):** Calibrated using Idzorek’s method

**Result:**
A well-balanced portfolio allocating **\~74.7% to equities** and the rest across bonds, with fewer constraints than classical MVO.

---

### ⚖️ Conclusion

> The **Black-Litterman Model** offered superior allocation flexibility, incorporating investor views and generating a more balanced portfolio compared to the constraint-heavy Ledoit-Wolf approach.

