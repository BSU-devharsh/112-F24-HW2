# There are two coding questions in this assignment.
# Please write your answers in the respective Java files.


## Question 1
## Java Homework Assignment: String Manipulation, Logical Operators, and Conditionals

**Objective:**

This assignment reinforces your understanding of String manipulation, logical operators, and conditional statements in Java. You will create a program that analyzes and processes text input based on specific criteria.

**Requirements:**

1. **Input:**
   - Prompt the user to enter a sentence or phrase.

2. **Analysis:**
   - Determine the length of the input string.
   - Count the number of vowels (a, e, i, o, u) in the string, ignoring case.
   - Check if the string starts with a capital letter.
   - Determine if the string contains the word "hello" (case-insensitive).
   - Find the last occurrence of the letter 'e' in the string (if present).

3. **Output:**
   - Display the following information:
     - The length of the input string.
     - The number of vowels in the string.
     - Whether the string starts with a capital letter (true/false).
     - Whether the string contains the word "hello" (true/false).
     - The index of the last occurrence of the letter 'e' (or -1 if not found).

**Grading Rubric:**

| Criteria | Points |
|---|---|
| Correctness of input and output | 15 |
| Proper use of String methods | 10 |
| Accurate use of logical operators | 10 |
| Clear and concise code structure | 10 |
| Appropriate comments and formatting | 5 |
| Total | 50 |

**Hints:**

- Use the `length()`, `charAt()`, `toUpperCase()`, `toLowerCase()`, `indexOf()`, and `lastIndexOf()` methods of the `String` class.
- Employ logical operators (`&&`, `||`, `!`) to combine conditions.
- Utilize conditional statements (`if`, `else if`, `else`) to make decisions based on different scenarios.

**Example Output:**

```
Enter a sentence: Hello, world!

Length of the string: 13
Number of vowels: 3
Starts with a capital letter: true
Contains "hello": true
Last occurrence of 'e': 10
```

**Submission:**

Submit your Java code file (e.g., `StringAnalysis.java`) along with any necessary documentation or comments.

**Additional Considerations:**

- Consider handling edge cases (e.g., empty input, invalid characters).
- Explore more advanced string manipulation techniques (e.g., substring, replace).
- Enhance the program to perform additional analyses or tasks based on your creativity.

Completing this assignment will solidify your understanding of essential Java concepts and develop problem-solving skills that are invaluable for programming.


## Question 2
## Java Homework Assignment: String Palindrome Checker

**Objective:**

This assignment will test your understanding of string manipulation, conditional statements, and loops in Java. You will create a program to determine whether a given input string is a palindrome.

**Requirements:**

1. **Input:**
   - Prompt the user to enter a string.

2. **Palindrome Check:**
   - Implement a function that takes a string as input and returns a boolean value indicating whether it's a palindrome.
   - A palindrome is a word, phrase, number, or other sequence of characters that reads the same backward as forward.
   - Ignore the case and punctuation for the palindrome check.

3. **Output:**
   - Display whether the input string is a palindrome or not.

**Grading Rubric:**

| Criteria | Points |
|---|---|
| Correctness of palindrome determination | 15 |
| Efficient algorithm implementation | 10 |
| Clear and concise code structure | 10 |
| Appropriate comments and formatting | 10 |
| Proper handling of edge cases (e.g., an empty string) | 5 |
| Total | 50 |

**Hints:**

- Use string manipulation methods to remove punctuation and convert the string to lowercase.
- Employ loops to compare characters from the beginning and end of the string.
- Consider using a recursive approach for an alternative solution.

**Example Output:**

```
Enter a string: Race car
The string is a palindrome.
```

**Submission:**

Submit your Java code file (e.g., `PalindromeChecker.java`) along with any necessary documentation or comments.

**Additional Considerations:**

- Explore different palindrome variations (e.g., word palindromes, numeric palindromes).
- Implement optimizations for larger input strings.
- Enhance the program to handle more complex palindrome patterns.

Completing this assignment will reinforce your understanding of string manipulation, conditional logic, and algorithm design in Java.
