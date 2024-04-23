# DCC-assignment-4
First, I converted the given pdf files into csv files using FITZ and a python code. While doing so, I had to make some modifications to the file, such as removing the headers with the column names which were present on every page. 
Once the pdfs were converted to csv files, I created a new database on MySQL Workbench, by creating a new schema. Then, I loaded the two tables by import table wizard. For each table, I first creted appropriate column names and mapped the original table column names to these column names to load the data properly.
