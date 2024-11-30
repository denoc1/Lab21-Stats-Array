# Lab 21 - Array- Stats

## Objective
In this lab, you will practice working with integer arrays, writing methods to manipulate and analyze arrays, and documenting your code.

---
In the `main` method:
1. Declare an integer array and assign values.
2. Write the following methods in your program, and verify their functionality by making calls from the `main` method.

---

### Methods

#### 1. `public static void displayArray(int[] array)`
- **Description:** Accepts an integer array and displays its values in array format.
- **Precondition:** The parameter `array` must be a valid integer array.
- **Postcondition:** None (void method).
- **Notes:** Do not use `toString()`.

---

#### 2. `public static double average(int[] array)`
- **Description:** Accepts an integer array and returns the average of the array's values.
- **Precondition:** The parameter `array` must be a valid integer array with at least one element.
- **Postcondition:** Returns the average of the array values as a `double`.

---

#### 3. `public static int countAboveAve(int[] array)`
- **Description:** Accepts an integer array and returns the number of values above the average.
- **Precondition:** The parameter `array` must be a valid integer array with at least one element.
- **Postcondition:** Returns the count of values greater than the average.
- **Notes:** This method must call the `average` method.

---

#### 4. `public static int largest(int[] array)`
- **Description:** Accepts an integer array and returns the largest value.
- **Precondition:** The parameter `array` must be a valid integer array with at least one element.
- **Postcondition:** Returns the largest integer in the array.

---

#### 5. `public static int indexOfSmallest(int[] array)`
- **Description:** Accepts an integer array and returns the index of the smallest value. If multiple values are the smallest, the index of the first occurrence is returned.
- **Precondition:** The parameter `array` must be a valid integer array with at least one element.
- **Postcondition:** Returns the index of the smallest value.

---

### Sample Output
#### Example 1:
The array is [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 

The average of all the numbers in the array is 5.5 

The number of values above 5.5 is 5 

The largest value in the array is 10 

The index of the smallest value is 0


#### Example 2:
The array is [-11, 4, -2, 8, -22, 4, 8, 8, -9, 1, 0, 2] 

The average of all the numbers in the array is -0.75 

The number of values above -0.75 is 8 

The largest value in the array is 8 

The index of the smallest value is 4


#### Example 3:
The array is [-1, 0, 14, 2, -6, -6, -6, 12, 15] 

The average of all the numbers in the array is 2.6666666666666665 

The number of values above 2.6666666666666665 is 3 

The largest value in the array is 15 

The index of the smallest value is 4


#### Example 4:
The array is [1, 1, 1, 1] 

The average of all the numbers in the array is 1.0 

The number of values above 1.0 is 0 

The largest value in the array is 1 

The index of the smallest value is 0


---

