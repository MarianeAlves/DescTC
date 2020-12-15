# The DescTC has become a package, a PyPI designed to make it more accessible for an end-user through pip install.

The DescTC package provides the distribution and valuable information of each variable of your data helping you 
to decide which data cleansing method you should use without having to type lots of commands one at a time.

The package includes methods that condense the inside story about each variable of your dataset into easy-to-understand 
formats (table and charts) that clearly and effectively communicate important points. Both work whether the variable is 
qualitative or quantitative.


Methods provided:

 *DescTC.table( )* 

    Offers you the following information of each quantitative/qualitative variable:

    - Type 
    - Quantity of zero numbers
    - Quantity of NaN's
    - % of NaN's 
    - Quantity of uniques values 
    - Quantity of outliers 
    - Min value / Lowest category 
    - Mean
    - Median
    - Mode
    - Max value / Highest category
    

 *DescTC.chart( )*

    Condense large amounts of information of each variable into easy-to-understand formats 
    that clearly and effectively communicate important points:

    - Plot the distribution of each variable 
    - Box plot of each quantitative variables
    - Plot the correlation between quantitative variables
    
Please be aware that your data must be converted to a pandas DataFrame with column names.

 *DescTC.printfullTable( )* 
    
    - Useful to see the entire outcome independently on which environment you are executing the package.
    
    
# Installation

    - pip install DescTC==0.1.1