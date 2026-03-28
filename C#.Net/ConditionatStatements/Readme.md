# 📘 C# Fundamentals: Loops  
### *(MygoMinds Training Notes)*

---

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/1.png" width="500"/>

---

# 🔀 Conditional Statements in C#

👉 Conditional statements help in **decision making**.

---

## 🔹 1.if Statement

### 📘 Definition  
👉 Executes a block of code only when a condition is true.

### 📌 Syntax
```
if(condition)
{
    // code
}
```
### 🔀 Flowchart (if Statement)

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/if-Img1.webp" width="500"/>


### 💻 Example Program
```
int age = 18;

if(age >= 18)
{
    Console.WriteLine("Adult");
}
```
## 🔹 2.if...else Statement

### 📘 Definition

👉 Executes one block if the condition is true, otherwise executes another block.

### 📌 Syntax
```
if(condition)
{
    // code
}
else
{
    // code
}
```

### 🔀 Flowchart (if...else)

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/if_else 2.webp" width="500"/>

### 💻 Example Program
```
int age = 16;

if(age >= 18)
{
    Console.WriteLine("Adult");
}
else
{
    Console.WriteLine("Minor");
}
```
## 🔹 3. if...else if...else Statement

### 📘 Definition

👉 Used to check multiple conditions and execute the first matching block.

### 📌 Syntax
```
if(condition1)
{
    // code
}
else if(condition2)
{
    // code
}
else
{
    // code
}
```

### 🔀 Flowchart (if...else if...else)

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/if_else_if_ladder-Img3.webp" width="500"/>

### 💻 Example Program
```
int marks = 75;
if(marks >= 90)
{
    Console.WriteLine("Grade A");
}
else if(marks >= 70)
{
    Console.WriteLine("Grade B");
}
else
{
    Console.WriteLine("Grade C");
}
```
## 🔹 4. switch Statement

### 📘 Definition

👉 Selects and executes one block of code from multiple options based on a variable value.

### 📌 Syntax
```
switch(variable)
{
    case value1:
        // code
        break;

    case value2:
        // code
        break;

    default:
        // code
        break;
}
```
## 🔄 Flowchart (switch Statement)

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/switch_img4.webp" width="500"/>

### 💻 Example Program
```
int day = 2;

switch(day)
{
    case 1:
        Console.WriteLine("Monday");
        break;

    case 2:
        Console.WriteLine("Tuesday");
        break;

    default:
        Console.WriteLine("Other Day");
        break;
}
```
## 🔹5. Ternary Operator (? :)

### 📘 Definition

👉 A short form of if-else used to return a value based on a condition.

### 📌 Syntax

condition ? value_if_true : value_if_false;

### 🔄Flowchart switch Statement

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/ternary -Img5.jpg" width="500"/>

### 💻 Example Program
```
int age = 20;
string result = (age >= 18) ? "Adult" : "Minor";
Console.WriteLine(result);
```

## ✅ Conditional Statements Test

### 👉 Click The Below Link For Test2:
🔗 <a href="https://online-test.classplusapp.com/?testId=69c659948fce2567a58a3d4b&defaultLanguage=en-US">Test1</a>

## 🧠 1. What is a Loop?

👉 A **Loop** is used to execute a block of code repeatedly based on a condition.

### 🔹 Why Loops?
- Reduce code repetition  
- Improve efficiency  
- Handle large data easily  

---

## 🔁 2. Types of Loops in C#

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/2.png" width="500"/>

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

---

### 📌 Observe The Number Series

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/4.png" width="500"/>

---

### 📌 Spot the Loop

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/5.png" width="500"/>

---

### 📌 Match The Following

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/6.png" width="500"/>

---

### 📌 Spot the Loop

<img src="https://github.com/mygomindsrepo2026/CSharp/blob/main/C%23.net/Loops/images/Loops/7.png" width="500"/>

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
### 👉 Click The Below Link For Test2:
🔗 <a href="https://online-test.classplusapp.com/?testId=69c659948fce2567a58a3d4b&defaultLanguage=en-US">Test2</a>
---

# 💻 Conditional Statement Programs (C#)

---

### 1️⃣ Even or Odd

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 10;
        if (num % 2 == 0)
            Console.WriteLine("Even");
        else
            Console.WriteLine("Odd");
    }
}
```

---

### 2️⃣ Day of Week (Switch)

```csharp
using System;
class Program
{
    static void Main()
    {
        int day = 2;
        switch (day)
        {
            case 1: Console.WriteLine("Monday"); break;
            case 2: Console.WriteLine("Tuesday"); break;
            case 3: Console.WriteLine("Wednesday"); break;
            case 4: Console.WriteLine("Thursday"); break;
            case 5: Console.WriteLine("Friday"); break;
            case 6: Console.WriteLine("Saturday"); break;
            case 7: Console.WriteLine("Sunday"); break;
            default: Console.WriteLine("Invalid"); break;
        }
    }
}
```

---

### 3️⃣ Divisible by 5 & 4

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 20;
        if (num % 5 == 0 && num % 4 == 0)
            Console.WriteLine("Divisible");
        else
            Console.WriteLine("Not Divisible");
    }
}
```

---

### 4️⃣ Positive, Negative, Zero

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = -5;
        if (num > 0)
            Console.WriteLine("Positive");
        else if (num < 0)
            Console.WriteLine("Negative");
        else
            Console.WriteLine("Zero");
    }
}
```

---

### 5️⃣ Largest of Two Numbers

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 10, b = 20;
        if (a > b)
            Console.WriteLine(a);
        else
            Console.WriteLine(b);
    }
}
```

---

### 6️⃣ Largest of Three Numbers

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 10, b = 20, c = 15;
        if (a > b && a > c)
            Console.WriteLine(a);
        else if (b > c)
            Console.WriteLine(b);
        else
            Console.WriteLine(c);
    }
}
```

---

### 7️⃣ Leap Year

```csharp
using System;
class Program
{
    static void Main()
    {
        int year = 2024;
        if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0)
            Console.WriteLine("Leap Year");
        else
            Console.WriteLine("Not Leap Year");
    }
}
```

---

### 8️⃣ Vowel or Consonant

```csharp
using System;
class Program
{
    static void Main()
    {
        char ch = 'a';
        if ("aeiouAEIOU".Contains(ch))
            Console.WriteLine("Vowel");
        else
            Console.WriteLine("Consonant");
    }
}
```

---

### 9️⃣ Character Type

```csharp
using System;
class Program
{
    static void Main()
    {
        char ch = 'A';
        if (char.IsUpper(ch))
            Console.WriteLine("Uppercase");
        else if (char.IsLower(ch))
            Console.WriteLine("Lowercase");
        else if (char.IsDigit(ch))
            Console.WriteLine("Digit");
        else
            Console.WriteLine("Special Character");
    }
}
```

---

### 🔟 Divisible by 3 or 7

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 21;
        if (num % 3 == 0 || num % 7 == 0)
            Console.WriteLine("Divisible");
        else
            Console.WriteLine("Not Divisible");
    }
}
```

---

### 1️⃣1️⃣ Number in Range

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 25;
        if (num >= 10 && num <= 50)
            Console.WriteLine("In Range");
        else
            Console.WriteLine("Out of Range");
    }
}
```

---

### 1️⃣2️⃣ Smallest of Three Numbers

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 10, b = 5, c = 8;
        if (a < b && a < c)
            Console.WriteLine(a);
        else if (b < c)
            Console.WriteLine(b);
        else
            Console.WriteLine(c);
    }
}
```

---

### 1️⃣3️⃣ Multiple of 2, 3, or Both

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 6;
        if (num % 2 == 0 && num % 3 == 0)
            Console.WriteLine("Multiple of Both");
        else if (num % 2 == 0)
            Console.WriteLine("Multiple of 2");
        else if (num % 3 == 0)
            Console.WriteLine("Multiple of 3");
        else
            Console.WriteLine("Not Multiple");
    }
}
```

---

### 1️⃣4️⃣ Voting Eligibility

```csharp
using System;
class Program
{
    static void Main()
    {
        int age = 20;
        if (age >= 18)
            Console.WriteLine("Eligible");
        else
            Console.WriteLine("Not Eligible");
    }
}
```

---

### 1️⃣5️⃣ Pass or Fail

```csharp
using System;
class Program
{
    static void Main()
    {
        int marks = 40;
        if (marks >= 35)
            Console.WriteLine("Pass");
        else
            Console.WriteLine("Fail");
    }
}
```

---

### 1️⃣6️⃣ Grade Calculation

```csharp
using System;
class Program
{
    static void Main()
    {
        int marks = 75;
        if (marks >= 75)
            Console.WriteLine("A");
        else if (marks >= 60)
            Console.WriteLine("B");
        else if (marks >= 35)
            Console.WriteLine("C");
        else
            Console.WriteLine("Fail");
    }
}
```

---

### 1️⃣7️⃣ Number of Digits

```csharp
using System;
class Program
{
    static void Main()
    {
        int num = 123;
        if (num >= 10 && num <= 99)
            Console.WriteLine("Two Digit");
        else if (num >= 100 && num <= 999)
            Console.WriteLine("Three Digit");
        else
            Console.WriteLine("Other");
    }
}
```

---

### 1️⃣8️⃣ Triangle Validity

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 60, b = 60, c = 60;
        if (a + b + c == 180)
            Console.WriteLine("Valid Triangle");
        else
            Console.WriteLine("Invalid");
    }
}
```

---

### 1️⃣9️⃣ Triangle Type

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 5, b = 5, c = 5;
        if (a == b && b == c)
            Console.WriteLine("Equilateral");
        else if (a == b || b == c || a == c)
            Console.WriteLine("Isosceles");
        else
            Console.WriteLine("Scalene");
    }
}
```

---

### 2️⃣0️⃣ Simple Calculator (Switch)

```csharp
using System;
class Program
{
    static void Main()
    {
        int a = 10, b = 5;
        char op = '+';

        switch (op)
        {
            case '+': Console.WriteLine(a + b); break;
            case '-': Console.WriteLine(a - b); break;
            case '*': Console.WriteLine(a * b); break;
            case '/': Console.WriteLine(a / b); break;
            default: Console.WriteLine("Invalid"); break;
        }
    }
}
```

---
## 🎯 Final Summary

- ✅ **if** → Executes code when condition is true  
- ✅ **if...else** → Chooses between two conditions  
- ✅ **if...else if...else** → Handles multiple conditions  
- ✅ **switch** → Selects one case from many options  
- ✅ **ternary operator** → Short form of if-else 

## 👉 FINAL TEST

  🔗<a href="https://online-test.classplusapp.com/?testId=69c659948fce2567a58a3d4b&defaultLanguage=en-US">Final Test</a>

  ### Practice Questions
  <a href="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/feature-Loops/C%23.Net/ConditionatStatements/Cs%20ques.md">Practice Questions</a>

---