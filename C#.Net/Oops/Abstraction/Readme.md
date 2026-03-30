<img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/26.png" width="500"/>

---

#  Abstraction in OOPS

---

## Introduction

**Abstraction** is one of the core concepts of Object-Oriented Programming (OOPS).

It means **hiding internal implementation details** and showing only the **essential features** to the user.

👉 In simple words:

> “Show what is necessary, hide how it works.”

---

##  Real-Time Example

###  Car

* You can **drive a car** without knowing how the engine works
* You only use **steering, brake, accelerator**

👉 This is **Abstraction**

---

##  How Abstraction is Achieved in C#

Abstraction is implemented using:

1. **Abstract Classes**
2. **Interfaces**

---

## 1️⃣ Abstract Class

An **abstract class** cannot be instantiated.
It can contain:

* Abstract methods (without body)
* Normal methods (with body)

### 🔹 Example

```csharp
abstract class Animal
{
    public abstract void Sound(); // abstract method

    public void Sleep()
    {
        Console.WriteLine("Animal is sleeping");
    }
}

class Dog : Animal
{
    public override void Sound()
    {
        Console.WriteLine("Bark");
    }
}
```

---

## 2️⃣ Interface


<p align="left">
  <a href="https://github.com/mygomindsrepo2026/DotNetFullStack/tree/main/C%23.Net/Oops/Abstraction"> 
    <b style="font-size:20px; margin-left:10px;">Abstraction</b>
  </a>
</p>

---

An **interface** contains only method declarations (no implementation).

### 🔹 Example

```csharp
interface IVehicle
{
    void Start();
}

class Car : IVehicle
{
    public void Start()
    {
        Console.WriteLine("Car started");
    }
}
```

---

## 🔁 Abstract Class vs Interface

| Feature        | Abstract Class          | Interface         |
| -------------- | ----------------------- | ----------------- |
| Methods        | Abstract + Normal       | Only Abstract     |
| Implementation | Can have implementation | No implementation |
| Inheritance    | Single                  | Multiple          |
| Use Case       | Base class              | Contract          |

---

##  Key Points

* Hides unnecessary details
* Improves code security
* Focuses on **what**, not **how**
* Achieved using abstract classes and interfaces

---

##  Advantages of Abstraction

* ✅ Reduces complexity
* ✅ Increases maintainability
* ✅ Enhances security
* ✅ Improves code reusability

---

##  Conclusion

Abstraction is used to:

* Hide complex logic
* Expose only required functionality

It makes applications **clean, scalable, and easy to manage**.

---


<a href="https://online-test.classplusapp.com/?testId=67e40e1e7eeefb2239b1eae8&defaultLanguage=en-US">Test3</a>

---

<a href="https://online-test.classplusapp.com/?testId=67ebf60258510b94ffd42bef&defaultLanguage=en-US">Test4</a>

---


