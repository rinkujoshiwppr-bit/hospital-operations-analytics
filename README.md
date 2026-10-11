# Hospital Operations & Patient Care Analytics

A Python data-analytics portfolio project exploring patient records, hospital visits, waiting time, satisfaction, department demand, and billing data.

## Tools
- Python
- Pandas and NumPy
- Matplotlib
- Jupyter Notebook

## Project files
- `hospital_operations_patient_care_analytics.ipynb` — analysis notebook
- `patients.csv`, `visits.csv`, `billing.csv` — source datasets
- `Hospital_Analytics_LinkedIn_Dashboard.png` — dashboard image for portfolio preview
- `DATA_QUALITY_NOTES.md` — known data issues to investigate
- `requirements.txt` — Python dependencies

## Run locally
1. Install Python 3.10+ and Jupyter.
2. Open a terminal in this folder.
3. Install packages: `pip install -r requirements.txt`
4. Start Jupyter: `jupyter notebook`
5. Open `hospital_operations_patient_care_analytics.ipynb`.
6. Choose **Kernel → Restart & Run All**.

Keep all three CSV files in the same folder as the notebook. The notebook uses relative paths instead of personal Windows file paths and no longer requires file-picker popups.

## Important limitations
This is a learning/portfolio project, not a clinical tool. The supplied datasets contain inconsistencies; see `DATA_QUALITY_NOTES.md`. The notebook has been made more portable and syntax-checked, but the full sequence of notebook cells has not been verified end-to-end in this preparation. Please run all cells from a fresh kernel and fix any runtime errors before claiming it is fully tested.

## Privacy
Before making this repository public, verify that the CSVs contain no real patient information and that you have permission to share them.
