### Mini project - Sandwich Shop inventory management
## Built using Python (with gspread, google auth) and Google Drive/Sheets APIs

# A small python project to automate a simple stock management system for a fictional sandwich shop.
# The python code automtes the following:
- Checks for valid data entry and loops back if incorrect.
- Calculates surplus stock data.
- Calculates future stock with the following:
    - Gets last five days sales data
    - Averages that data, adds 10%, rounds to an int
- Inserts this data into a spreadsheet, in the relevant workbook.