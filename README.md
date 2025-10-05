# Forest Fire Prediction using Machine Learning

## Project Overview
This project predicts the **Fire Weather Index (FWI)** — a numerical indicator of fire danger — using the **Algerian Forest Fire Dataset**.  
Users can input various weather and environmental parameters through a web interface, and the trained ML model outputs the **FWI value**.

---

## Features
- Uses **Ridge Regression** model (with ~98.4% accuracy)
- Includes **StandardScaler** for feature scaling
- End-to-end deployment-ready with **Flask** integration
- User-friendly web interface for predictions

---

## Tech Stack
- **Python**
- **scikit-learn**
- **Flask**
- **NumPy, Pandas, Matplotlib**
- **Pickle (for model serialization)**

---

## Input Parameters
| Parameter | Description |
|------------|--------------|
| **Temperature** | Ambient temperature (°C) |
| **RH** | Relative Humidity (%) |
| **Ws** | Wind Speed (km/h) |
| **Rain** | Rainfall (mm/m²) |
| **FFMC** | Fine Fuel Moisture Code |
| **DMC** | Duff Moisture Code |
| **ISI** | Initial Spread Index |
| **Classes** | Fire occurrence (1 = Fire, 0 = No Fire) |
| **Region** | 1 = Bejaia, 0 = Sidi Bel-abbes |

---

## Output
**FWI (Fire Weather Index)** — a continuous numeric value indicating fire intensity.  
Higher FWI → greater fire danger 🔥




