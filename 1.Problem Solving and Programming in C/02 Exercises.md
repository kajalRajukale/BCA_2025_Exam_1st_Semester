# Problem Solving and Programming in C

## Content

- [Problem Solving and Programming in C](#problem-solving-and-programming-in-c)
    - [Exercises](#exercises)
        - [Exercise 1: Print "Hello, World!"](#exercise-1-print-hello-world)
        - [Exercise 2: Add Two Numbers](#exercise-2-add-two-numbers)
        - [Exercise 3: Find the Largest Number](#exercise-3-find-the-largest-number)
        - [Exercise 4: Check Even or Odd](#exercise-4-check-even-or-odd)
        - [Exercise 5: Calculate Factorial](#exercise-5-calculate-factorial)
        - [Exercise 6: Generate Fibonacci Series](#exercise-6-generate-fibonacci-series)
        - [Exercise 7: Reverse a Number](#exercise-7-reverse-a-number)
        - [Exercise 8: Check Palindrome](#exercise-8-check-palindrome)
        - [Exercise 9: Calculate GCD](#exercise-9-calculate-gcd)
        - [Exercise 10: Calculate LCM](#exercise-10-calculate-lcm)
        - [Exercise 11: Find Prime Numbers](#exercise-11-find-prime-numbers)
        - [Exercise 12: Sum of Digits](#exercise-12-sum-of-digits)
        - [Exercise 13: Count Digits](#exercise-13-count-digits)
        - [Exercise 14: Swap Two Numbers](#exercise-14-swap-two-numbers)
        - [Exercise 15: Find Armstrong Numbers](#exercise-15-find-armstrong-numbers)
        - [Exercise 16: Calculate Power](#exercise-16-calculate-power)
        - [Exercise 17: Find Sum of Array Elements](#exercise-17-find-sum-of-array-elements)
        - [Exercise 18: Find Largest Element in Array](#exercise-18-find-largest-element-in-array)
        - [Exercise 19: Reverse an Array](#exercise-19-reverse-an-array)
        - [Exercise 20: Find Second Largest Element in Array](#exercise-20-find-second-largest-element-in-array)
        - [Exercise 21: Find the Sum of Even Numbers](#exercise-21-find-the-sum-of-even-numbers)
        - [Exercise 22: Find the Sum of Odd Numbers](#exercise-22-find-the-sum-of-odd-numbers)
        - [Exercise 23: Find the Average of Array Elements](#exercise-23-find-the-average-of-array-elements)
        - [Exercise 24: Find the Median of Array Elements](#exercise-24-find-the-median-of-array-elements)
        - [Exercise 25: Find the Mode of Array Elements](#exercise-25-find-the-mode-of-array-elements)
        - [Exercise 26: Find the Standard Deviation of Array Elements](#exercise-26-find-the-standard-deviation-of-array-elements)
        - [Exercise 27: Find the Sum of Natural Numbers](#exercise-27-find-the-sum-of-natural-numbers)
        - [Exercise 28: Find the Sum of Squares of Natural Numbers](#exercise-28-find-the-sum-of-squares-of-natural-numbers)
        - [Exercise 29: Find the Sum of Cubes of Natural Numbers](#exercise-29-find-the-sum-of-cubes-of-natural-numbers)
        - [Exercise 30: Find the Sum of Prime Numbers](#exercise-30-find-the-sum-of-prime-numbers)
        - [Exercise 31: Find the Sum of Fibonacci Series](#exercise-31-find-the-sum-of-fibonacci-series)
        - [Exercise 32: Find the Sum of Even Fibonacci Numbers](#exercise-32-find-the-sum-of-even-fibonacci-numbers)
        - [Exercise 33: Find the Sum of Odd Fibonacci Numbers](#exercise-33-find-the-sum-of-odd-fibonacci-numbers)
        - [Exercise 34: Find the Sum of Digits of a Number](#exercise-34-find-the-sum-of-digits-of-a-number)
        - [Exercise 35: Find the Product of Digits of a Number](#exercise-35-find-the-product-of-digits-of-a-number)
        - [Exercise 36: Find the Reverse of a String](#exercise-36-find-the-reverse-of-a-string)


## Exercises

### Exercise 1: Print "Hello, World!"

#### Description: Write a program that prints "Hello, World!" to the console.

#### Solution

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

### Exercise 2: Add Two Numbers

#### Description: Write a program that takes two integers as input and prints their sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int a, b, sum;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    sum = a + b;
    printf("Sum: %d\n", sum);
    return 0;
}
```

### Exercise 3: Find the Largest Number

#### Description: Write a program that takes three integers as input and prints the largest number.

#### Hint: Use conditional statements to compare the three integers.

#### Solution

```c
#include <stdio.h>

int main() {
    int a, b, c;
    printf("Enter three integers: ");
    scanf("%d %d %d", &a, &b, &c);
    if (a >= b && a >= c)
        printf("Largest: %d\n", a);
    else if (b >= a && b >= c)
        printf("Largest: %d\n", b);
    else
        printf("Largest: %d\n", c);
    return 0;
}
```

### Exercise 4: Check Even or Odd

#### Description: Write a program that takes an integer as input and checks if it is even or odd.

#### Hint: Use the modulus operator to determine if the number is even or odd.

#### Solution

```c
#include <stdio.h>

int main() {
    int num;
    printf("Enter an integer: ");
    scanf("%d", &num);
    if (num % 2 == 0)
        printf("%d is even.\n", num);
    else
        printf("%d is odd.\n", num);
    return 0;
}
```

### Exercise 5: Calculate Factorial

#### Description: Write a program that takes an integer as input and calculates its factorial.

#### Hint: Use a loop to multiply the numbers from 1 to the given integer.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, i;
    unsigned long long factorial = 1;
    printf("Enter an integer: ");
    scanf("%d", &num);
    if (num < 0)
        printf("Factorial of a negative number doesn't exist.\n");
    else {
        for (i = 1; i <= num; ++i) {
            factorial *= i;
        }
        printf("Factorial of %d = %llu\n", num, factorial);
    }
    return 0;
}
```

### Exercise 6: Generate Fibonacci Series

#### Description: Write a program that generates the Fibonacci series up to a given number of terms.

#### Hint: Use a loop to generate the series by adding the previous two terms.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, t1 = 0, t2 = 1, nextTerm;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");
    for (int i = 1; i <= n; ++i) {
        printf("%d, ", t1);
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }
    return 0;
}
```

### Exercise 7: Reverse a Number

#### Questio from Kajal

How to reverse a string

#### Description: Write a program that takes an integer as input and prints its reverse.

#### Hint: Use a loop to extract digits from the number and build the reversed number.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, reversed = 0, remainder;
    printf("Enter an integer: ");
    scanf("%d", &num);
    while (num != 0) {
        remainder = num % 10;
        reversed = reversed * 10 + remainder;
        num /= 10;
    }
    printf("Reversed number: %d\n", reversed);
    return 0;
}
```

### Exercise 8: Check Palindrome

#### Description: Write a program that checks if a given integer is a palindrome.

#### Hint: Reverse the number and compare it with the original number.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, reversed = 0, remainder, original;
    printf("Enter an integer: ");
    scanf("%d", &num);
    original = num;
    while (num != 0) {
        remainder = num % 10;
        reversed = reversed * 10 + remainder;
        num /= 10;
    }
    if (original == reversed)
        printf("%d is a palindrome.\n", original);
    else
        printf("%d is not a palindrome.\n", original);
    return 0;
}
```

### Exercise 9: Calculate GCD

#### Description: Write a program that calculates the Greatest Common Divisor (GCD) of two integers.

#### Hint: Use a loop to find the highest number that divides both integers without a remainder.

#### Solution

```c
#include <stdio.h>

int main() {
    int a, b, gcd;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    for (int i = 1; i <= a && i <= b; ++i) {
        if (a % i == 0 && b % i == 0)
            gcd = i;
    }
    printf("GCD of %d and %d is %d\n", a, b, gcd);
    return 0;
}
```

### Exercise 10: Calculate LCM

#### Description: Write a program that calculates the Least Common Multiple (LCM) of two integers.

#### Hint: Use a loop to find the smallest number that is divisible by both integers.

#### Solution

```c
#include <stdio.h>

int main() {
    int a, b, lcm;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    lcm = (a > b) ? a : b;
    while (1) {
        if (lcm % a == 0 && lcm % b == 0) {
            printf("LCM of %d and %d is %d\n", a, b, lcm);
            break;
        }
        ++lcm;
    }
    return 0;
}
```

### Exercise 11: Find Prime Numbers

#### Description: Write a program that prints all prime numbers between two given numbers.

#### Hint: Use nested loops to check if each number in the range is prime.

#### Solution

```c
#include <stdio.h>

int main() {
    int low, high, i, flag;
    printf("Enter two numbers (intervals): ");
    scanf("%d %d", &low, &high);
    printf("Prime numbers between %d and %d are: ", low, high);
    while (low < high) {
        flag = 0;
        for (i = 2; i <= low / 2; ++i) {
            if (low % i == 0) {
                flag = 1;
                break;
            }
        }
        if (flag == 0)
            printf("%d ", low);
        ++low;
    }
    return 0;
}
```

### Exercise 12: Sum of Digits

#### Description: Write a program that calculates the sum of the digits of a given integer.

#### Hint: Use a loop to extract digits from the number and add them.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, sum = 0, remainder;
    printf("Enter an integer: ");
    scanf("%d", &num);
    while (num != 0) {
        remainder = num % 10;
        sum += remainder;
        num /= 10;
    }
    printf("Sum of digits: %d\n", sum);
    return 0;
}
```

### Exercise 13: Count Digits

#### Description: Write a program that counts the number of digits in a given integer.

#### Hint: Use a loop to divide the number by 10 until it becomes 0.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, count = 0;
    printf("Enter an integer: ");
    scanf("%d", &num);
    while (num != 0) {
        num /= 10;
        ++count;
    }
    printf("Number of digits: %d\n", count);
    return 0;
}
```

### Exercise 14: Swap Two Numbers

#### Description: Write a program that swaps the values of two integers without using a temporary variable.

#### Hint: Use arithmetic operations to swap the values.

#### Solution

```c
#include <stdio.h>

int main() {
    int a, b;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    a = a + b;
    b = a - b;
    a = a - b;
    printf("After swapping: a = %d, b = %d\n", a, b);
    return 0;
}
```

### Exercise 15: Find Armstrong Numbers

#### Description: Write a program that prints all Armstrong numbers between two given numbers.

#### Hint: Use nested loops to check if each number in the range is an Armstrong number.

#### Solution

```c
#include <stdio.h>
#include <math.h>

int main() {
    int low, high, num, original, remainder, n = 0, result = 0;
    printf("Enter two numbers (intervals): ");
    scanf("%d %d", &low, &high);
    printf("Armstrong numbers between %d and %d are: ", low, high);
    for (int i = low; i <= high; ++i) {
        num = i;
        original = num;
        while (original != 0) {
            original /= 10;
            ++n;
        }
        original = num;
        while (original != 0) {
            remainder = original % 10;
            result += pow(remainder, n);
            original /= 10;
        }
        if (result == num)
            printf("%d ", num);
        n = 0;
        result = 0;
    }
    return 0;
}
```

### Exercise 16: Calculate Power

#### Description: Write a program that calculates the power of a number using a loop.

#### Hint: Use a loop to multiply the base by itself exponent times.

#### Solution

```c
#include <stdio.h>

int main() {
    int base, exp;
    long long result = 1;
    printf("Enter base and exponent: ");
    scanf("%d %d", &base, &exp);
    for (int i = 1; i <= exp; ++i) {
        result *= base;
    }
    printf("%d^%d = %lld\n", base, exp, result);
    return 0;
}
```

### Exercise 17: Find Sum of Array Elements

#### Description: Write a program that calculates the sum of all elements in an array.

#### Hint: Use a loop to iterate through the array and add each element to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
        sum += arr[i];
    }
    printf("Sum of array elements: %d\n", sum);
    return 0;
}
```

### Exercise 18: Find Largest Element in Array

#### Description: Write a program that finds the largest element in an array.

#### Hint: Use a loop to iterate through the array and compare each element to find the largest.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, max;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
    }
    max = arr[0];
    for (int i = 1; i < n; ++i) {
        if (arr[i] > max)
            max = arr[i];
    }
    printf("Largest element: %d\n", max);
    return 0;
}
```

### Exercise 19: Reverse an Array

#### Description: Write a program that reverses the elements of an array.

#### Hint: Use a loop to iterate through the array from the end to the beginning.

#### Solution

```c
#include <stdio.h>

int main() {
    int n;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
    }
    printf("Reversed array: ");
    for (int i = n - 1; i >= 0; --i) {
        printf("%d ", arr[i]);
    }
    printf("\n");
    return 0;
}
```

### Exercise 20: Find Second Largest Element in Array

#### Description: Write a program that finds the second largest element in an array.

#### Hint: Use a loop to iterate through the array and keep track of the largest and second largest elements.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, first, second;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
    }
    first = second = arr[0];
    for (int i = 1; i < n; ++i) {
        if (arr[i] > first) {
            second = first;
            first = arr[i];
        } else if (arr[i] > second && arr[i] != first) {
            second = arr[i];
        }
    }
    printf("Second largest element: %d\n", second);
    return 0;
}
```

### Exercise 21: Find the Sum of Even Numbers

#### Description: Write a program that calculates the sum of all even numbers between 1 and a given number.

#### Hint: Use a loop to iterate through the numbers and add the even numbers to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a number: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        if (i % 2 == 0) {
            sum += i;
        }
    }
    printf("Sum of even numbers: %d\n", sum);
    return 0;
}
```

### Exercise 22: Find the Sum of Odd Numbers

#### Description: Write a program that calculates the sum of all odd numbers between 1 and a given number.

#### Hint: Use a loop to iterate through the numbers and add the odd numbers to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a number: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        if (i % 2 != 0) {
            sum += i;
        }
    }
    printf("Sum of odd numbers: %d\n", sum);
    return 0;
}
```

### Exercise 23: Find the Average of Array Elements

#### Description: Write a program that calculates the average of all elements in an array.

#### Hint: Use a loop to iterate through the array and calculate the sum, then divide by the number of elements.

#### Solution

```c
#include <stdio.h>

int main() {
    int n;
    float sum = 0.0, average;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    float arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%f", &arr[i]);
        sum += arr[i];
    }
    average = sum / n;
    printf("Average of array elements: %.2f\n", average);
    return 0;
}
```

### Exercise 24: Find the Median of Array Elements

#### Description: Write a program that calculates the median of all elements in an array.

#### Hint: Sort the array and find the middle element(s).

#### Solution

```c
#include <stdio.h>

void sort(int arr[], int n) {
    int temp;
    for (int i = 0; i < n - 1; ++i) {
        for (int j = i + 1; j < n; ++j) {
            if (arr[i] > arr[j]) {
                temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }
    }
}

int main() {
    int n;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
    }
    sort(arr, n);
    if (n % 2 == 0) {
        printf("Median: %.2f\n", (arr[n / 2 - 1] + arr[n / 2]) / 2.0);
    } else {
        printf("Median: %d\n", arr[n / 2]);
    }
    return 0;
}
```

### Exercise 25: Find the Mode of Array Elements

#### Description: Write a program that calculates the mode of all elements in an array.

#### Hint: Use a loop to count the frequency of each element and find the element with the highest frequency.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, maxCount = 0, mode;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%d", &arr[i]);
    }
    for (int i = 0; i < n; ++i) {
        int count = 0;
        for (int j = 0; j < n; ++j) {
            if (arr[j] == arr[i]) {
                count++;
            }
        }
        if (count > maxCount) {
            maxCount = count;
            mode = arr[i];
        }
    }
    printf("Mode: %d\n", mode);
    return 0;
}
```

### Exercise 26: Find the Standard Deviation of Array Elements

#### Description: Write a program that calculates the standard deviation of all elements in an array.

#### Hint: Use a loop to calculate the mean, then use another loop to calculate the variance and standard deviation.

#### Solution

```c
#include <stdio.h>
#include <math.h>

int main() {
    int n;
    float sum = 0.0, mean, variance = 0.0, stddev;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    float arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; ++i) {
        scanf("%f", &arr[i]);
        sum += arr[i];
    }
    mean = sum / n;
    for (int i = 0; i < n; ++i) {
        variance += pow(arr[i] - mean, 2);
    }
    variance /= n;
    stddev = sqrt(variance);
    printf("Standard Deviation: %.2f\n", stddev);
    return 0;
}
```

### Exercise 27: Find the Sum of Natural Numbers

#### Description: Write a program that calculates the sum of the first N natural numbers.

#### Hint: Use a loop to add the numbers from 1 to N.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        sum += i;
    }
    printf("Sum of the first %d natural numbers: %d\n", n, sum);
    return 0;
}
```

### Exercise 28: Find the Sum of Squares of Natural Numbers

#### Description: Write a program that calculates the sum of the squares of the first N natural numbers.

#### Hint: Use a loop to add the squares of the numbers from 1 to N.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        sum += i * i;
    }
    printf("Sum of the squares of the first %d natural numbers: %d\n", n, sum);
    return 0;
}
```

### Exercise 29: Find the Sum of Cubes of Natural Numbers

#### Description: Write a program that calculates the sum of the cubes of the first N natural numbers.

#### Hint: Use a loop to add the cubes of the numbers from 1 to N.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, sum = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        sum += i * i * i;
    }
    printf("Sum of the cubes of the first %d natural numbers: %d\n", n, sum);
    return 0;
}
```

### Exercise 30: Find the Sum of Prime Numbers

#### Description: Write a program that calculates the sum of all prime numbers up to a given number.

#### Hint: Use a loop to check each number up to the given number and add it to the sum if it is prime.

#### Solution

```c
#include <stdio.h>
#include <stdbool.h>

bool isPrime(int n) {
    if (n <= 1) return false;
    for (int i = 2; i <= n / 2; ++i) {
        if (n % i == 0) return false;
    }
    return true;
}

int main() {
    int n, sum = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    for (int i = 2; i <= n; ++i) {
        if (isPrime(i)) {
            sum += i;
        }
    }
    printf("Sum of prime numbers up to %d: %d\n", n, sum);
    return 0;
}
```

### Exercise 31: Find the Sum of Fibonacci Series

#### Description: Write a program that calculates the sum of the first N terms of the Fibonacci series.

#### Hint: Use a loop to generate the Fibonacci series and add the terms to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, t1 = 0, t2 = 1, nextTerm, sum = 0;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        sum += t1;
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }
    printf("Sum of the first %d terms of the Fibonacci series: %d\n", n, sum);
    return 0;
}
```

### Exercise 32: Find the Sum of Even Fibonacci Numbers

#### Description: Write a program that calculates the sum of the even terms of the Fibonacci series up to a given number of terms.

#### Hint: Use a loop to generate the Fibonacci series and add the even terms to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, t1 = 0, t2 = 1, nextTerm, sum = 0;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        if (t1 % 2 == 0) {
            sum += t1;
        }
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }
    printf("Sum of the even terms of the first %d terms of the Fibonacci series: %d\n", n, sum);
    return 0;
}
```

### Exercise 33: Find the Sum of Odd Fibonacci Numbers

#### Description: Write a program that calculates the sum of the odd terms of the Fibonacci series up to a given number of terms.

#### Hint: Use a loop to generate the Fibonacci series and add the odd terms to the sum.

#### Solution

```c
#include <stdio.h>

int main() {
    int n, t1 = 0, t2 = 1, nextTerm, sum = 0;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    for (int i = 1; i <= n; ++i) {
        if (t1 % 2 != 0) {
            sum += t1;
        }
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }
    printf("Sum of the odd terms of the first %d terms of the Fibonacci series: %d\n", n, sum);
    return 0;
}
```

### Exercise 34: Find the Sum of Digits of a Number

#### Description: Write a program that calculates the sum of the digits of a given number.

#### Hint: Use a loop to extract the digits of the number and add them.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, sum = 0, remainder;
    printf("Enter an integer: ");
    scanf("%d", &num);
    while (num != 0) {
        remainder = num % 10;
        sum += remainder;
        num /= 10;
    }
    printf("Sum of digits: %d\n", sum);
    return 0;
}
```

### Exercise 35: Find the Product of Digits of a Number

#### Description: Write a program that calculates the product of the digits of a given number.

#### Hint: Use a loop to extract the digits of the number and multiply them.

#### Solution

```c
#include <stdio.h>

int main() {
    int num, product = 1, remainder;
    printf("Enter an integer: ");
    scanf("%d", &num);
    while (num != 0) {
        remainder = num % 10;
        product *= remainder;
        num /= 10;
    }
    printf("Product of digits: %d\n", product);
    return 0;
}
```

### Exercise 36: Find the Reverse of a String

#### Description: Write a program that takes a string as input and prints its reverse.

#### Hint: Use a loop to iterate through the string from the end to the beginning.

#### Solution

```c
#include <stdio.h>
#include <string.h>

int main() {
    char str[100];
    printf("Enter a string: ");
    scanf("%s", str);
    int len = strlen(str);
    printf("Reversed string: ");
    for (int i = len - 1; i >= 0; --i) {
        printf("%c", str[i]);
    }
    printf("\n");
    return 0;
}
```


