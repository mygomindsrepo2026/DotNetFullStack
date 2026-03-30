#  Classes and Objects in OOPS

---

##  Introduction

In Object-Oriented Programming (OOPS), **Classes and Objects** are the fundamental building blocks.

They help us model real-world entities in code, making programs more structured and reusable.

---

##  What is a Class?

A **Class** is a blueprint or template used to create objects.
It defines **properties (variables)** and **behaviors (methods)**.

### 🔹 Example (C#)

```csharp
class Car
{
    public string brand;
    public int speed;

    public void Drive()
    {
        Console.WriteLine("Car is moving");
    }
}
```

---

##  What is an Object?

An **Object** is an instance of a class.
It represents a real-world entity and can access the class properties and methods.

### 🔹 Example (C#)

```csharp
Car myCar = new Car();
myCar.brand = "Toyota";
myCar.speed = 120;

myCar.Drive();
```

---

## 🔁 Class vs Object

| Feature    | Class               | Object          |
| ---------- | ------------------- | ----------------- |
| Definition | Blueprint           | Instance of class |
| Memory     | No memory allocated | Memory allocated  |
| Example    | Car                 | BMW, Audi         |
| Purpose    | Define structure    | Use functionality |

---

##  Real-Time Example

###  Mobile Phone

* **Class** → Mobile
* **Objects** → iPhone, Samsung
* **Properties** → Brand, Price
* **Methods** → Call(), Message()

---

##  Creating Multiple Objects

```csharp
Car car1 = new Car();
car1.brand = "BMW";

Car car2 = new Car();
car2.brand = "Audi";
```

---

##  Access Modifiers (Basic)

| Modifier  | Description               |
| --------- | ------------------------- |
| public    | Accessible everywhere     |
| private   | Accessible within class   |
| protected | Accessible in inheritance |

---

##  Advantages

* ✅ Easy to understand real-world problems
* ✅ Code reusability
* ✅ Better structure
* ✅ Simplifies development

---

##  Conclusion

* A **Class** defines the structure
* An **Object** uses that structure

Together, they form the **foundation of OOPS concepts**.

---

### Tests for Classes And Object

---

<a href="https://online-test.classplusapp.com/?testId=67e16ce4732c700d72ee14c6&defaultLanguage=en-US">Test1</a>

---

<a href="https://online-test.classplusapp.com/?testId=67e2c4d18436a74bf55b79e2&defaultLanguage=en-US">Test2</a>




