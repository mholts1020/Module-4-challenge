# Module-4-challenge

Asset Managers Risk and Return Analysis
This project analyzes one data sets whale_navs.csv which includes the net asset value of four different funds/asset managers (Soros Fund Management, Paulson & Co, Tiger Global Management, and Berkshire Hathaway) and the S&P 500 index ranging from October 2014 to September 11th, 2020. The project consists of obtaining and analyzing different risk/return parameters to evaluate which investment has the best performance, this includes creating plots and obtaining summary statistics (such as the mean) as well as useful information such as Standard Deviation, Variance, Covariance, Beta and Sharpe Ratio.

The dataset includes the following:

Timestamp (data set includes the following information for each day in our time range )
Net Asset Values (NAVS)
Technologies
The following technologies were used to build and deploy this application:

Python - Version 3.9.7
Anaconda (Which includes Jupyter Lab and Pandas)
Path (from pathlib)
matplotlib

4. Opening the file on Jupyter Notebook
Being in the folder created when you downloaded the repository type jupyter lab, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the risk_return_analysis.ipynb which contains all steps and notes followed to analyze this dataset pair.

Explanation of the Processes Followed
1. Data Import & Conversion
Before being able to properly analyze the data to draw conclusions we must first import the data, the following bullett gives a summary of what was done:

Importing both the dataset using the pandas read_csv function and setting parameters to set index column to "Timestamp", making it parse dates and infer date/time format
Calculating daily returns using the pct_change function in conjunction with the dropna
Aggregating daily return values to have cumulative data using the cumprod


Contributors
Maxwell Snyder

License
MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
