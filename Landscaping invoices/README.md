# Landscape Monthly Invoices Analysis

A comprehensive data analysis project examining company invoice history, correction trends, and monthly distribution totals. 

## 📊 Visual Overview
Below is the summary visualization of invoice trends generated from our dataset:

![Landscape Monthly Invoices Chart](https://unsplash.com)

---

## 📈 Key Metrics Summary
Based on our verified transaction logs, the platform managed **$90,973.42 in Grand Total revenue** over a total of **12 Unique Customers**.


| Metric | Value |
| :--- | :--- |
| **Grand Total Revenue** | $90,973.42 |
| **Unique Customer Count** | 12 |
| **Average Monthly Total** | $7,581.12 |

---

## 📅 Breakdown by Month Order
The underlying transaction patterns are segmented by month order numbers below:

### Month 2 (February Lifecycle)
* **Monthly Total Generated:** $4,234.38
* **Unique Customer Volume:** 3
* **Key Contributors:** 
  * Charles Edminson (`$276.56` Corrected)
  * Grey Takeda (`$2,054.85` Corrected)
  * Cedric Salzwedel (`$902.97` Corrected)

### Month 3 (March Lifecycle)
* **Monthly Total Generated:** $9,639.96
* **Unique Customer Volume:** 5
* **Key Contributors:** 
  * Boris Wyrick (`$2,747.84` Corrected)
  * Yoko Wayne (`$1,919.08` Corrected)
  * Emalee Tucker (`$2,634.02` Corrected)
  * Todd Unkle (`$1,477.74` Corrected)
  * Deacon Kokkinos (`$861.28` Corrected)

### Month 4 (April Lifecycle)
* **Monthly Total Generated:** $7,517.62
* **Unique Customer Volume:** 4
* **Key Contributors:** 
  * Jaymes Gao (`$1,250.30` Corrected)
  * Monday Reier (`$1,223.80` Corrected)
  * Cicely Allegri (`$2,944.99` Corrected)
  * Shirley Smith (`$1,948.53` Base Invoice Amount)

---

## 🛠️ Data Pipeline & Commands

### Prerequisites
Ensure you have Python 3.8+ installed along with `pandas` for processing the dataframes.

```bash
pip install pandas matplotlib notebook
```

### Execution
Run the cleaning script to generate the corrected sums and plot the matching bar charts:

```bash
python generate_metrics.py --input invoice_data.csv
```

---

## 🤝 Contributing
1. Fork the Project Repository.
2. Create your Feature Branch (`git checkout -b feature/AmazingMetrics`).
3. Commit your Changes (`git commit -m 'Add new metric views'`).
4. Push to the Branch (`git push origin feature/AmazingMetrics`).
5. Open a Pull Request.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
