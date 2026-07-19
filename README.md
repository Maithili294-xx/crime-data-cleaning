# crime-data-cleaning
A Python script that automatically cleans messy police data by fixing typos, broken dates, and weird formatting.

Messy Crime Data Cleaner
A quick Python script using pandas to take messy, real-world police log data and scrub it into a clean, ready-to-use spreadsheet.

What it does:
Fixes Typos: Automatically standardizes messy categories (like fixing homocide to homicide).

Cleans Numbers & Dates: Stripped out symbols like $ and , from money columns and standardized mixed-up date formats.

Fills Blanks: Handles missing values using smart defaults (like the median for age).

Removes Outliers: Drops impossible data points like negative ages or suspects over 110.
