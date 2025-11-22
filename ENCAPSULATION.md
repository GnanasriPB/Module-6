# Exp.No:6c
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```
class Student:
    def __init__(self, name, age):
        self.__name = name    # private member
        self.__age = age      # private member

    # Getter for age
    def get_age(self):
        return self.__age

    # Setter for age
    def set_age(self, age):
        self.__age = age

    # Display student info
    def display(self):
        print(f"Name: {self.__name} {self.__age}")


# Create object
student = Student("Jessa", 14)
student.display()

# Update age using setter
student.set_age(16)
student.display()


```

### OUTPUT
<img width="405" height="180" alt="image" src="https://github.com/user-attachments/assets/a2b424e4-1637-412b-a70f-4eb113bad9fe" />


### RESULT
Thus,Python program to create a class Student with the private members name and age, and add getter and setter methods to initialize and modify the age variable was implemented successfully.


