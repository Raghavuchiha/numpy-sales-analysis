# 📊 Sales Analysis with NumPy

> A hands-on data analysis project exploring 8 months of sales data using Python and NumPy — covering totals, trends, profit margins, and performance labeling.

---

## 🗂️ Project Overview

This project performs a complete sales analysis on monthly data using **NumPy**, covering everything from basic aggregations to growth trends and profit classification.

| Month | Sales ($) | Expenses ($) | Profit ($) |
|-------|-----------|--------------|------------|
| Jan   | 1,200     | 800          | 400        |
| Feb   | 1,500     | 900          | 600        |
| Mar   | 1,100     | 850          | 250        |
| Apr   | 1,800     | 1,000        | 800        |
| May   | 2,100     | 1,200        | 900        |
| Jun   | 1,700     | 950          | 750        |
| Jul   | 2,500     | 1,400        | 1,100      |
| Aug   | 2,300     | 1,300        | 1,000      |

---

## ✨ Features

- ✅ Total & average sales calculation
- ✅ Highest and lowest sales detection
- ✅ Monthly profit computation
- ✅ Total profit summary
- ✅ Best profit month identification
- ✅ Top-performing months filter (sales > $2,000)
- ✅ Below-average months detection
- ✅ Month-over-month growth tracking
- ✅ Highest growth month identification
- ✅ Monthly profit percentage calculation
- ✅ Performance labeling (Average / Good / Excellent)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python and pip installed, then install NumPy:

```bash
pip install numpy
```

Or install from the requirements file:

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook sales.ipynb
```

Or launch via JupyterLab:

```bash
jupyter lab sales.ipynb
```

---

## 📁 Project Structure

```
sales-analysis/
│
├── sales.ipynb          # Main analysis notebook
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 📈 Key Results

| Metric                  | Value         |
|-------------------------|---------------|
| 💰 Total Sales          | $14,200       |
| 📉 Average Monthly Sale | $1,775        |
| 🏆 Highest Sale Month   | July — $2,500 |
| 📦 Lowest Sale Month    | March — $1,100|
| 💵 Total Profit         | $5,800        |
| 🔝 Best Profit Month    | July — $1,100 |
| 📈 Highest Growth Month | July — +$800  |

### 🏷️ Performance Labels

| Label      | Criteria         | Months                  |
|------------|------------------|-------------------------|
| Excellent  | Sales > $2,500   | *(none this period)*    |
| Good       | Sales ≥ $1,800   | Apr, May, Jul, Aug      |
| Average    | Sales < $1,800   | Jan, Feb, Mar, Jun      |

---

## 🧠 Concepts Covered

```python
np.sum()       # Total aggregation
np.average()   # Mean calculation
np.max()       # Peak value
np.min()       # Minimum value
np.argmax()    # Index of maximum value
np.where()     # Conditional labeling
Boolean indexing  # Filtering months by condition
Array slicing     # Month-over-month growth
```

---

## 📦 Requirements

```
numpy
vs code
```

> Save the above in a `requirements.txt` file.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-analysis`
3. Commit your changes: `git commit -m 'Add new analysis'`
4. Push to the branch: `git push origin feature/new-analysis`
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ and NumPy</p>
