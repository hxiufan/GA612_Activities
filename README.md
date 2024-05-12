Cleaning for olympics.csv
1. Replace the messy headers names

2. Indentified the null values; the result is 0.

3. Indetified the duplacated values; result is 0.

4. Standardised the data types.

5. Validate the data.

6. Saved a copy of the cleaned dataset. 


Cleaing for BL-Flickr-Images-Book.csv

1. Read the file, check the first few rows, indentify the basic information of the data structure

2. Used .isnull() to identify the missing data

3. There were four columns with a significant number of missing data:
Edition Statement         7514
Corporate Author          8287
Corporate Contributors    8287
Former owner              8286
Engraver                  8287

Thus, I considered them as not valuable for the analysis. 

4. Dropped the above five columns

5. Checked if there were duplicated values in "Indentifier" by using .is_uniuqe

6. Displayed a few rows to find out if there were non-consistent value types, and found there are some in "Date of Publication" and "Place of Publication"

7. Displayed some of the rows in details

8. Cleaned the column of 'Date of Publication', removed "[" and unified the strings format

9 Cleaned the column of "Place of Publication", replace the '-' with a space ' '

10. Printed the first few rows to verify, and found the year was in floating with one decimal.

11. Convert the year into integer type.

12. Replaced the NaN value in "Author" and "Publisher", using "Unknown" as a placeholder.

13. Imputed the missing value in 'Date of Publication' with mode, then verified the result. 

14. Saved a copy of the cleaned dataset.
