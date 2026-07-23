# Programming Fundamentals - Assignment 3 (Complete Documentation & Source Code)

**Student Name:** Ali Raza[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span)[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span)  
**Roll No:** SU92-BSSEM-F25-016[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span)  
**Section:** 2A - BSSE[span_8](start_span)[span_8](end_span)[span_9](start_span)[span_9](end_span)  
**Submitted To:** Professor Umer Khalil / Professor Umar Khalil[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span)  

---

## 📌 Repository Overview
This repository contains the complete, well-commented, and thoroughly debugged C++ source codes for **Programming Fundamentals Theory - Assignment 3**[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span)[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span). The entire assignment is structured into four distinct parts, covering core object-oriented and procedural programming paradigms including 1D/2D arrays, custom functions, pass-by-reference, function overloading, string manipulation algorithms, and mathematical problem-solving[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span)[span_19](start_span)[span_19](end_span).

---

## 📂 Detailed File Structure & Problem Breakdown

### 1. Part 1: Arrays, References & Basic Math (`assignment_3_part1.cpp`)[span_20](start_span)[span_20](end_span)
* **Problem 1 (Array Average - `calculateAverage`):** Iterates through an integer array to accumulate the total sum and computes the precise floating-point average score[span_21](start_span)[span_21](end_span).
* **Problem 2 (Min & Max Finder - `findMinMax`):** Utilizes C++ pass-by-reference (`&minVal`, `&maxVal`) to efficiently determine both the smallest and largest elements in a single traversal[span_22](start_span)[span_22](end_span).
* **Problem 3 (Custom Power Function - `calculatePower`):** Implements manual exponentiation logic to handle both positive and negative integer exponents without depending on external math libraries[span_23](start_span)[span_23](end_span).
* **Problem 4 (Voltage Calculator - `calculateVoltage`):** Computes electrical circuit voltage based on Ohm's Law formula ($V = I \times R$)[span_24](start_span)[span_24](end_span).
* **Problem 5 (Cricket Team Initials - `displayInitials`):** Processes a 2D character array of player names to extract and print their respective initial letters[span_25](start_span)[span_25](end_span).
* **Problem 6 (Word Length Calculator - `calculateWordLength`):** Manually evaluates a C-style string's length by counting characters up to the null-terminator (`\0`)[span_26](start_span)[span_26](end_span).

### 2. Part 2: Advanced Arrays, Sorting & Conversions (`assignment_3_part2.cpp`)[span_27](start_span)[span_27](end_span)
* **Problem 1 (Second Lowest & Highest Scores - `secondLowest` / `secondHighest`):** Analyzes student marks arrays to accurately filter out and retrieve the second lowest and second highest values[span_28](start_span)[span_28](end_span).
* **Problem 2 (Array Summation - `sumArray`):** Computes the cumulative sum of all numerical entries inside a student marks array[span_29](start_span)[span_29](end_span).
* **Problem 3 (Temperature Converter - `celsiusToFahrenheit`):** Converts temperature metrics from Celsius scale into Fahrenheit scale[span_30](start_span)[span_30](end_span).
* **Problem 4 (Leap Year Checker - `isLeapYear`):** Evaluates year inputs using standard Gregorian calendar conditions (divisible by 400, or divisible by 4 but not 100)[span_31](start_span)[span_31](end_span).
* **Problem 5 (Vowel Counter - `totalVowels`):** Scans a character word array to count the total occurrences of vowels in both uppercase and lowercase forms[span_32](start_span)[span_32](end_span).
* **Problem 6 (Letter Sorting - Bubble Sort):** Implements an in-place Bubble Sort algorithm to arrange an array of letters in alphabetical order[span_33](start_span)[span_33](end_span).

### 3. Part 3: Number Theory, Statistics & Strings (`assignment_3_part3.cpp`)[span_34](start_span)[span_34](end_span)
* **Problem 1 (Even & Odd Frequency Counters - `countEvenNumbers` / `countOddNumbers`):** Separates and counts the total frequency of even and odd integers within an array[span_35](start_span)[span_35](end_span).
* **Problem 2 (2D Array Display):** Takes row and column size inputs from the user to dynamically input and print matrix/table values[span_36](start_span)[span_36](end_span).
* **Problem 3 (GCD Finder - `findGCD`):** Implements the classic Euclidean algorithm using a `while` loop to find the Greatest Common Divisor of two integers[span_37](start_span)[span_37](end_span).
* **Problem 4 (Batting Strike Rate - `calculateStrikeRate`):** Computes a cricket player's batting strike rate using total runs scored and balls faced[span_38](start_span)[span_38](end_span).
* **Problem 5 (String Length Utility - `getLength`):** Determines string size by scanning elements until the null-character mark[span_39](start_span)[span_39](end_span).
* **Problem 6 (String Copy Utility - `copyWord`):** Safely copies characters from a source string buffer into a destination backup array index by index[span_40](start_span)[span_40](end_span).

### 4. Part 4: Matrices, Overloading & Reversal (`assignment_3_part4.cpp`)[span_41](start_span)[span_41](end_span)
* **Problem 1 (Matrix Total Sum):** Processes 2D table rows and columns to accumulate the total sum of all stored elements[span_42](start_span)[span_42](end_span).
* **Problem 2 (Profit/Loss Table Reduction):** Performs sequential multi-dimensional array calculations and index-based subtractions[span_43](start_span)[span_43](end_span).
* **Problem 3 (Area Calculator - Function Overloading):** Demonstrates **Function Overloading** by creating multiple functions sharing the name `calculateArea` for computing square areas vs. rectangle areas[span_44](start_span)[span_44](end_span).
* **Problem 4 (Bowling Average - `getBowlingAverage`):** Computes a bowler's average runs conceded per wicket while incorporating strict division-by-zero protection[span_45](start_span)[span_45](end_span).
* **Problem 5 (Vertical Word Printer - `printVertical`):** Iterates through a string to print individual characters vertically down separate console lines[span_46](start_span)[span_46](end_span).
* **Problem 6 (Word Reversal - `reverseWord`):** Reverses a C-style string in-place using a two-pointer swap strategy (moving start and end pointers inward)[span_47](start_span)[span_47](end_span).

---

## 🛠️ How to Compile and Run

Ensure you have a C++ compiler installed on your machine (such as GCC/MinGW via terminal or Code::Blocks). You can compile and execute any part using the following commands:

```bash
# To compile and run Part 1
g++ assignment_3_part1.cpp -o part1
./part1

# To compile and run Part 4
g++ assignment_3_part4.cpp -o part4
./part4
