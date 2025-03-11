# Eren-Bedir
class Person:
    def __init__(self, name, age, student_class):
        self.name = name
        self.age = age
        self.student_class = student_class

    def greet(self):
        print(f"Hello, my name is {self.name}, I am {self.age} years old.")
        print(f"I am in class {self.student_class}.")


eren_bedir = Person("Eren Bedir", 21, "01")


eren_bedir.greet()
