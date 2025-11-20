# GDP Change & Value Analyzer

This project analyzes annual U.S. GDP data using a text dataset and Python.  
It identifies:
- The year with the minimum percent change in Real GDP  
- The year with the maximum percent change in Real GDP  
- The corresponding GDP (in trillions of dollars) for those years

The program reads a GDP data file, extracts the relevant rows, finds the minimum and maximum values, and displays them in a formatted table.

---

## Features

- Robust file-input validation (reprompts until a valid file is provided)
- Extracts percent-change values and GDP values from fixed-width table rows
- Computes:
  - Minimum GDP growth year & value
  - Maximum GDP growth year & value
  - GDP (in trillions) for each of those years
- Clean console output in tabular format


## File Structure

