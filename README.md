# US Bikeshare Data Analysis

## Overview
This project explores bikeshare usage data from three major US cities: Chicago, New York City, and Washington. The analysis provides insights into usage patterns, popular stations, trip durations, and user demographics through an interactive Python program.

## Project Details
**Date Created:** December 8, 2024  
**Author:** haritetala  
**Course:** Udacity Programming for Data Science with Python Nanodegree

## Description
The bikeshare analysis program allows users to interactively explore bikeshare data by:
- Filtering data by city, month, and day of the week
- Computing descriptive statistics on usage patterns
- Identifying popular travel times, stations, and routes
- Analyzing trip durations and user demographics
- Displaying raw data upon request

## Files Used
- `bikeshare.py` - Main Python script for data analysis
- `chicago.csv` - Bikeshare data for Chicago (not included in repository)
- `new_york_city.csv` - Bikeshare data for New York City (not included in repository)
- `washington.csv` - Bikeshare data for Washington (not included in repository)

**Note:** CSV data files are excluded from version control via `.gitignore` to avoid tracking large files on GitHub.

## Requirements
- Python 3.x
- pandas library
- numpy library
- time module (standard library)

## How to Run
1. Ensure Python 3 and required libraries are installed
2. Place the CSV data files in the same directory as `bikeshare.py`
3. Run the program:
   ```bash
   python bikeshare.py
   ```
4. Follow the interactive prompts to explore the data

## Features
- **Interactive filtering** by city, month, and day
- **Statistical analysis** including most common travel times, stations, and trips
- **User demographics** analysis (where available)
- **Raw data display** option to view individual trip records
- **Restart capability** to perform multiple analyses

## Credits
- Udacity for providing the project template and course materials
- Motivate (bikeshare system provider) for the dataset
- Python pandas documentation: https://pandas.pydata.org/docs/
- Python datetime documentation: https://docs.python.org/3/library/datetime.html

## License
This project is part of the Udacity Programming for Data Science with Python Nanodegree program.
