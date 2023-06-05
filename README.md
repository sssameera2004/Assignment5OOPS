METHOD 1:-
class Point:
    def __init__(self, x, y, z):
        self.x = x
        self.y = y
        self.z = z

    def sqSum(self):
        return (self.x)**2 + (self.y)**2 + (self.z)**2  


point1 = Point(1,3,5)
print(point1.sqSum())

METHOD2:-

class Point:
    def __init__(self, x, y, z):
        self.x = x
        self.y = y
        self.z = z
        
    def sqSum(self):
        a = self.x * self.x
        b = self.y * self.y
        c = self.z * self.z
        return(a + b + c)
point1 = Point(1,3,5)
print(point1.sqSum())

CHALLANGE 2:-
METHOD 1:-
class Calculator:

    def __init__(self, num1, num2):
        self.num1 = num1
        self.num2 = num2

    def add(self):
        return self.num1 + self.num2

    def subtract(self):
        return self.num2 - self.num1

    def divide(self):
        return self.num2 / self.num1

    def multiply(self):
        return self.num1 * self.num2

obj = Calculator(10, 94)
print(obj.add())
print(obj.subtract())
print(obj.multiply())
print(obj.divide())

METHOD 2:-
class cal():
    def __init__(self,num1,num2):
        self.num1=num1
        self.num2=num2
    def add(self):
        return self.num1+self.num2
    def sub(self):
        return self.num1-self.num2
    def mul(self):
        return self.num1*self.num2
    def div(self):
        return self.num1/self.num2
num1=float(input("Enter first number: "))
num2=float(input("Enter second number: "))
obj=cal(num1,num2)
print("Result: ",obj.add())
print("Result: ",obj.sub())
print("Result: ",obj.mul())
print("Result: ",(obj.div(),2))



