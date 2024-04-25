```
# parent class
class Animal:
    def __init__(self, name, species):
        self.name = name
        self.species = species

    def eat(self):
        print(f"{self.name} is eating.")

# child class
class Cat(Animal):
    def __init__(self, name, species, color):
        super().__init__(name, species)
        self.color = color

    def purr(self):
        print(f"{self.name} is purring.")

# create objects of both classes
my_animal = Animal("Spot", "Dog")
my_cat = Cat("Whiskers", "Cat", "Black")

# use inherited method from Animal class
my_animal.eat()

# use methods specific to the Cat class
my_cat.eat()
my_cat.purr()
```