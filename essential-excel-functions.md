




For many analysts, being able to use the powerful built-in functions in Excel is essential to maximize efficiency – particularly when working with large data ranges or undertaking complicated calculations.

all analysts will have a short list all analysts will have a short list of favorite Excel functions that are used on a daily basis to save time and effort. Here is our list of functions that every finance professional should know.

## Lookup Functions

Excel’s lookup functions are helpful as they search a row or column for a particular value or can locate a value in a specific position within the data.
The INDEX function returns a value or the reference to a value from within a table or range. Useful for retrieving individual data points.

     =INDEX(array,row_num,[column_num])

     =INDEX(reference,row_num,[column_num],[area_num])


In this example we are being asked to find the third product in the products list. The formula highlights the data range and then specifies 3 as the data point to retrieve, which in this case is lipstick.

<img width="703" height="308" alt="image" src="https://github.com/user-attachments/assets/9e31d18d-7e4d-4c41-848d-3560e7917b10" />

## MATCH functions

The MATCH function searches for a specified item in a range of cells and returns the relative position of that item within the range.

    =MATCH(lookup_value, lookup_array, [match_type])

This example asks us to find the position of Zaret in the list. Zaret is 12th in the list of names so the match function returns 12 as the answer.

<img width="768" height="341" alt="image" src="https://github.com/user-attachments/assets/72c8ac93-910b-459d-aecc-16bdbe38d29d" />

## VLOOKUP

The VLOOKUP function is a vertical search function within an array. It looks for a value in the leftmost column of a table, and then returns a value in the same row from a specified column.

    =VLOOKUP(lookup_value,lookup_array,return_array,[if_not_found],[match_model],[search model])

This example asks us to find out what product has Zaret sold. The formula highlights that it is searching for Zaret within the data range, and then requires an output from the 3rd column along in that particular row.  

<img width="702" height="313" alt="image" src="https://github.com/user-attachments/assets/9cb82e97-4d69-4cdf-9db5-f98dc8d36098" />  

An HLOOKUP works in the same way but is a horizontal rather than vertical search so will move along the rows rather than columns to find the output required. XLOOKUP is a newer Excel function and will work in any direction and return exact matches.  

## OFFSET

The OFFSET function returns a cell or an array a set distance away from a starting point.  

     =OFFSET(reference, rows, cols, [height], [width])  

This example asks us to find the cell 2 rows (down) and 3 columns (right) from B14.  

<img width="695" height="315" alt="image" src="https://github.com/user-attachments/assets/21d1af90-3316-4790-96a8-91cacf8ed4a1" />  










