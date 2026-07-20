




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

## CHOOSE

The CHOOSE function returns a value from a list and is part of a broader set of Microsoft Excel functions that allows analysts to run different scenarios in the model.  

     =CHOOSE(index_num, value1, [value2],…)  

In this example, revenue growth and EBITDA margin are the assumptions used to calculate the projections. The analyst has created three scenarios: worst, base and best case for both these assumptions. Using the CHOOSE function, it is possible to create a dynamic model which switches between these assumptions, by changing the scenario number in cell C6.  

By toggling the value in cell C6 from 1 an to 3, analyst will be able to present either the worst, base or best case scenario for both revenue growth and EBITDA margin. The assumptions used for each scenario are presented in the tables above.  

<img width="702" height="283" alt="image" src="https://github.com/user-attachments/assets/7f3d24ca-79b4-4f73-9ff4-a2c5a2adc042" />  

## ISBLANK

The ISBLANK function is used to check whether a cell is blank and returns TRUE if it is or FALSE if it is not.

     =ISBLANK(value)

Below is a list of cells that contains a different value. In this example, if the cell contains nothing at all, the ISBLANK function will return TRUE. If it contains any value, including any space, text, number, date, time, month, year, percentage, logical value, formula or even error value, ISBLANK will return FALSE.  

<img width="704" height="330" alt="image" src="https://github.com/user-attachments/assets/e7699be1-f20c-4fea-82e4-5f58c0272342" />  

## ISERROR

The ISERROR function is a logical function that is used to identify whether cells contain an error value or not. If there is any type of error in the cell it will return TRUE as result, and if not, it returns FALSE.

     =ISERROR(value)

In the below example we are asked to check for errors in the value column.

<img width="698" height="327" alt="image" src="https://github.com/user-attachments/assets/ac9f4ac1-a133-43f0-b852-5c2164b7925b" /> 


# FINANCIAL FORMULAS

Financial formulas can significantly reduce the amount of time and effort required to complete more complete calculations.  

## NPV

The NPV function calculates the net present value of an investment by using a discount rate and a series of future cash flows.

     =NPV(rate_value1,[value2],…)

In this example we are asked to calculate the NPV for each of the cash flows using the IRR as the discount rate. 

<img width="639" height="222" alt="image" src="https://github.com/user-attachments/assets/40c42eee-989a-4b0e-a27b-7ebb1550438a" />  

## XNP

The XNPV function calculates the net present value of a series of cash flows that don’t occur at regular intervals, using specified dates and a discount rate.

     =XNPV(rate, values, dates)

In this example we are asked to calculate the NPV using the XNPV function to take into account the non-periodic dates. 

<img width="698" height="225" alt="image" src="https://github.com/user-attachments/assets/cede63a3-0bf0-4b21-b511-01dba3d8b6ce" />  

## IRR

The IRR function calculates the internal rate of return for a series of periodic cash flows.

     =IRR(values,[guess])

In this example we are asked to calculate the annual return for the below cash streams. Note that a negative value denotes a cash outflow for the investor.  

<img width="637" height="130" alt="image" src="https://github.com/user-attachments/assets/e2c0f8bd-c36a-4bce-a5e0-7f66d62053a2" />  

## XIRR

The XIRR function calculates the internal rate of return with specified dates.

In this example we have already calculated the XNPV and we are being asked to calculate the IRR using the XIRR function to take into account the non-periodic dates. 

<img width="720" height="240" alt="image" src="https://github.com/user-attachments/assets/1133ba4f-af88-442f-9f2b-02fe79c2f690" />  


# Date and Time Functions

## TODAY

The TODAY function in Excel returns the current date. The format of the date can be amended later using the format cells, date function to customize it.

     =TODAY()

<img width="715" height="79" alt="image" src="https://github.com/user-attachments/assets/f1fedc56-69ce-455b-b6ad-e760e2e5f593" />  

## EOMONTH

The EOMONTH function returns the number for the last day of the month that is the indicated number of months before or after a specified date.

     =EOMONTH(start_date,months)

In this example we are asked what the date (end of the month) six months from the start date is. This is useful if we are looking to establish the potential completion date which will be six months later.  

<img width="719" height="104" alt="image" src="https://github.com/user-attachments/assets/a6104745-6ce9-4482-bc40-d51cae102782" />  

## YEARFRAC

The YEARFRAC function calculates as a fraction of the year, the number of whole days between two dates. This establishes the exact number of days between two transactions and can be helpful for calculations looking at accrued interest rate payments etc. The ‘basis’ element of the formula specifies which type of day count to use (such as 360 or 365 day convention).
=YEARFRAC(start_date,end_date,[basis])

The example asks us, as a fraction of the year, how many days are there from the start and end dates?  

<img width="718" height="145" alt="image" src="https://github.com/user-attachments/assets/0ce3d53d-f6db-474b-af54-f75aa03095ab" />  



































