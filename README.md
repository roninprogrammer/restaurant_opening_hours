# Opening Hours Restaurant

## Requirement 
This (http://setel.axzae.com/homework/) endpoint has a list of restaurants and their hours of openings. Create a list view (or a recycler view) in an Android application that loads this data remotely and displays the restaurant name and its current operation state (Open or Closed). Upon tapping on the restaurant, shows the full list of its operating hours.
Please write this application in Kotlin for Android / Swift for iOS / Dart for Flutter depending on the platform that you are tested on and use a Git repository. You could use any external libraries if needed.

## Example

Input:
------
time: 11:30pm
data: "Ali, Muthu & Ah Hock","Mon-Thu, Sun 11:30 am - 9:00 pm  / Fri-Sat 11:30 am - 9:30 pm"

Output
-------------
Ali, Muthu & Ah Hock
Closed

Output: (Details Screen)
Ali, Muthu & Ah Hock
Mon 11:30 am - 9:00 pm
Tue 11:30 am - 9:00 pm
Wed 11:30 am - 9:00 pm
Thu 11:30 am - 9:00 pm
Fri 11:30 am - 9:30 pm
Sat 11:30 am - 9:30 pm
Sun 11:30 am - 9:00 pm



Rules: 
*If a day of the week is not listed, the restaurant is closed on that day.
*There are only one continuous opening per day, as in no restaurant will open - in the morning and open at night again.
*No restaurant will remain open after 11:59PM.
*All times are local — don’t worry about timezone-awareness.
*There’s an intended two-second delay on the endpoint to simulate slow network response.


