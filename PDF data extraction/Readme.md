
## Extract Data from a PDF File

This assignment comprises the execution of pdf data processing and analysis tasks applied to documents in PDF format. This task focuses on converting the health in an PDF file ("health.pdf") into a csv file. Moreover, it mainly focuses on extracting the pdf data, rearranging the data in more redable format and converting it into csv file for further analysis.

The PDF file, "health.pdf", contains the children's health data over 202 countries in the world. The table spreads over four pages. The below code is parsing pdf pages 1-3, while the 4th page is parsed using Tabula. The required task are the following:

* Correctly parse and extract the table
* It is not required to extract the column labels. Except for the first column, which should be named as "Country Name", the other columns should be indexed with integers as shown in the figure;
* If the number followed by a character "x" in the pdf file, "x" must be dropped in your script
* Extracted table should be saved in a CSV file named as "health.csv".
