# 📘 Post 2 – Arrays (Introductory)

## 📦 What is an Array?
- An **array** is a collection of elements stored at **contiguous memory locations**.
- All elements are of the **same data type**.
- Each element can be accessed using its **index** (position).


## 🎯 Why Arrays?
- Store multiple values in a **single variable**.
- Provide **fast access (O(1))** using index.
- Serve as the **foundation** for advanced DSA concepts like Stacks, Queues, Hash Tables.


## 🧩 Daily Life Examples
- 📚 **Books in a rack** → Shelf position = index, Book = element.  
- 🎥 **Seats in a cinema hall row** → Seat number = index, Person = element.  
- 📱 **Photos in phone gallery** → Photo index = position, Photo = element.  

## ⚡ Key Properties
- Fixed size (in many languages like C, C++, Java).  
- Fast access (direct index lookup).  
- Costly insertion/deletion in the middle (requires shifting).  

## ✅ Code Example 1 (C++)
```c++
#include <iostream>
using namespace std;

int main() {
    int arr[] = {10, 20, 30, 40, 50};

    // Accessing elements
    cout << arr[0] << endl;  // 10
    cout << arr[2] << endl;  // 30

    // Updating element
    arr[1] = 25;
    for (int i = 0; i < 5; i++) {
        cout << arr[i] << " "; // 10 25 30 40 50
    }

    return 0;
}
```


## ✅ Code Example 2 (Java)
```java
public class ArrayExample {
    public static void main(String[] args) {
        int[] arr = {10, 20, 30, 40, 50};

        // Accessing elements
        System.out.println(arr[0]);  // 10
        System.out.println(arr[2]);  // 30

        // Updating element
        arr[1] = 25;
        for (int num : arr) {
            System.out.print(num + " "); // 10 25 30 40 50
        }
    }
}
```

## ✅ Code Example 3 (Python)
```python
# Creating an array (list in Python)
arr = [10, 20, 30, 40, 50]

# Accessing elements
print(arr[0])  # 10
print(arr[2])  # 30

# Updating element
arr[1] = 25
print(arr)  # [10, 25, 30, 40, 50]
```

## 📌 Takeaway
- Arrays = ordered collection of same-type elements.
- They provide fast access but often have fixed size.
- Foundation for many advanced DSA concepts.


➡️ Next Post: Types of Arrays & Basic Operations
