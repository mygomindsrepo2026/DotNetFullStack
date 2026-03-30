# 🔄 Polymorphism in OOPS

---

##  Introduction

**Polymorphism** means **“many forms”**.

👉 A single method can behave differently based on input.

---

##  Real-Time Example

###  Phone

* Same button → Different actions (call, video call)

---

##  Types of Polymorphism

1. **Compile-Time (Method Overloading)**
2. **Run-Time (Method Overriding)**

---

## 1️⃣ Method Overloading

```csharp
class MathOperations
{
    public int Add(int a, int b)
    {
        return a + b;
    }

    public double Add(double a, double b)
    {
        return a + b;
    }
}
```

---

## 2️⃣ Method Overriding

```csharp
class Animal
{
    public virtual void Sound()
    {
        Console.WriteLine("Animal sound");
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

##  Key Points

* Same method name
* Different behavior
* Improves flexibility

---

##  Advantages

* ✅ Code flexibility
* ✅ Reusability
* ✅ Easy extension

---

##  Conclusion

Polymorphism allows:

* Writing flexible and scalable code
* Using one interface for multiple behaviors

---


<a href="https://online-test.classplusapp.com/?testId=6801b8841bc4af0efc2b1546&defaultLanguage=en-US">Test9</a>

---

<a href="https://online-test.classplusapp.com/?testId=67efd481cf3f7315352c16c1&defaultLanguage=en-US">Test10</a>

---