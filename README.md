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

## Usage Example
When you run the program, you'll be prompted to make selections:

```
Hello! Let's explore some US bikeshare data!
Which city would you like to explore? (Chicago, New York City, Washington): chicago
Which month? (all, January, February, March, April, May, June): march
Which day of the week? (all, Monday, Tuesday, ... Sunday): friday
```

The program will then display statistics about:
- Most common travel times (month, day, hour)
- Most popular stations and trip routes
- Total and average trip duration
- User demographics (type, gender, birth year)

## Features
- **Interactive filtering** by city, month, and day
- **Statistical analysis** including most common travel times, stations, and trips
- **User demographics** analysis (where available)
- **Raw data display** option to view individual trip records
- **Restart capability** to perform multiple analyses

## Statistics Computed
The program analyzes the bikeshare data to provide the following insights:

### Time Statistics
- Most common month for bike rentals
- Most common day of the week for bike rentals
- Most common hour of the day for bike rentals

### Station Statistics
- Most commonly used start station
- Most commonly used end station
- Most frequent trip route (start-end station combination)

### Trip Duration Statistics
- Total cumulative travel time
- Average travel time per trip

### User Statistics
- Count of each user type (Subscriber, Customer)
- Count of each gender (where available)
- Birth year statistics: earliest, most recent, and most common (where available)

## Credits
- Udacity for providing the project template and course materials
- Motivate (bikeshare system provider) for the dataset
- Python pandas documentation: https://pandas.pydata.org/docs/
- Python datetime documentation: https://docs.python.org/3/library/datetime.html

## License
This project is part of the Udacity Programming for Data Science with Python Nanodegree program.
