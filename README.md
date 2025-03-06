# Eren-Bedir
class Person:
    def __init__(self, name, age, student_class, department):
        self.name = name
        self.age = age
        self.student_class = student_class
        self.department = department

    def greet(self):
        print(f"Hello, my name is {self.name}, I am {self.age} years old.")
        print(f"I am in class {self.student_class}, studying {self.department}.")


eren = Person("Eren Bedir", 21, "01", "Computer Engineering (English)")

eren.greet()
