# Calendar-using-C-programming-language
## C Language Calendar

This C language project provides a basic calendar functionality, allowing users to input a date (day, month, and year) and view the corresponding month's calendar with the specified date highlighted.

### Features

* **Leap Year Calculation:**  Accurately determines if a given year is a leap year, ensuring correct calendar display.
* **Day Calculation:**  Calculates the day of the week for any given date, enabling proper calendar formatting.
* **Calendar Display:**  Prints the calendar for the specified month and year, marking the input date with an asterisk (*).

### Functions

* `isLeapYear(int year)`:  Checks if a year is a leap year.
* `leapYears(int year)`:  Calculates the number of leap years up to a given year.
* `todayOf(int y, int m, int d)`:  Determines the day number (1-365 or 1-366) within a year for a specific date.
* `days(int y, int m, int d)`: Calculates the total number of days from the beginning of the calendar era to the specified date.
* `calendar(int date, int y, int m)`: Displays the calendar for the given month and year, highlighting the input date.

### Usage

1. **Compile:**  Compile the C code using a C compiler (e.g., GCC).
2. **Run:** Execute the compiled program.
3. **Input:**  Enter the desired date (day, month, and year) when prompted.
4. **Output:**  The program will display the calendar for the specified month, with the input date marked.

### Example

```
Enter Date: 15
Enter Month: 9
Enter Year: 2024

         Sep 2024
 S  M  T  W  T  F  S 
 1  2  3  4  5  6  7 
 8  9 10 11 12 13 14 
15* 16 17 18 19 20 21 
22 23 24 25 26 27 28 
29 30 
```

### Notes

* This code uses the deprecated `conio.h` header and `clrscr()` function, which may not be available on all systems. Consider replacing it with platform-independent alternatives for clearing the screen.
* Error handling for invalid input dates is not implemented. You may want to add input validation to improve robustness.
* The code assumes the Gregorian calendar.

### Contributing

Feel free to fork this repository and contribute improvements or additional features.

