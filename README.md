# Marketing-Analytics-HW1

# Nintendo Switch 2 – Bass Diffusion Model Forecast

## Project Overview

This project analyzes the expected market diffusion of **Nintendo Switch 2** using the Bass Diffusion Model.  
The PlayStation Portable (PSP) is used as a "look-alike" product to estimate model parameters (p, q, M).

The analysis includes:

- Estimation of Bass model parameters using PSP sales data
- Forecast of Nintendo Switch 2 adoption
- Annual and cumulative adoption predictions
- Visualization of diffusion curves

---

## Project Structure


project_folder/
│
├── data/
│ └── Data.xlsx
│
├── report/
│ ├── report.Rmd
│ └── report.pdf
│
├── helper_functions.R
├── README.md


### Folder Descriptions

- **data/**  
  Contains datasets used for analysis.

- **report/**  
  Contains the R Markdown source file and final PDF report.

- **helper_functions.R**  
  Contains reusable Bass model functions:
  - `bass_f()` – adoption rate
  - `bass_F()` – cumulative adoption

---

## Setup Instructions

1. Open the project folder in RStudio.
2. Install required packages (if not already installed):

```r
install.packages(c("ggplot2", "ggpubr", "diffusion", "readxl"))

Open:

report/report.Rmd

Knit the document to generate the PDF report.


Key Results

Peak adoption occurs approximately 4–5 years after launch.

Diffusion follows a classic S-shaped curve.

Market potential was set at 160 million units based on prior Nintendo ecosystem performance.

References

Statista. (2025). Game consoles market revenue worldwide. Statista Market Insights. https://www.statista.com/outlook/cmo/consumer-electronics/gaming-equipment/game-consoles/worldwide

Statista. (2025, July 10). Sony PlayStation Portable and PlayStation Vita unit sales worldwide from 2004 to 2022.  https://www.statista.com/statistics/1029044/worldwide-sony-playstation-vita-unit-sales

Towey, H. (2026, February 3). Nintendo Switch becomes the company’s best-selling console ever. CNBC. https://www.cnbc.com/2026/02/03/nintendo-switch-best-selling-console-gaming.html


