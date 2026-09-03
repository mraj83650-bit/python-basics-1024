# Factorial Program

A simple program to calculate the **factorial of a number**.

## 📌 About

The factorial of a positive integer `n` is the product of all positive integers from `1` to `n`.

### Formula

```text
n! = n × (n-1) × (n-2) × ... × 2 × 1
```

For example:

```text
5! = 5 × 4 × 3 × 2 × 1 = 120
```

## 💻 Program

```c
#include <stdio.h>

int main() {
    int n, fact = 1;

    printf("Enter a number: ");
    scanf("%d", &n);

    for (int i = 1; i <= n; i++) {
        fact = fact * i;
    }

    printf("Factorial of %d = %d\n", n, fact);

    return 0;
}
```

## ▶️ Example Output

```text
Enter a number: 5
Factorial of 5 = 120
```

## 🛠️ Language Used

* C

## 📂 File Structure

```text
factorial/
│
├── factorial.c
└── README.md
```

## 🚀 How to Run

1. Clone the repository.
2. Open the project folder in a C compiler or IDE.
3. Compile the program.
4. Run the executable.
5. Enter a number to calculate its factorial.

## 📚 Concept Used

* Variables
* `for` loop
* User input/output
* Arithmetic operations

## 👨‍💻 Author

**Mayank Raj**

B.Tech CSE Student
