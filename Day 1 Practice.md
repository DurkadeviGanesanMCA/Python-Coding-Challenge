## Case Study – Library Fine Calculator Instructions:

- Create variables:
- student_name
- book_name
- days_late
- fine_per_day
- Use input() function to get details from the user.
- Use type casting:
- int() for days_late
- float() for fine_per_day

### Calculate:

- total_fine = days_late * fine_per_day
- Display all details using:
- print()
- f-string
- Display datatype of important variables using:

- ## Library Fine Calculator

### Taking input from user
- student_name = input("Enter Student Name: ")
- book_name = input("Enter Book Name: ")
- days_late = int(input("Enter Number of Late Days: "))
- fine_per_day = float(input("Enter Fine Per Day: "))

### Fine Calculation
total_fine = days_late * fine_per_day

### Library Fine Calculator

```python
# Taking input from user

student_name = input("Enter Student Name: ")
book_name = input("Enter Book Name: ")
days_late = int(input("Enter Number of Late Days: "))
fine_per_day = float(input("Enter Fine Per Day: "))

# Fine Calculation
total_fine = days_late * fine_per_day

# Displaying Details
print("\n----- Library Fine Details -----")

print(f"Student Name   : {student_name}")
print(f"Book Name      : {book_name}")
print(f"Days Late      : {days_late}")
print(f"Fine Per Day   : {fine_per_day}")
print(f"Total Fine     : {total_fine}")

# Displaying Datatypes
print("\n----- Datatypes -----")

print(type(student_name))
print(type(days_late))
print(type(fine_per_day))
```

## Description
This Python program:
- Takes student and book details as input
- Calculates the total library fine
- Displays fine details
- Shows the datatype of variables


### Output

```text
Enter Student Name: Ravi
Enter Book Name: Data Science
Enter Number of Late Days: 15
Enter Fine Per Day: 10

----- Library Fine Details -----
Student Name   : Ravi
Book Name      : Data Science
Days Late      : 15
Fine Per Day   : 10.0
Total Fine     : 150.0

----- Datatypes -----
<class 'str'>
<class 'int'>
<class 'float'>
```
