# Custom Functions for Power Apps

![it ain't much but its honest work](assets/work.jpg)

This component library contains 3 components with the following custom properties:

1. dateFunctions
   1. countWeekdays - counts weekdays in between of two given dates
   2. endOfMonth - returns the last day of a given month - Thanks to Matthew Devaney for that one!
   3. getQuarter - returns the quarter of a given date
   4. firstOfMonth - returns the first day of a given month
   5. getHalfyear - returns the halfyear of a given date
2. regexFunctions
   1. isTime - validates time
   2. isEmail - validates email
   3. isURL - validates URL
   4. isDecimal - validates decimal
   5. isText   - validates text
3. conversionFunctions
   1. milesToK - converts miles to kilometers
   2. kToMiles - converts kilometers to miles
   3. celsiusToFahrenheit - converts celsius to fahrenheit
   4. fahrenHeitToCelsius - converts fahrenheit to celsius

You can either use the unpacked source code (Use Power Platform CLI to pack the files again) or use the packed .msapp file.

If you want to learn ore on how to build custom functions in Power Apps, please read my blog post here: [Intro du custom functions in Power Apps](https://m365princess.com/intro-custom-functions-power-apps)
