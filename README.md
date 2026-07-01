# Python-Basics
skip this stuff




# Python Basics

## 1. Hello World

**"Hello, World!"** is the first program almost everyone writes when learning a new programming language.

Its only purpose is to check that your programming environment works and to show how to display text.

### Example

```python
print("Hello, World!")
```

### Output

```text
Hello, World!
```

---

## 2. Python Indentation

**Indentation** means adding spaces (usually **4 spaces**) at the beginning of a line. In Python, indentation tells the computer which lines belong together.

Think of it like an outline in a document:

- Main point
  - Sub-point
  - Another sub-point

### Example

```python
if 5 > 3:
    print("5 is greater than 3")
```

Without the indentation, Python will give an error.

---

## 3. Python Variable

A **variable** is like a **labeled box** that stores information so you can use it later.

For example, instead of remembering the number `25`, you can store it in a variable named `age`.

### Example

```python
age = 25
name = "Alice"

print(age)
print(name)
```

### Explanation

- `age` stores the number `25`.
- `name` stores the text `"Alice"`.

You can change a variable's value whenever you want:

```python
age = 26
```

Now `age` holds `26` instead of `25`.