# CS.11.05-extra-practice-1
Your personal practice exercise for CS year 11 unit 5 - arrays

# String and Array Manipulator Project

Create a Java program that performs various string and array manipulations. Your program should include the following methods:

## Part 1: String Operations
1. Create a method `findVowels` that:
   - Takes a String parameter
   - Returns the count of vowels (a, e, i, o, u) in the string
   - Should be case-insensitive

2. Create a method `reverseString` that:
   - Takes a String parameter
   - Returns the string in reverse order
   - Example: "hello" → "olleh"

## Part 2: Array Operations
3. Create a method `findMax` that:
   - Takes an integer array parameter
   - Returns the largest number in the array

4. Create a method `calculateAverage` that:
   - Takes an integer array parameter
   - Returns the average of all numbers in the array as a double

## Part 3: Combined Operations
5. Create a method `mergeArrays` that:
   - Takes two String array parameters
   - Returns a new array containing all elements from both arrays
   - Example: ["a","b"] and ["c","d"] → ["a","b","c","d"]

## Main Method Requirements
In your main method:
1. Create test cases to demonstrate each method
2. Print the results in a clear, organized way
3. Include at least one example for each method

## Sample Output Format
```
String Operations:
Vowel Count in "Hello World": 3
Reversed String "Programming": gnimmargorP

Array Operations:
Maximum in [5,2,9,1,7]: 9
Average of [10,20,30,40]: 25.0

Combined Operations:
Merged Arrays: [a, b, c, d]
```

---

### Extra Practice Quiz

#### Question 1: Merge Two Arrays
Given two arrays of integers, write a method called `merge` that merges the two arrays into one larger array. The method `merge` will return a new one-dimensional array of integers.
```java
int[] array1 = {10, 20, 30}; 
int[] array2 = {40, 50, 60}; 
merge(array1, array2) → {10, 20, 30, 40, 50, 60}
```

#### Question 2: Interleave Two Arrays
Given two arrays of integers of equal length, write a method called `interleave` that interleaves the elements from both arrays into one larger array. The method `interleave` will return a new one-dimensional array of integers.
```java
int[] array1 = {1, 2, 3}; 
int[] array2 = {4, 5, 6}; 
interleave(array1, array2) → {1, 4, 2, 5, 3, 6}
```

#### Question 3: Sum of Corresponding Elements
Given two arrays of integers of equal length, write a method called `sumArrays` that computes the sum of each element in the first array with the corresponding element in the second array. The method `sumArrays` will return a new one-dimensional array of integers.
```java
int[] array1 = {1, 2, 3}; 
int[] array2 = {4, 5, 6}; 
sumArrays(array1, array2) → {5, 7, 9}
```

#### Question 4: Count Vowels in Strings
Given an array of Strings, write a method called `vowelCount` that calculates the number of vowels in each String and stores them into a new array. The method `vowelCount` will return a new one-dimensional array of integers. Implement a helper method called `countVowels` that counts the number of vowels in a single word.
*Hint: You can check if a character is a vowel by comparing it against the characters 'a', 'e', 'i', 'o', and 'u' (both uppercase and lowercase).*
```java
String[] words = {"Hello", "World", "Java", "Programming"}; 
vowelCount(words) → {2, 1, 2, 3}
```

---

