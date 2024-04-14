#  SBI Stock Volume Ranker
This project analyzes SBI stock data for the month of January 2024 and ranks the volume for each minute of the day. It compares the volume at the same time point across the last 5 working days and assigns a rank (1 being the highest volume).


## Problem Statement: 
1) We have SBI stock Open, high, low, close and volume data for every minute for every day.
2) The data is from 1st Jan 2024 till 31st Jan 2024 ( Each day having 375 rows of data i.e. 9:15 am till 3:29 pm).
3) We have to rank the volume in a such a way that it checks the exact same time for every day and for the last 5 days, it gives us the rank of volume ( rank 1 means highest volume).
4) So if we are analysing on 31st Jan 9:30 am volume, so we will compare the 9:30 am volume of 30th Jan, 29th Jan, 28th Jan, 27th Jan and 26th Jan ( working days) and then give a rank to it.
5) The output shall be stored in the current dataframe as a new column "rank".

## Features:

* Analyzes minute-by-minute volume data for SBI stock.
* Ranks volume for each minute considering the last 5 working days.
* Uses Pandas library for data manipulation.

## Requirements:

* Python 
* Pandas library

## Contributing: 

Contributions to this project are welcome! If you have ideas for improving the analysis, adding new features, or fixing issues, please open an issue or submit a pull request.

## License: 

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments:

The dataset used in this project is publicly available and can be found on various sources, including Kaggle.
Thank you for your interest in the project! We hope you find the insights and code provided valuable for your data analysis endeavors.
