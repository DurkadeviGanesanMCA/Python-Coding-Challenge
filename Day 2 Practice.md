### Python Basic Programs

### 1. Read Two Numbers and Perform All Arithmetic Operations

```python
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("\n******** Arithmetic Operations ********")
print(f"Addition       : {num1 + num2}")
print(f"Subtraction    : {num1 - num2}")
print(f"Multiplication : {num1 * num2}")
print(f"Division       : {num1 / num2}")
print(f"Modulus        : {num1 % num2}")
print(f"Floor Division : {num1 // num2}")
print(f"Power          : {num1 ** num2}")
```

---

### 2. Check the Data Type of the Value Entered

```python
value = input("\nEnter a value: ")

print("Data Type:", type(value))
```

---

### 3. Find the Length of a String and Count the Number of Words

```python
text = input("\nEnter a string: ")

length = len(text)
word_count = len(text.split())

print(f"Length of string : {length}")
print(f"Number of words  : {word_count}")
```

---

### 4. Count Words in a Sentence

```python
sentence = input("\nEnter a sentence: ")

count = len(sentence.split())

print("Word Count:", count)
```

---

### 5. Reverse Each Word in a Sentence

```python
sentence = input("\nEnter a sentence: ")

words = sentence.split()

reversed_words = [word[::-1] for word in words]

result = " ".join(reversed_words)

print("Reversed Words:", result)
```

---

### 6. Check Whether a Character is a Vowel or Consonant

```python
ch = input("\nEnter a character: ").lower()

if ch in "aeiou":
    print("Vowel")
else:
    print("Consonant")
```

---

### 7. Check if a String is a Palindrome

```python
text = input("\nEnter a string: ")

if text == text[::-1]:
    print("Palindrome")
else:
    print("Not a palindrome")
```
