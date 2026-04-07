this is readme fileCollections in C#
<p align="center"> <b>Learn Collections with examples, visuals & interview focus 🚀</b> </p>
<!-- ================= INTRO SECTION ================= --> <table> <tr> <td width="65%"> <img src="https://github.com/mygomindsrepo2026/DotNetFullStack/blob/main/C%23.Net/Images/collections.png" width="100%"/> </td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="250"/> </a> <br/>

<b>🎥 Collections Interview Questions</b>

</td> </tr> </table>
🔹 What are Collections?

Collections in C# are used to store and manage groups of objects dynamically.

👉 Key Points:

Dynamic size (Resizable)
Built-in methods
Easy data manipulation
🔹 Types of Collections
<table> <tr> <td width="65%">
1️⃣ Non-Generic Collections
Stores data as object
No type safety 
Slower performance

 Examples:

ArrayList
Hashtable
Stack
Queue
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 Non-Generic Explained</b> </td> </tr> </table>
<table> <tr> <td width="65%">
2️⃣ Generic Collections ⭐
Type-safe ✅
Faster 🚀
Compile-time checking

 Examples:

List<T>
Dictionary<TKey, TValue>
Stack<T>
Queue<T>
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 Generic Collections</b> </td> </tr> </table>
🔹 Common Collection Classes
<table> <tr> <td width="65%">
Collection	Description
List<T>	Dynamic array
Dictionary<TKey, TValue>	Key-value pairs
Stack<T>	LIFO
Queue<T>	FIFO
HashSet<T>	Unique items
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 Collections Overview</b> </td> </tr> </table>
🔹 Example: List<T>
<table> <tr> <td width="65%">

 <code>
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        List<string> names = new List<string>();

        names.Add("John");
        names.Add("Alice");

        foreach (var name in names)
        {
            Console.WriteLine(name);
        }
    }
}
</code>
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 List Example</b> </td> </tr> </table>
🔹 Example: Dictionary
<table> <tr> <td width="65%">
  <code>
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        Dictionary<int, string> students = new Dictionary<int, string>();

        students.Add(1, "John");
        students.Add(2, "Alice");

        Console.WriteLine(students[1]);
    }
}
</code>
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 Dictionary Example</b> </td> </tr> </table>
🔹 When to Use Which?
<table> <tr> <td width="65%">
Scenario	Collection
Ordered list	List<T>
Key-value data	Dictionary
Unique values	HashSet
Undo operations	Stack
Queue system	Queue
</td> <td width="35%" align="center"> <a href="https://www.youtube.com/watch?v=OMb4OUTRrhQ"> <img src="https://img.youtube.com/vi/OMb4OUTRrhQ/0.jpg" width="200"/> </a> <br/> <b>🎥 Interview Tips</b> </td> </tr> </table>
🔹 Advantages
✔ Dynamic size
✔ High performance
✔ Type safety
✔ Easy to use
✔ Flexible
🧪 Practice Tests
<p align="center">

<a href="https://online-test.classplusapp.com/?testId=67e16ce4732c700d72ee14c6&defaultLanguage=en-US">📝 Test 1</a> |
<a href="https://online-test.classplusapp.com/?testId=67e2c4d18436a74bf55b79e2&defaultLanguage=en-US">📝 Test 2</a> |
<a href="https://online-test.classplusapp.com/?testId=67e40e1e7eeefb2239b1eae8&defaultLanguage=en-US">📝 Test 3</a>

</p>
🏁 Conclusion

👉 Collections are must-know for interviews & real projects
👉 Always use Generic Collections for better performance
