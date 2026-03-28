# 💻 Conditional Statements – Complete Readme (C#)

---

## 🔹 Spot the Operator Names

| Operator | Name                     |   |            |
| -------- | ------------------------ | - | ---------- |
| `<`      | Less than                |   |            |
| `!=`     | Not equal to             |   |            |
| `>`      | Greater than             |   |            |
| `&&`     | Logical AND              |   |            |
| `<=`     | Less than or equal to    |   |            |
| `        |                          | ` | Logical OR |
| `>=`     | Greater than or equal to |   |            |
| `==`     | Equal to                 |   |            |

---

## 🔹 Spot the Outputs

| Expression           | Output |
| -------------------- | ------ |
| `2 < 3`              | True   |
| `3 + 4 * 2 <= 7`     | False  |
| `4 > 5`              | False  |
| `9 * 8 + 3 >= 4`     | True   |
| `4 == 2 + 2`         | True   |
| `3 * 2 == 6`         | True   |
| `"mygo" == "mygo"`   | True   |
| `234 == 432`         | False  |
| `'a' == 'A'`         | False  |
| `2 == '2'`           | False  |
| `6 % 2 == 0`         | True   |
| `7 % 2 != 0`         | True   |
| `2 * 3 == 6`         | True   |
| `"admin" == "maidn"` | False  |
| `"mom" == "mom"`     | True   |
| `"Dad" == "daD"`     | False  |

---

## 🔹 Interview Questions

1. What are conditional statements in C#.net?
2. What are the different types of conditional statements?
3. How do you write an if statement?
4. How do you write an if-else statement?
5. How do you write an if-else if-else statement?
6. What is a nested if statement?
7. Provide an example of conditional statements.
8. How to use logical operators (&&, ||, !)?
9. Write syntax of if-else?
10. Write syntax of else-if?
11. Write syntax of multiple if?
12. Write syntax of nested if?

---

## 🔹 Recommended Conditional Statements

| Problem                    | Recommended Statement |
| -------------------------- | --------------------- |
| Even or Odd                | if-else               |
| Biggest of 2 numbers       | if-else               |
| Biggest of 3 numbers       | if-else if            |
| Positive / Negative / Zero | if-else if            |
| Divisible by 5 and 11      | if                    |
| Uppercase / Lowercase      | if-else               |
| Age between 18–25          | if                    |
| Grade calculation          | if-else if            |
| Menu selection             | switch                |

---

## 🔹 When to Use

* **if** → Single condition
* **if-else** → Two conditions
* **if-else if** → Multiple conditions
* **nested if** → Condition inside another condition
* **switch** → Multiple fixed values

---

## 🔹 Spot Output Programs

### Program 1

```csharp
int x = 10, y = 20;
if (x == y);
Console.WriteLine(x, y);
```

👉 Output: `10 20` (because of semicolon after if)

---

### Program 2

```csharp
int x = 10, y = 10;
if (x % 2 == y);
Console.WriteLine("Equal");
```

👉 Output: `Equal` (if condition ignored)

---

## 🔹 Spot the Condition Type

| Problem                       | Type        |
| ----------------------------- | ----------- |
| Even or Odd                   | if-else     |
| Positive / Negative           | if-else     |
| Positive / Negative / 0       | if-else if  |
| Vowel or Consonant            | if-else     |
| Voting eligibility            | if          |
| Gender                        | if-else     |
| Leap year                     | if          |
| Uppercase / Lowercase         | if-else     |
| Uppercase / Lowercase / Digit | if-else if  |
| Greatest of 2 numbers         | if-else     |
| Greatest of 3 numbers         | if-else if  |
| Discount condition            | nested if   |
| Grade calculation             | if-else if  |
| Divisible by 2                | if          |
| Login validation              | if-else     |
| Customer discount             | nested if   |
| Multiple error messages       | multiple if |
| Course selection              | switch      |
| Day of week                   | switch      |
| Banking options               | switch      |

---

## 🔹 Programs (Questions)

1. Check whether a number is positive or negative
2. Check whether a number is even or odd
3. Check whether a number is divisible by 5 and 11
4. Find biggest among two numbers
5. Find biggest among three numbers
6. Bank transaction (deposit/withdraw)
7. Employee bonus calculation
8. Student grade classification
9. Check leap year
10. Check lowercase or uppercase
11. Check alphabet or not
12. Check uppercase/lowercase alphabet
13. Triangle validity
14. Triangle type
15. Profit or loss

---

## 🔹 Type Conversion Questions

### 1. Char to Int

* Returns ASCII value
  👉 Example: `'A' → 65`

### 2. Int to Char

* Converts ASCII to character
  👉 Example: `65 → 'A'`

### 3. Increment Character

* Moves to next character
  👉 Example: `'A'++ → 'B'`

---


