# SAS-Import
A SAS code set that imports a specific dataset, in either tab-delimited or csv format.


This import file is designed to import any csv or tab-delimited text file into a sas dataset file (.sas7bdat)  

It will assume that all columns are text columns unless the names of the columns are added to any of the data type tables at the top of the code file.

For example, if you would like to make a column a numeric column, you would add the column name to the numeric table.

Obviously, the path to the file must be changed at the beginning of the code file first.

Several changes to come, including importing all files in a directory, and possibly suggesting types for data files.
