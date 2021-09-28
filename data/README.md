# Raw data

## raw-data.xls

Contains raw data on weekly new unemployment claims by state. Data was downloaded from https://oui.doleta.gov/unemploy/claims.asp on Sep 28, 2021, by selecting State, 
Beginning Year = 2016, Ending Year 2022, Spreadsheet, and highlighting all states.

The resulting file is stored in this folder as raw-data.xls. Opening the file produces a warning 
about a mismatch between file format and file extension. As a result, RStudio
had some trouble reading the file in. To surmount this, I created a cleaned version
of the data and stored it in .csv format. The differences are:

- Empty rows at the top of the data were removed
- Variable names were changed to make them easier to read into R
- A notation regarding the date downloaded was removed from the bottom of the table.