# Pandastic

This is one of my earlier code I wrote in Python as part of the subnmission for the Data Science-Artificial intelligence course I was taking in Singapore Polytechnic.

Part of assignment requirements was to produce Simple Text-based Analysis using Pandas

## Assignment rubrics
1.	Demonstrate competency in using the Python Numpy, Pandas and Matplotlib packages for data analysis and data visualization
2.	Demonstrate basic competency in working with relational and No-SQL databases for data analysis
3.	Demonstrate competency in applying the insights gained from the outputs of your Python programs to deliver a useful data analysis presentation for your stakeholders

## Example of the result expected
'''
Successfully loaded dataset data/nedian-resale-prices-for-registered-applications-by- 
town - and- fl at-type-utf8. csv 
This is the shape Of the dataset 
(6396, 4) 
This is the index of the dataset 
Rangelndex (start=ø, stop-6396, step-I) 
424ae7. e9e336 
1263% .254279 
136eeø. eøeeee 
33eøeø.eeeeee 
415eeø.eøeeee 
5m eeeeee 
8ssøeø.eøeeee 
These are the columns in the dataset 
Index (C , 
• price • J, 
The total number of non-NA values in this dataset is: 
quarter 
town 
fl at_type 
pri 
6396 
6396 
6396 
2856 
dtype: int64 
A sunnary of this dataset is shown below: 
<class 'pandas .core .frarp .DataFranp ' > 
Rangelndex: 6396 entries, e to 6395 
Data columns (total 4 columns) : 
quarter 
town 
fl at_type 
pri 
6396 non-null object 
6396 non-null object 
6396 non-null object 
2856 non-null float64 
dtypes: float64(1), object(3) 
"Emory usage: 
None 
A descriptive 
2øe.ø+ KB 
statistical sumary of this dataset is shown below: 
2856 .eøeeee 
count 
std 
75% 
max 

'''

Example 1 
Simple Text-based Analysis using Numpy


This output uses the Numpy library to load a HDB CSV dataset with the median resale prices by town and flat type and quickly breaks down the data with some simple useful-to-know information.

With this quick breakdown, we quickly realise the price column may have n/a values since the isnumeric is False for this column.

It also helps us to think about how we may want to extract subsets of this dataset and the choice of chart type for data visualization later.


Instead of simply just .....


I decided to name this program Pandastic because the pandas library was the main library. :-)
