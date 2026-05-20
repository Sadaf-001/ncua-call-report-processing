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
```

## Workflow
1. Extract ZIP archive
2. Read TXT files into pandas DataFrames
3. Convert TXT files to CSV
4. Clean column names
5. Merge datasets
6. Export final merged file

## Author
Sadaf Khan
