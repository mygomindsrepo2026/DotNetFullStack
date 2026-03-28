# 📘 C# Fundamentals: Loops  
### *(MygoMinds Training Notes)*

---

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/1.png" width="500"/>

---
## 🧠 1. What is a Loop?

👉 A **Loop** is used to execute a block of code repeatedly based on a condition.

### 🔹 Why Loops?
- Reduce code repetition  
- Improve efficiency  
- Handle large data easily  

---

## 🔁 2. Types of Loops in C#

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/2.png" width="500"/>

- 🔹 `for` loop  
- 🔹 `while` loop  
- 🔹 `do-while` loop  
- 🔹 `foreach` loop  

---
## 🔹 3. for Loop

👉 Used when the number of iterations is known.

### 📌 Syntax:

```csharp
for(initialization; condition; increment/decrement)
{
    // code
}
```

---

### 📌 Example: Print "MygoMinds" 5 Times

```csharp
for(int i = 1; i <= 5; i++)
{
    Console.WriteLine("MygoMinds");
}
```
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/3.png" width="500"/>

---

### 📌 Observe The Number Series

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/4.png" width="500"/>

---

### 📌 Spot the Loop

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/5.png" width="500"/>


---

### 📌 Match The Following
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/6.png" width="500"/>


---

### 📌 Spot the Loop

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/7.png" width="500"/>


---

## 🔹 4. while Loop

👉 Used when the number of iterations is **not known**.

### 📌 Syntax:

```csharp
while(condition)
{
    // code
}
```

### 📌 Example:

```csharp
int i = 1;

while(i <= 5)
{
    Console.WriteLine(i);
    i++;
}
```

---

## 🔹 5. do-while Loop

👉 Executes at least **once**, even if condition is false.

### 📌 Syntax:

```csharp
do
{
    // code
}
while(condition);
```

### 📌 Example:

```csharp
int i = 1;

do
{
    Console.WriteLine(i);
    i++;
}
while(i <= 5);
```
---

## 🔹 6. foreach Loop

👉 Used to iterate through collections like arrays.

### 📌 Syntax:

```csharp
foreach(type variable in collection)
{
    // code
}
```

### 📌 Example:

```csharp
int[] numbers = {1, 2, 3, 4, 5};

foreach(int num in numbers)
{
    Console.WriteLine(num);
}
```
### 👉 Click The Below Link For Test1:
🔗 <a href="https://online-test.classplusapp.com/?testId=69c659948fce2567a58a3d4b&defaultLanguage=en-US">Test1</a>
---

## 💻 Coding Questions

### 1️⃣ Check whether a number is Even or Odd 
```
using System;
class Program
{
    static void Main()
    {
        int num = 10;
        if (num % 2 == 0)
            Console.WriteLine("Even Number");
        else
            Console.WriteLine("Odd Number");
    }
}
```
### 2️⃣ Display Day of Week  
```
using System;
class Program
{
    static void Main()
    {
        int day = 3;
        switch (day)
        {
            case 1: Console.WriteLine("Monday");
            break;
            case 2: Console.WriteLine("Tuesday"); 
            break;
            case 3: Console.WriteLine("Wednesday"); 
            break;
            case 4: Console.WriteLine("Thursday"); 
            break;
            case 5: Console.WriteLine("Friday"); 
            break;
            case 6: Console.WriteLine("Saturday"); 
            break;
            case 7: Console.WriteLine("Sunday"); 
            break;
            default: Console.WriteLine("Invalid day"); break;
        }
    }
}
```
## 3️⃣ Check whether a number is divisible by 5 & 4
```
using System;
class Program
{
    static void Main()
    {
        int num = 20;
        if (num % 5 == 0 && num % 4 == 0)
            Console.WriteLine("Divisible by 5 and 4");
        else
            Console.WriteLine("Not divisible");
    }
}
```
## 4️⃣ Fibonacci Series 

👉 A **Fibonacci series** is a sequence of numbers where each number is the sum of the two previous numbers.

📌 Example: 0, 1, 1, 2, 3, 5, 8...
```
using System;
class Program
{
    static void Main()
    {
        int n1 = 0, n2 = 1, n3, i;
        Console.WriteLine(n1);
        Console.WriteLine(n2);
        for (i = 2; i < 10; i++)
        {
            n3 = n1 + n2;
            Console.WriteLine(n3);
            n1 = n2;
            n2 = n3;
        }
    }
}
```
## 5️⃣ Prime Number

👉 A **prime number** is a number greater than 1 that has only two factors: 1 and itself. 

📌 Example: 2, 3, 5, 7, 11...
```
using System;
class Program
{
    static void Main()
    {
        int num = 7;
        int count = 0;
        for (int i = 1; i <= num; i++)
        {
            if (num % i == 0)
                count++;
        }
        if (count == 2)
            Console.WriteLine("Prime Number");
        else
            Console.WriteLine("Not Prime Number");
    }
}
```
## 6️⃣ Factorial of a Number

👉 The **factorial** of a number is the product of all positive integers from 1 up to that number.  

📌 Example: 5! = 5 × 4 × 3 × 2 × 1 = 120 
```
using System;
class Program
{
    static void Main()
    {
        int num = 5;
        int fact = 1;
        for (int i = 1; i <= num; i++)
        {
            fact = fact * i;
        }
        Console.WriteLine("Factorial = " + fact);
    }
}
```
## 7️⃣ Palindrome Number

👉 A **palindrome** is a number or string that reads the same forward and backward.

📌 Example: 121, "madam"
```
using System;
class Program
{
    static void Main()
    {
        int num = 121, rev = 0, rem, temp;
        temp = num;
        while (num > 0)
        {
            rem = num % 10;
            rev = rev * 10 + rem;
            num = num / 10;
        }
        if (temp == rev)
            Console.WriteLine("Palindrome");
        else
            Console.WriteLine("Not Palindrome");
    }
}
```
## 8️⃣ Armstrong Number

👉 An **Armstrong number** is a number where the sum of its digits raised to the power of the number of digits equals the number itself.

📌 Example: 153 = 1³ + 5³ + 3³  
```
using System;
class Program
{
    static void Main()
    {
        int num = 153, sum = 0, rem, temp;
        temp = num;
        while (num > 0)
        {
            rem = num % 10;
            sum = sum + (rem * rem * rem);
            num = num / 10;
        }
        if (sum == temp)
            Console.WriteLine("Armstrong Number");
        else
            Console.WriteLine("Not Armstrong");
    }
}
```
## 9️⃣ Anagram

👉 An **anagram** is a word formed by rearranging the letters of another word using all original letters exactly once. 

📌 Example: "listen" → "silent"
```
using System;
class Program
{
    static void Main()
    {
        string str1 = "listen";
        string str2 = "silent";
        char[] a = str1.ToCharArray();
        char[] b = str2.ToCharArray();
        Array.Sort(a);
        Array.Sort(b);
        string s1 = new string(a);
        string s2 = new string(b);
        if (s1 == s2)
            Console.WriteLine("Anagram");
        else
            Console.WriteLine("Not Anagram");
    }
}
```

## 🔟 check whether a number is a perfect number or not

👉A **perfect number** is a number whose sum of proper divisors (excluding itself) equals the number.

📌 6 → divisors: 1, 2, 3 → sum = 6

```
using System;
class PerfectNumber
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        int num = int.Parse(Console.ReadLine());
        int sum = 0;
        for (int i = 1; i <= num / 2; i++)
        {
            if (num % i == 0)
            {
                sum += i;
            }
        }
        if (sum == num && num != 0)
        {
            Console.WriteLine(num + " is a Perfect Number.");
        }
        else
        {
            Console.WriteLine(num + " is NOT a Perfect Number.");
        }
    }
}
```
### Practice Coding Questions
<a href="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/feature-Loops/C%23.Net/Loops/practicereadme.md">Practice Questions</a>


