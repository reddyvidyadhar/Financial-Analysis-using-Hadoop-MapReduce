# NASDAQ Financial Analysis using Hadoop MapReduce

Used mapreduce  on a Hadoop environment at Center for Computational Research (CCR), Buffalo to compute stock volatility of companies listed on NASDAQ. Analysed the scalability of my implementation on different data sizes and number of nodes.

**Dataset**: CSV records of 2970 stocks spanning over 3 years (~30,000 files, 30 mn rows).Each file contains the data for one stock using its symbol as the file name. A stock list file is provided for cross reference.

**References**: http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf

Details about stock volatility at http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:standard_deviation_volatility. 