```
class triangle:
    def __init__(self, a,b,c):
        self.a = a
        self.b = b
        self.c = c
    
    def perimeter(self):
        p = self.a+self.b+self.c
        return p

# Create an object of the Person class
x = triangle(3,4,5)

# Call the calculate_age() method of the person1 object
result = x.perimeter()




# Print out the person's age
print("perimeter of traingle is ", result)
```