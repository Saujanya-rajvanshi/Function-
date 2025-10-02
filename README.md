# Function-
Function type on return and argument 

Here are examples for all four cases:

---

### 1. **No Return, No Argument**
```c
#include <stdio.h>

// Function with no return and no arguments
void greet() {
    printf("Hello! Welcome to the program.\n");
}

int main() {
    greet(); // Call the function
    return 0;
}
```

**Output:**
```
Hello! Welcome to the program.
```

---

### 2. **No Return, But Argument**
```c
#include <stdio.h>

// Function with no return but with arguments
void displayNumber(int num) {
    printf("The number is: %d\n", num);
}

int main() {
    int n = 25;
    displayNumber(n); // Call the function and pass an argument
    return 0;
}
```

**Output:**
```
The number is: 25
```

---

### 3. **Return With Argument**
```c
#include <stdio.h>

// Function with return and arguments
int addNumbers(int a, int b) {
    return a + b; // Return the sum of the two numbers
}

int main() {
    int num1 = 10, num2 = 20;
    int sum = addNumbers(num1, num2); // Call the function and store the result
    printf("The sum is: %d\n", sum);
    return 0;
}
```

**Output:**
```
The sum is: 30
```

---

### 4. **Return Without Argument**
```c
#include <stdio.h>

// Function with return and no arguments
int getNumber() {
    return 42; // Return a fixed number
}

int main() {
    int num = getNumber(); // Call the function and store the result
    printf("The number is: %d\n", num);
    return 0;
}
```

**Output:**
```
The number is: 42
``` 

### Explanation of Each Case:
1. **No Return, No Argument**: The function doesn't return any value or take input.
2. **No Return, But Argument**: The function takes input but doesn't return any value.
3. **Return With Argument**: The function takes input and returns a result.
4. **Return Without Argument**: The function doesn't take input but returns a result.

