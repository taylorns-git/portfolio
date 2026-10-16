# Portfolio 🚀

A showcase of projects in Business Intelligence, data analytics, process analysis, and Python applications.

---

## 🩺 Featured Python Project: Patient Vitals Tracker (`vitals_tracker.py`)

A command-line Python application designed to collect, evaluate, and persist patient vital sign records.

### Key Features
* **Interactive Data Entry & Validation:** Accepts patient details using `try-except` loops to guarantee non-negative numerical inputs.
* **Age-Based Physiological Logic:** Categorizes heart rates as *Below average*, *Average*, or *Above average* based on clinical age categories (infants to adults).
* **Data Persistence:** Automatically saves and loads entries from `patient_vitals.csv` using Python's `csv` module (`csv.DictWriter` / `csv.DictReader`).

### How to Run
```bash
python vitals_tracker.py
