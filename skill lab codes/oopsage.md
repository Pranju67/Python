```
# Import the datetime module to work with dates
import datetime

# Define a class called Person
class Person:
    def __init__(self, name, birthdate):
        self.name = name
        self.birthdate = birthdate
    
    def calculate_age(self):
        today = datetime.date.today()
        age = today.year - self.birthdate
        return age

# Create an object of the Person class
person1 = Person("Alice", 1990)

# Call the calculate_age() method of the person1 object
age = person1.calculate_age()

# Print out the person's age
print(person1.name, "is", age, "years old.")
```
