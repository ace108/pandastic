# Pandastic

This is one of my earlier code I wrote in Python as part of the subnmission for the Data Science-Artificial intelligence course I was taking in Singapore Polytechnic.

Part of assignment requirements was to produce Simple Text-based Analysis using Pandas using whatever dataset.

## Example of the result expected
```
Successfully loaded dataset data/median-resale-prices-for-registered-applications-by-town-and-flat-type-utf8.csv 

This is the shape of the dataset 
(6396, 4) 

This is the index of the dataset 
Rangelndex (start=0, stop=6396, step=1) 

These are the columns in the dataset 
Index(['quarter', 'town', 'flat-type', 'prize'], dtype='object')

The total number non-NA values in this dataset is:
quarter      6396
town         6396 
flat_type    6396 
price        2856
dtype: int64

A summary of this dataset is shown below:
<class 'pandas.core.frame.DataFrame' > 
Rangelndex: 6396 entries, 0 to 6395 
Data columns (total 4 columns) : 
quarter      6396 non-null object
town         6396 non-null object
flat_type    6396 non-null object
price        2856 non-null object
dtype: float64(1), object(3)
Memory usage: 200.0+ KB
None


A descriptive statiscal summary of this dataset is shown below:
               price
count    2856.000000
mean   424407.090336
std   126306.254279
min   136000.000000
25%   330000.000000
50%   415000.000000
75%   501500.000000 
max   855000.000000
```

Instead of just dealing with just one specific dataset, I made this such that datasets in CSV/Excel format in a specific folders are read and processed to produce the analysis information for the data read in from a file. I decided to name this program Pandastic because the pandas library was the main library. :-)
