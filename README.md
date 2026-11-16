# Rainfall Advisory Analysis

## Project Overview

This project analyses monthly rainfall data from five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos. The aim is to clean inaccurate rainfall data, identify rainfall patterns using Python and NumPy, and provide planting recommendations to support farmers.

## Project Files

- `rainfall_analysis.ipynb` – Contains data cleaning, rainfall analysis and planting recommendations.
- `rainfall_summary.csv` – Contains annual rainfall totals, wettest months, dry-month counts and recommended planting windows.
- `requirements.txt` – Lists the Python libraries required for the project.

## How to Run the Notebook

1. Download or clone this repository from GitHub.
2. Open Google Colab at https://colab.research.google.com/.
3. Upload `rainfall_analysis.ipynb` or open it directly from GitHub.
4. Ensure NumPy is installed by running `!pip install -r requirements.txt` if necessary.
5. Select Runtime → Run all to execute the notebook and view the results.

## Planting Advisory

- **Nairobi, Nakuru, Kisumu and Mombasa:** April and May are the recommended potential planting window because they have the highest combined rainfall.
- **Machakos:** November and December are the recommended potential planting window based on the highest combined rainfall.
- **Important consideration:** Farmers should monitor weather forecasts and consider soil conditions and crop water requirements before planting. The Machakos data also contains two imputed rainfall values, which should be verified against original weather station records.
