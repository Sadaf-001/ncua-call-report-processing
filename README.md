# NCUA Call Report Data Processing

## Overview
This project processes raw NCUA quarterly call report TXT files into structured CSV datasets and merges them into a unified analysis-ready dataset using Python and Pandas.

## Objectives
- Extract ZIP files
- Convert TXT files into CSV format
- Clean and standardize column headers
- Merge datasets using common identifiers
- Export a final merged dataset

## Technologies Used
- Python
- Pandas
- Google Colab
- GitHub

## Dataset
NCUA quarterly call report data.

## Merge Keys
The datasets were merged using:
- `CU_NUMBER`
- `CYCLE_DATE`
- `JOIN_NUMBER`

## Output
Final merged dataset dimensions:

```python
(4505, 2687)
