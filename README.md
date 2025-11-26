# Simple Python Calculator

A beginner-friendly command-line calculator that accepts two user inputs, asks for an operation, and performs basic arithmetic using Python’s modern `match-case` control flow. Includes error handling for invalid inputs. 

---

## Features

* Accepts two integer inputs.
* Supports:

  * Addition (+)
  * Subtraction (–)
  * Multiplication (*)
  * Division (/)
* Uses Python’s `match` statement for clean operation selection.
* Handles invalid numeric input via `try–except`.

---

## How It Works

1. Prompts the user for two numbers (`a` and `b`).
2. Shows available operations.
3. Reads the operator.
4. Executes the matching arithmetic block:

   ```python
   match o:
       case "+":
           a + b
   ```

   (Full logic in the script.) 
5. Catches invalid input and prints an error message.

---

## Usage

### Run the script

```bash
python main.py
```

### Example Interaction

```
Enter the first number: 8
Enter the second number: 3
what kind of operation do you want to perform...
Enter Operation: *
The result is: 24
```

### Invalid Input Example

```
Enter the first number: hi
Enter a valid value of a and b
```

---

## Requirements

* Python 3.10+ (for `match-case`)

---

## Customization

You can extend the calculator by:

* Adding modulus (`%`)
* Adding exponent (`**`)
* Adding input validation loops
* Converting it into a GUI or CLI tool


