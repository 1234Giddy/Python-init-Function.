# Python-init-Function.
The 'init' Function in python is a special method that is executed automatically when an object is created from a class.It is commonly used to initialize the attributes of an object.
Class person:
def__init__(self,name,age):
self.name = name
self.age = age
def__introduce(self):
print(f"Hello,my name is{self.name}and I am {self.age}years old.")
#Creating objects from trhe person class
person 1 = person("Alice",28)
person 2 = person("Bob",32)
#calling the introduce method on each person object
person1.Introduce()
person2.Introduce()

#Output
Hello, my name is Alice and I am 28 years old.
Hello, my name is Bob and I am 32 years old.
