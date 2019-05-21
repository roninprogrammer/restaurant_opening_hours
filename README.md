# Opening 

## Requirement 
The attached CSV data file has a list of restaurants and their hours of openings.  Create a list view (or a recycler view) in an mobile application that loads this data locally from the app package and displays the restaurant name and the hours of its opening.   You could use external libraries if needed such as CSV parser.

## Example

Input:
------
"Osakaya Restaurant","Mon-Thu, Sun 11:30 am - 9:00 pm  / Fri-Sat 11:30 am - 9:30 pm"
 
Output
-------------

Osakaya Restaurant
Mon 11:30 am - 9:00 pm
Tue 11:30 am - 9:00 pm
Wed 11:30 am - 9:00 pm
Thu 11:30 am - 9:00 pm
Fri 11:30 am - 9:30 pm
Sat 11:30 am - 9:30 pm
Sun 11:30 am - 9:00 pm
 
Rules: 
* If a day of the week is not listed, the restaurant is closed on that day
* There are only one continuous opening per day, as in no restaurant will open in the morning and open at night again
* No restaurant will remain open after 11:59PM
* All times are local — don’t worry about timezone-awareness
* The CSV file will be well-formed

