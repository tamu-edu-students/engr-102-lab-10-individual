# ENGR 102 Lab Topic 10 (individual)

## Activities
There are two deliverables for this individual assignment. Please submit the following files to Gradescope and Canvas. Check out the [Frequently Asked Questions](#frequently-asked-questions) below. **Please include the individual header in your ~.py file.**

1. [Roman Numerals](#roman-numerals)

## Roman Numerals
Roman numerals were a way of writing numbers in ancient Rome. Letters are used to represent fixed integer values and can be combined to represent other numbers. They are commonly found on clock faces and old buildings. For more information about Roman numerals, [see the Wikipedia article](https://en.wikipedia.org/wiki/Roman_numerals).

The file [`roman_numerals.py`](roman_numerals.py) contains code that takes as input from the user two Roman numerals, converts them into a numeric value, then compares them to determine which one is larger. At least, that’s what the program is *supposed* to do. Instead, the file you are given has several bugs! Find and fix all of them. Keep the same filename for submission to Gradescope. When debugging, remember DRIFT: discover, reproduce, isolate, fix, and test. It's a good idea to come up with several test cases to test your code **before** you start making changes.

Example (correct) output (using inputs `MCCXXXIX` and `MCMXVIII`):
```
Enter the first Roman numeral: MCCXXXIX
Enter the second Roman numeral: MCMXVIII
MCCXXXIX is smaller than MCMXVIII
```

After you have successfully debugged the file, create a file named `roman_numerals_bugs.pdf` that documents each of the bugs that you found. For each bug, include the following information:
- A brief explanation of the cause of the error and how you fixed it. This explanation should be written in English, in your own words, and in complete sentences. You should write between 50 to 100 words per bug.
- The original (incorrect) line(s) of code containing the bug
- The fixed (correct) line(s) of code
- The type of error (syntax, runtime, logic)
- One test case that reproduces the bug. The test case should include the inputs, the expected (correct) output, and the actual (incorrect) output or error message. This **MUST** be different from the test cases found on Gradescope.

Submit `roman_numerals.py` to Gradescope for autograding, and `roman_numerals_bugs.pdf` to Canvas for manual grading.

## Frequently Asked Questions
1. **How many bugs are there?** I don't know... I forgot to count when I added them. :(

2. **Are there syntax/runtime/logic bugs?** Yes, yes, and yes! Good luck finding all of them!

3. **Do I need to use the debugger?** Nope, you can use any debugging method you like.

Have a question you don't see here? Email your instructor!

Revised Fall 2026 SNR
