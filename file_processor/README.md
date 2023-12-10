<span style="font-size: 20px;"><b> File processor. </span></b>

[ipyb](eng_file_processor.ipynb)

## Project description.
Based on open-source data from the annual report of the Chief Oncologist of the Ministry of Health of Russia

**Goal:** To transform 138 xlsx files with tables that are poorly suitable for analysis into 4 datasets ready for further work. The tables contain information on the incidence and mortality of oncological diseases and the state of oncology care in the regions of the Russian Federation.

**The project involves:**
- Downloading files from Yandex.Disk,
- Transforming tables:
  - Creating new columns based on data extracted from table headers,
  - Formatting columns for readability,
  - Performing minor table normalization,
  - Cleaning rows with aggregated data,
  - Collecting tables into 4 datasets based on their contents,
- Uploading tables to Google Sheets.

## Skillset.
yadisk   
gspread  
os  
pandas  
openpyxl  
re

## Result.
Data is reorganized and prepared for further analysis. 

Example of source data:  
[2021_Таблица_051_Состояние_онко_помощи_в_РФ.xlsx](2021_Таблица_051_Состояние_онко_помощи_в_РФ.xlsx)  
[2021_Таблица_101_Злокачественные_новообразования_в_РФ_(заболеваемость_и_смертность).xlsx](2021_Таблица_101_Злокачественные_новообразования_в_РФ_(заболеваемость_и_смертность).xlsx)

Processed data:  
[Oncology care status (treatment)](https://docs.google.com/spreadsheets/d/11ch2hH_jGhFBuNQslV2F_2b8GN374RS-c6bS2X7CnVs)  
[Oncology care status (population)](https://docs.google.com/spreadsheets/d/1P33EZT-CQqu1atFeqAsPWCy-Bp3rvw87iPRnJckTQcM)  
[Oncology care status (population) table 2](https://docs.google.com/spreadsheets/d/1KKfeebttMfPreGBm1Zzm0ag5fBHLdcM9fgZLos2HQUc)  
[Malignant neoplasms: incidence and mortality](https://docs.google.com/spreadsheets/d/1uj9oTNnAV_8FntB5Lsrw7Rskbdjc9uXepH0pVQzSR7M)
