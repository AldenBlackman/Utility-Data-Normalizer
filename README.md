# Utility-Data-Normalizer
This is a personal project that automates the process of standardizing utility data csv and xlsx files.

The goal of this package is to use python and pandas to create a package that can read different types of utility data files I've seen, and automatically convert them to a standardized format, with stanard column names, intervals, and visualizations that may be used to derive valuable insights.  

The first step will be to build a standardize_file function that can take in csvs and excel files, apply column mapping, normalizes datetime and units, infers energy type and year, resamples to monthly, and then exports to exel.  

Then, 15-min interval data  concatenation, aggregation, and visualization.

column_mappings.yaml is the used to convert many common column names to standard ones. 

test_utility_data.csv and test_utility_data.xlsx are sample monthly data. synthetic_monthly_files.zip is the artificially created zip of monthly 15 minute interval data files.

