# Day 14 – Lookup & Reference Functions (Part 2)

## Task

Used INDEX() and MATCH() functions to fill missing Department values by fetching the correct data from a related table.

## Functions Used

- INDEX()
- MATCH()

## Work Completed

- Created a related table containing Employee ID and Department.
- Created missing Department values in the main dataset.
- Used MATCH() to find the corresponding Employee ID in the related table.
- Used INDEX() to return the correct Department value.
- Combined INDEX() and MATCH() to fill the missing Department values.
- Successfully retrieved Department values for EMP1000 to EMP1005.

## Formula Used

```excel
=INDEX('Day-14 Related Table'!$B$2:$B$7,MATCH(A2,'Day-14 Related Table'!$A$2:$A$7,0))
