#  C# Fundamentals: Arrays

### *(MygoMinds Training Notes)*

---

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/60Arr.png" width="500"/>

###  Arrays Practice Test Links

<p align="center">

<a href="https://online-test.classplusapp.com/?testId=69cb65737b16650a5e72253b&defaultLanguage=en-US">
📝 <b>Test1</b>
</a> &nbsp; | &nbsp;

<a href="https://online-test.classplusapp.com/?testId=69cb660f79ac2ebe355172c0&defaultLanguage=en-US">
📝 <b>Test2</b>
</a> &nbsp; | &nbsp;

<a href="https://online-test.classplusapp.com/?testId=69cb66fcc18c96084624b2c5&defaultLanguage=en-US">
📝 <b>Test3</b>
</a> &nbsp; | &nbsp;

<a href="https://online-test.classplusapp.com/?testId=69cb6652bf6704ce5d0fcf37&defaultLanguage=en-US">
📝 <b>Test4</b>
</a>

</p>

##  1. What is Data?

👉 **Data** represents values that programs process and manipulate.
Data can be categorized into **Literals** and **Objects**.

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/61.png" width="500"/>

### 🔹 Literals

**Literals are fixed values directly written in code.**

**Examples:**

* Integer → `10`
* Floating Point → `10.5`
* Character → `'A'`
* String → `"Hello"`

---

### 🔹 Objects

**Objects represent real-world entities with properties.**

**Example:**

```
empId : 101  
name : Ram  
salary : 20000
```

##  2. Containers in Programming

**Containers Are Used To store the data.**

##  Container	Description	Example

| Container | Description  |            Example  |
|-----------|----------------------|--------------|
| Variable  | Stores single value  |  age=25  |
| Array     | Stores similar values| [78, 89, 67, 83, 76] |
| Object    | Represents entity    | Employee details |
| Collection| Group of objects     | List of employees |

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/62.png" width="500"/>

##  3. Match the Following

| Example                       | Type       |
| ----------------------------- | ---------- |
| 78.3                          | Variable   |
| 248                           | Variable   |
| "jai","ram","preeti","robert" | Array      |
| 78,89,67,83,76                | Array      |
| empId,name,salary             | Object     |
| list of employees             | Collection |
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/63.png" width="500"/>

### 👉 Click The Below Link For Test1(Basics):
 <a href="https://online-test.classplusapp.com/?testId=69cb65737b16650a5e72253b&defaultLanguage=en-US"><b>Test1 </b></a>

##  4. Operations on Data

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/65.png" width="500"/>

### Operations on Numbers

* Discount
* GST
* Total Cost
* Percentage
* Currency Converter
* Salary Calculations
* Tax
* ROI
* Budget
* Loan Eligibility
* Profit & Loss
* Even / Odd
* Prime Number
* Perfect Number
* Palindrome
* Armstrong Number
* Factorial
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/66.png" width="500"/>

###  Operations on Strings

* Length of string
* Concatenation
* Count vowels & consonants
* Count uppercase & lowercase
* Count digits
* Reverse string
* Check palindrome
* Check anagram
* Check pangram
* Compare strings
* Reverse words
* Search word
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/67.png" width="500"/>


## 5. Arrays

👉 An **Array** is a data structure used to store multiple values of the same type.

###  Example

```
Values : 2 4 3 5 7 9 6  
Index  : 0 1 2 3 4 5 6
```
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/71.png" width="500"/>


### 🔹characteristics of Arrays

* Stores homogeneous values
* Fixed size
* Access using index
* Index starts from 0
* Last index = size - 1

---
## 🔁 Types of Arrays in C#
👉**Arrays** are classified into different types based on structure.
### 🔹 1. Single-Dimensional Array
**👉 Stores elements in a linear sequence.**

###  Example:
```
int[] arr = {1, 2, 3, 4, 5};
```
### 🔹 2. Multi-Dimensional Array
**👉 Stores data in rows and columns (table format).**
###  Example:
```
int[,] matrix = {
    {1, 2},
    {3, 4}
};
```
### 🔹 3. Jagged Array
**👉 Array of arrays (each row can have different sizes).**
###  Example:
```
int[][] jagged = new int[2][];
jagged[0] = new int[] {1, 2, 3};
jagged[1] = new int[] {4, 5};
```

### 👉 Click The Below Link For Test2:

<a href="https://online-test.classplusapp.com/?testId=69cb660f79ac2ebe355172c0&defaultLanguage=en-US"> <b>Test2</b> </a>

---
##  6. Array Operations

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/68.png" width="500"/>

### Given Array:

```
2 4 3 5 7 9 6
```

### 🔹 Sum of Elements

```
2 + 4 + 3 + 5 + 7 + 9 + 6 = 36
```

### 🔹 Sum of First & Last

```
2 + 6 = 8
```

### 🔹 Sum of Even Elements

```
2 + 4 + 6 = 12
```

### 🔹 Sum of Odd Elements
```
3 + 5 + 7 + 9 = 24
```
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/69.png" width="500"/>

##  7. Searching in Arrays

<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/70.png" width="500"/>

### 🔹 Maximum Element
```
Max = 9
```
### 🔹 Minimum Element

```
Min = 2
```
### 🔹 Sum of Max & Min
```
2 + 9 = 11
```
### 🔹 Middle Element
```
Middle = 5
```
---
##  8. Searching Techniques

### 🔹 Linear Search
👉 Checks each element sequentially.
### 🔹 Binary Search
👉 Divides array into halves for faster searching.
---
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/68.png" width="500"/>

##  9. Sorting in Arrays

👉 Sorting arranges elements in order.

### 🔹 Types

* Ascending Order
* Descing Order

###  Example
**Ascending:**
```
2 3 4 5 6 7 9
```
**Descending:**
```
9 7 6 5 4 3 2
```
## 🔁 10. Swapping Elements
👉 Swapping means exchanging two values.
###  Example
**Before Swap**
```
a = 5  
b = 10
```

**After Swap**
```
a = 10  
b = 5
```

### 👉 Click The Below Link For Test3:
<a href="https://online-test.classplusapp.com/?testId=69cb66fcc18c96084624b2c5&defaultLanguage=en-US"> <b>Test3 </b></a>

##  Final Summary
* Data represents values used in programs
* Containers store data (Variable, Array, Object, Collection)
* Arrays store multiple similar values
* Index starts from 0
### Arrays Support:
* Searching
* Sorting
* Summation
* Swapping
* Logical operations
---
## based on the below figure create an array to strore 6 even and 6 odd numbers
<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/72.png" width="500"/>

##  Practice Problems

### 1️⃣ Find maximum element

```
int[] arr = {10, 20, 30, 5};
int max = arr[0];

foreach(int num in arr)
{
    if(num > max)
        max = num;
}
Console.WriteLine("Max: " + max);
```
### 2️⃣ Find minimum element
```
int min = arr[0];

foreach(int num in arr)
{
    if(num < min)
        min = num;
}
Console.WriteLine("Min: " + min);
```

### 3️⃣ Find sum of elements
```
int sum = 0;

foreach(int num in arr)
{
    sum += num;
}
Console.WriteLine("Sum: " + sum);
```
### 4️⃣ Reverse an array
```
Array.Reverse(arr);

foreach(int num in arr)
{
    Console.Write(num + " ");
}
```
### 5️⃣ Count even & odd numbers
```
int even = 0, odd = 0;

foreach(int num in arr)
{
    if(num % 2 == 0)
        even++;
    else
        odd++;
}
Console.WriteLine($"Even: {even}, Odd: {odd}");
```
### 6️⃣ Find duplicates
```
for(int i = 0; i < arr.Length; i++)
{
    for(int j = i + 1; j < arr.Length; j++)
    {
        if(arr[i] == arr[j])
            Console.WriteLine("Duplicate: " + arr[i]);
    }
}
```
### 7️⃣ Merge two arrays
```
int[] a = {1, 2};
int[] b = {3, 4};
int[] c = new int[a.Length + b.Length];

a.CopyTo(c, 0);
b.CopyTo(c, a.Length);

foreach(int num in c)
{
    Console.Write(num + " ");
}
```
### 8️⃣ Second Largest Element
```
int first = int.MinValue, second = int.MinValue;

foreach(int num in arr)
{
    if(num > first)
    {
        second = first;
        first = num;
    }
    else if(num > second && num != first)
    {
        second = num;
    }
}
Console.WriteLine("Second Largest: " + second);
```
### 9️⃣ Remove Duplicates
```
var unique = arr.Distinct();

foreach(int num in unique)
{
    Console.Write(num + " ");
}
```
### 🔟 Frequency of Elements
```
for(int i = 0; i < arr.Length; i++)
{
    int count = 1;
    bool visited = false;

    for(int j = i - 1; j >= 0; j--)
    {
        if(arr[i] == arr[j])
        {
            visited = true;
            break;
        }
    }
    if(!visited)
    {
        for(int j = i + 1; j < arr.Length; j++)
        {
            if(arr[i] == arr[j])
                count++;
        }
        Console.WriteLine($"{arr[i]} occurs {count} times");
    }
}
```
### 1️⃣1️⃣ Linear Search
 Definition
 **Linear Search** is a searching technique where each element in the array is checked one by one until the required element is found.

```
int key = 20;

for(int i = 0; i < arr.Length; i++)
{
    if(arr[i] == key)
        Console.WriteLine("Found at index " + i);
}
```
### 1️⃣2️⃣ Binary Search

👉 **Binary Search** is an efficient searching technique that works on sorted arrays by repeatedly dividing the search space into halves.
```
Array.Sort(arr);
int index = Array.BinarySearch(arr, 20);
Console.WriteLine("Index: " + index);
```
### 1️⃣3️⃣ Sort Array
👉**Sorting** is the process of arranging elements in a specific order such as ascending or descending.
```
Array.Sort(arr);

foreach(int num in arr)
{
    Console.Write(num + " ");
}
```
### 1️⃣4️⃣ Check if Array is Palindrome
👉 An array is palindrome if it reads the same forward and backward.
```
int[] arr = {1, 2, 3, 2, 1};
bool isPalindrome = true;
for(int i = 0; i < arr.Length / 2; i++)
{
    if(arr[i] != arr[arr.Length - 1 - i])
    {
        isPalindrome = false;
        break;
    }
}
if(isPalindrome)
    Console.WriteLine("Palindrome Array");
else
    Console.WriteLine("Not Palindrome");
```
### 1️⃣5️⃣ Find Missing Number in Array
👉 Find missing number from sequence (1 to n)
```
int[] arr = {1, 2, 4, 5}; // Missing 3
int n = arr.Length + 1;
int expectedSum = n * (n + 1) / 2;
int actualSum = 0;
foreach(int num in arr)
{
    actualSum += num;
}
Console.WriteLine("Missing Number: " + (expectedSum - actualSum));
```
---
### 👉 Click The Below Link For Test4:
<a href="https://online-test.classplusapp.com/?testId=69cb6652bf6704ce5d0fcf37&defaultLanguage=en-US "><b>Test4</b></a>

---
## Practice Coding Questions

<a href="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Arrays/ArrPraQues.md">
<b>Practice Questions</b> </a>

---

Training material provided by **MygoMinds**
