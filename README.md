# Coding Challenges in Java

Includes problems and source code of solutions to many different general, intermediate and advanced level coding challenges given in exams (online/offline) or competitive programming round of interviews.


## Table of Contents

- [Prerequisite](#prerequisite)
- [Directory Structure](#directory-structure)
- [Index](#index)
- [List of Problems](#list-of-problems)
- [Creators](#creators)


## Prerequisite

All the problems are solved in Java. So, before you to go through and work with the given solution a prior knowledge to different chapters in Java like - Data types, Operators, Control statements, Looping statements, Methods, Arrays, Strings, Classes and Objects, Collection framework, Exceptions and a basic understanding of Data Structures is required.


## Directory Structure

```text
coding-challenges-java/
├── 1D Arrays/
├── 2D Arrays/
├── Algorithms/
│   ├── Searching Algorithms/
│   └── Sorting Algorithms/
├── Basic Programming/
├── Data Structures/
│   ├── Linked List/
│   ├── Queue/
│   └── Stack/
├── Patterns/
├── Recursion/
└── Strings/
```

## Index

1. [1D Arrays](#1d-arrays)
2. [2D Arrays](#2d-arrays)
3. [Algorithms](#algorithms)
   - [Searching Algorithms](#searching-algorithms)
   - [Sorting Algorithms](#sorting-algorithms)
4. [Basic Programs](#basic-programs)
5. [Data Structures](#data-structures)
   - [Linked List](#linked-lists)
   - [Queue](#queue)
   - [Stack](#stack)
6. [Patterns](#patterns)
7. [Recursion](#recursion)
8. [Strings](#strings)


## List of Problems

### 1D Arrays

```text
- 001_Write a program to initialize an array and display all its elements.

- 002_Write a program to find the maximum element of an array.
     Input: 20 40 30 50 10
    Output: 50

- 003_Write a program to find the second maximum element of an array.
  [Note: The length of the array must be >= 2]
     Input: 20 50 30 10 40
    Output: 40

- 004_Write a program to the display the duplicate elements of an array.
  [Note: The array is of type int (primitive)]
     Input-1: 20 50 30 30 10 40 20
    Output-1: 20 30

     Input-2: 99 55 33 11 66
    Output-2: There is no duplicate element in the array

- 005_Write a program to the display the duplicate elements of an array.
  [Note: The array is of type String (non-primitive)]
     Input-1: Jack Eric Robert Smith Jack Donald Eric
    Output-1: Eric Jack

     Input-2: Mike Peter Bob Daisy Diana
    Output-2: There is no duplicate element in the array

- 006_Write a program to completely remove all the duplicate elements in an array.
     Input: [1, 2, 1, 3, 4, 1]
    Output: [2, 3, 4]

- 007_Write a program to shift the position of a specified element at the end of an array.
     Input-1: [1, 2, 1, 4, 8, 5, 1, 9]
              1
    Output-1: [2, 4, 8, 5, 9, 1, 1, 1]

     Input-2: [1, 2, 1, 4, 8, 5, 1, 9]
              6
    Output-2: The element 6 is not present in the array

- 008_Write a program to sort Employee objects stored in an ArrayList on the basis of their salary.
```

### 2D Arrays

```text
- 001_Write a program to initialize a 2D array and display all its elements.

- 002_Write a program to verify couple of given 2D arrays are identical (i.e. same) or different.
     Input-1: 10 20 30 40
              10 20 30 40
    Output-1: Given 2D arrays are identical

     Input-2: 10 20 40 30
              10 20 30 40
    Output-2: Given 2D arrays are different

     Input-3: 10 20 40 30
              10 20
    Output-3: Given 2D arrays are different

- 003_Write a menu driven program using switch case construct to input a M X N matrix and display it. 
  Then perform the following operations based on user's choice:
    - Display the largest element of each row
    - Display the smallest element of each row
    - Display the largest element of each col
    - Display the smallest element of each col

- 004_Write a program and take the size of a square matrix as input. Input the elements. Display them
  in matrix form and also print its diagonals in the given manner.
    e.g.
      1     3
         5
      7     9
```

### Algorithms

#### Searching Algorithms

```text
- 001_Write a program to find an element and its position in the array using Linear Search algorithm.
     Input-1: 50 10 30 40 20
              30
    Output-1: Element is found at index = 2

     Input-2: 50 40 30 20 10
              70
    Output-2: Element is not found

- 002_Write a program to find an element and its position in the array using Binary Search algorithm.
  [Note: Binary Search algorithm works only with sorted arrays, so if the given array is not sorted
  remember to sort the elements of the array before searching for the desired element]
     Input-1: 11 22 33 44 55
              33
    Output-1: Element is found at index = 2

     Input-2: 77 55 33 22 11
              55
    Output-2: Element is found at index = 3

     Input-3: 77 55 33 22 11
              99
    Output-3: Element is not found
```

#### Sorting Algorithms

```text
- 001_Write a program to sort an unsorted array in ascending and descending order using Bubble Sort
  algorithm.
     Input: 33 22 11 55 44
    Output: 11 22 33 44 55
            55 44 33 22 11

- 002_Write a program to sort an unsorted array in ascending and descending order using Selection Sort
  algorithm.
     Input: 33 22 11 55 44
    Output: 11 22 33 44 55
            55 44 33 22 11

- 003_Write a program to sort an unsorted array in ascending and descending order using Selection Sort
  algorithm.
  [Note: In this case call the method to sort the array in ascending or descending order through method
  chaining.
   e.g - obj_ref.selectionSortAsc().displayArray();
         obj_ref.selectionSortDesc().displayArray();]
     Input: 33 22 11 55 44
    Output: 11 22 33 44 55
            55 44 33 22 11
```

### Basic Programs

```text
- 001_Write a program to validate whether a given number is even or odd.
     Input-1: 2
    Output-1: The number is even

     Input-2: 7
    Output-2: The number is odd

- 002_Write a program to print the maximum digit of a given number N.
  [Note: N > 0 and N is of type int]
     Input: 1234
    Output: 4

- 003_Write a program to split a given number N in between into two parts, reverse both parts then
  concatenate them to form a new number and print the new number as output.
  [Note: N > 0 and N is of type int]
     Input-1: 1234
    Output-1: 2143

     Input-2: 54321
    Output-2: 45123

- 004_Given a number N extract its first 3 digits and display it in console.
  [Note: N >= 100 and N is of type int]
     Input: 875160
    Output: 875

- 005_Write a program to reverse a number N and display it in console.
  [Note: N > 0 and N is of type int]
     Input: 4593
    Output: 3954

- 006_Write a program to print the numbers which is divisible by 3 and 5 in between 1 to N.
     Input: 50
    Output: 15 30 45

- 007_Write a menu driven program using switch case construct that converts a decimal number into 
  its equivalent Binary, Octal and Hexadecimal (Assume an integer input).
    Input: 
      Press 1 for Dec to Bin
      Press 2 for Dec to Oct
      Press 3 for Dec to Hexadecimal

      Enter your choice:
      1
      Enter the number:
      10
    Output:
      Binary Equivalent: 1010

- 008_Accept a sentence which is terminated by either ".", "?" or "!". Each word of sentence is 
  separated by a single space. Decode the words according to their potential and arrange them in 
  ascending order.
  
    The encryption of alphabets is to be done as follows:
      A = 1, B = 2, C = 3... Z = 26

    The potential of a word is found by adding the encrypted value of the alphabets.
      e.g.
        KITE = 11 + 9 + 20 + 5 = 45

     Input: THE SKY IS THE LIMIT.
    Output: IS THE THE SKY LIMIT
    [Potential: IS = 28, THE = 33, THE = 33, SKY = 55, LIMIT = 63]

- 009_Write program and check whether the given number is an evil number or not. 
  [Note: A number is considered to be an Evil number if the binary equivalent of the whole number is 
  having even number of 1's in it.]
    e.g. 
      3, 5, 6, 9, 15 etc. [5 = 0 1 0 1, 9 = 1 0 0 1]

- 010_Write program and check whether the given number is a unique number or not.
  [Note: A unique number is a positive integer (without leading zeros) with no duplicate digits.]
    e.g. 
      7, 135, 214 etc. are unique numbers
      99, 171, 3301 etc are not unique numbers

- 011_Write a program to display all the pronic numbers from 1 to n and also count how many pronic 
  numbers are there in between the given range.
  [Note: A pronic number / rectangular number / oblong number is a number which is represented by the 
  product of two consecutive numbers, that is a number of the form "n x (n + 1)"]
    e.g. 
      0 x 1 = 0
      1 x 2 = 2
      2 x 3 = 6
      3 x 4 = 12
```

### Patterns

```text
- 001_Write a program to generate the following pattern, where the number of rows N = 5.
     Input: 5
    Output: * * * * *
            * * * * *
            * * * * *
            * * * * *
            * * * * *

- 002_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 0 1 0 1
            1 0 1 0 1
            1 0 1 0 1
            1 0 1 0 1
            1 0 1 0 1

- 003_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 0 1 0 1 0
            0 1 0 1 0
            0 1 0 1 0
            0 1 0 1 0
            0 1 0 1 0

- 004_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 0 1 0 1
            0 1 0 1 0
            1 0 1 0 1
            0 1 0 1 0
            1 0 1 0 1

- 005_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 0 1 0 1 0
            1 0 1 0 1
            0 1 0 1 0
            1 0 1 0 1
            0 1 0 1 0
- 006_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 1 1 1 1
            0 0 0 0 0
            1 1 1 1 1
            0 0 0 0 0
            1 1 1 1 1

- 007_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 0 0 0 0 0
            1 1 1 1 1
            0 0 0 0 0
            1 1 1 1 1
            0 0 0 0 0

- 008_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: * * * * *
            *       *
            *       *
            *       *
            * * * * *

- 009_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:   * * *
            * * * * *
            * * * * *
            * * * * *
              * * *

- 010_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 2 3 4 5
            5 4 3 2 1
            1 2 3 4 5
            5 4 3 2 1
            1 2 3 4 5

- 011_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 2 3 4 5
            a b c d e
            1 2 3 4 5
            a b c d e
            1 2 3 4 5

- 012_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 a 2 b 3
            4 c 5 d 6
            7 e 8 f 9
            1 a 2 b 3
            4 c 5 d 6

- 013_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 a 2 b 3
            3 b 2 a 1
            4 c 5 d 6
            6 d 5 c 4
            7 e 8 f 9

- 014_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: *       *
              *   *
                *
              *   *
            *       *

- 015_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: * * * * *
              *   *
                *
              *   *
            * * * * *

- 016_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: *
            * *
            * * *
            * * * *
            * * * * *

- 017_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: * * * * *
              * * * *
                * * *
                  * *
                    *

- 018_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:         *
                  * *
                * * *
              * * * *
            * * * * *

- 019_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: * * * * *
            * * * *
            * * *
            * *
            *

- 020_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:     *
               * *
              * * *
             * * * *
            * * * * *

- 021_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:         *
                  * * *
                * * * * *
              * * * * * * *
            * * * * * * * * *

- 022_Write a program to generate the following pattern, where the given no of rows N = 4.
     Input: 4
    Output:        1
                 3 2
               6 5 4
            10 9 8 7

- 023_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:         1
                  1 2 1
                1 2 3 2 1
              1 2 3 4 3 2 1
            1 2 3 4 5 4 3 2 1

- 024_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1
            2 1
            3 2 1
            4 3 2 1
            5 4 3 2 1

- 025_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 1 2 3 4 5
             2 3 4 5
              3 4 5
               4 5
                5

- 026_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output: 5 4 3 2 1
             4 3 2 1
              3 2 1
               2 1
                1

- 027_Write a program to generate the following pattern, where the given no of rows N = 5
  (Pascal's Triangle).
     Input: 5
    Output:         1
                  1   1
                1   2   1
              1   3   3   1
            1   4   6   4   1

- 028_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:       1
                2 1 2
               3 2 1 2 3
             4 3 2 1 2 3 4
           5 4 3 2 1 2 3 4 5

- 029_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:     *
               * *
              * * *
             * * * *
            * * * * *
             * * * *
              * * *
               * *
                *

- 030_Write a program to generate the following pattern, where the given no of rows N = 5.
     Input: 5
    Output:     *
               * *
              *   *
             *     *
            *       *
             *     *
              *   *
               * *
                *
```

### Recursion

```text
- 001_Write a program to print a message N times without using any loop, using a recursive method.
     Input: Hello World
            3
    Output: Hello World
            Hello World
            Hello World

- 002_Write a program to find the factorial of a number using recursion.
     Input: 5
    Output: 120

- 003_Write a program to reverse a string using recursion.
     Input: hello
    Output: olleh

- 004_Write a program to print numbers from 1 to N without using any loop (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input: 5
    Output: 1
            2
            3
            4
            5

- 005_Write a program to print numbers from N to 1 without using any loop (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input: 5
    Output: 5
            4
            3
            2
            1

- 006_Write a program to find the Nth term of fibonacci series (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input-1: 5
    Output-1: 3

     Input-2: 10
    Output-2: 34

- 007_Write a program to generate fibonacci series upto the Nth term (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input-1: 5
    Output-1: 0 1 1 2 3

     Input-2: 10
    Output-2: 0 1 1 2 3 5 8 13 21 34

- 008_Write a program to check whether a number is prime or not (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input-1: 5
    Output-1: Prime

     Input-2: 27
    Output-2: Not prime

- 009_Write a program to find prime numbers in between 1 to N (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input: 20
    Output: 2 3 5 7 11 13 17 19

- 010_Write a program to find first N prime numbers (by using recursion)
  [Note: N >= 1 and N is of type int]
     Input: 10
    Output: 2 3 5 7 11 13 17 19 23 29
```

### Strings

```text
- 001_Write a program to check whether the given string is palindrome or not.
     Input-1: madam
    Output-1: CONGRATS! it is a palindrome

     Input-2: cat
    Output-2: SORRY! it is not a palindrome

- 002_Write a program to read a sentence and a character from the user and check whether the given
  character is present in the sentence or not. If the character is present then print its number of
  occurrence, else print "Given character is not present in the sentence".
     Input-1: I am a good boy
              o
    Output-1: 3

     Input-2: she is beautiful
              x
    Output-2: Given character is not present in the sentence

- 003_Write a program to count the number of vowels present in the given string.
     Input-1: hello
    Output-1: 2

     Input-2: try
    Output-2: Vowels not found

- 004_Write a program to count the number of digits present in the given string.
     Input-1: h3ll0
    Output-1: 2

     Input-2: @pple
    Output-2: No digit found

- 005_Write a program to check whether the given password is valid or not.
  [Note: A password is considered to be valid if it satisfies the following conditions (pattern):
   - The length of the password should be at least 8 characters
   - It should contain at least one uppercase alphabet
   - It should contain at least one digit
   - It should contain at least one special character
   - It should not contain whitespace as character]
     Input-1: Robert123@U$A
    Output-1: The password is valid

     Input-2: Ryan#7uk
    Output-2: The password is valid

     Input-3: Shane #105
    Output-3: The password is invalid

     Input-4: john*47cena
    Output-4: The password is invalid

- 006_Write a program to check two given strings are anagram or not (ignoring case).
  [Note: Two strings are said to be anagram if both the strings have same set of characters, same
  number of times]
     Input-1: LiStEn
              SiLEnT
    Output-1: WOW! Both the strings are anagram

     Input-2: Aim
              Iaam
    Output-2: SORRY! strings are not anagram

     Input-3: Medicare
              Medicine
    Output-3: SORRY! strings are not anagram

- 007_Write a program to remove all whitespace and tab(s) present in a sentence.
  [Note: It should remove any leading, trailing and in-between whitespace or tab(s) from the string]
     Input-1: It Is A Wonderful Day
    Output-1: ItIsAWonderfulDay

     Input-2:     Wish You A  Very Good   Morning
    Output-2: WishYouAVeryGoodMorning

- 008_Write a program to convert string into initcap case or title case.
  [Note: First letter of all the words present in the string should be capitalized]
     Input-1: I love my India
    Output-1: I Love My India

     Input-2: EAST OR WEST IndiA is tHe beSt
    Output-2: East Or West India Is The Best

- 009_Write a program to count the number of extra whitespace present in between a sentence.
  [Note:
   - There is no need to count extra whitespace present at the leading or trailing position of
     the sentence
   - If the whitespace count is 1 in between two words consider it as a normal whitespace
   - If the whitespace count is 2 or more then consider it in the category of extra whitespace]
     Input-1: Santa Claus   is  coming home
    Output-1: 3

     Input-2:    Let's make a snowman  this winter
    Output-2: 1

- 010_Write a program to count the number of words in the given sentence.
     Input-1: Mr. Smith   is  the  owner of the car
    Output-1: 8

     Input-2: Let's eat something
    Output-2: 3

- 011_Write a program to count the occurrence of each character in a string.
     Input: Keerthi
    Output: K = 1
            e = 2
            r = 1
            t = 1
            h = 1
            i = 1

- 012_Write a program to find the duplicate characters in a string.
     Input: Marriage
    Output: [a, r]

- 013_Write a program to remove the duplicate characters in a string maintaining the order
  of each character.
     Input: bamboo
    Output: bamo

- 014_Write a program to count the no of palindromes present in a string if we split the string into
substring having minimum of 2 characters.
     Input: abccba
    Output: 3
[Hint: "abccba" = palindrome, "bccb" = palindrome, "cc" = palindrome. Hence in total 3 palindromes 
are there in the given string.]

- 015_Write a program to transform a string in the following order:
     Input: I love Java and Selenium
    Output: Selenium dna Java evol I
```

### Miscellaneous

```text
- 001_Write a program to retrieve data based on given column header and row header of an MS Excel sheet.
```

## Creators

**Deepjyoti Barman**

- <https://github.com/defiant-dj04>
- <https://www.linkedin.com/in/deepjyoti-barman/>