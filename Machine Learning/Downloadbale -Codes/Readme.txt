There are different iPython notebooks which you have practiced coding on namely-

My first Python code
Importing Modules/Packages
Expressions
Lists
Stacks, Queues, Graphs, Trees
Dictionaries
Tuples and Sets

quantrautil.py contains the code to fetch the data from different web sources. You need to add your Quandl API key in the file so that fetching from Quandl works without any error. Also, you need to install below packages.

!pip install quandl
!pip install iexfinance
!pip install nsepy
!pip install fix_yahoo_finance

Apart from these you have notebooks covering intermediate concepts suchs as

Importing Data from web source
pandas.read_csv
2-D Plotting
3-D Plotting
Candlesticks
Functions
Lambda
Conditional Statements
Loops 

NumPy:

1.Introduction to arrays
2.Indexing and Slicing
3.Vectorization and Broadcasting in arrays

Pandas:

1.Series
2.Dataframe & Basic Functionality
3.Descriptive Statistical Functions
4.Indexing and Missing Values
5.Grouping and Reshaping

There are csv files which we have used in the IPythons:

1. infy
2. infy_data
3. infy_data_bb
4. infy_data_nan
5. infy_dv
6. infy_twoweeks
7. infy_twoweeks_nan
8. infy_data
9. tcs

Note: You have to add "csv/filename.csv" as first parameter to read the csv files. 

An example code is shown below.
infy = pd.read_csv ('csv/infy_dv.csv')

Alternatively, you need to specify the full path of the CSV file or store the CSV file in the same folder as the code file for it to run with any error. 
If you face any error then write back to quantra@quantinsti.com.
