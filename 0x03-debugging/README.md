<h1>0x03. C - Debugging</h1>
<ul>
  <li>0. - In most projects, we often give you only one main file to test with. For example, this main file is a test for a postitive_or_negative() function similar to the one you worked with in an earlier C project:
  - Based on the main.c file above, create a file named 0-main.c. This file must test that the function positive_or_negative() gives the correct output when given a case of 0.

You are not coding the solution / function, you’re just testing it! However, you can adapt your function from 0x01. C - Variables, if, else, while - Task #0 to compile with this main file to test locally.

    You only need to upload 0-main.c and main.h for this task. We will provide our own positive_or_negative() function.
    You are not allowed to add or remove lines of code, you may change only one line in this task.
</li>
  <li>1. - Copy this main file. Comment out (don’t delete it!) the part of the code that is causing the output to go into an infinite loop.

    Don’t add or remove any lines of code, as we will be checking your line count. You are only allowed to comment out existing code.
    You do not have to compile with -Wall -Werror -Wextra -pedantic for this task.
</li>
  <li>2. - This program prints the largest of three integers.
  
  ? That’s definitely not right.

Fix the code in 2-largest_number.c so that it correctly prints out the largest of three numbers, no matter the case.

    Line count will not be checked for this task.
</li>
  <li>3. - This program converts a date to the day of year and determines how many days are left in the year, taking leap year into consideration.
  
  ? That doesn’t seem right.

Fix the print_remaining_days() function so that the output works correctly for all dates and all leap years.

    Line count will not be checked for this task.
    You can assume that all test cases have valid months (i.e. the value of month will never be less than 1 or greater than 12) and valid days (i.e. the value of day will never be less than 1 or greater than 31).
    You can assume that all test cases have valid month/day combinations (i.e. there will never be a June 31st or November 31st, etc.), but not all month/day/year combinations are valid (i.e. February 29, 1991 or February 29, 2427).
</li>
</ul>
