# a code on classes and objects in python
class Student:
  def __init__(self,name,age,section):
    self.name = name
    self.age = age
    self.section = section
  def show_details(self):
    print(self.name)
    print(self.age)
    print(self.section)

name = input("Name: ")
age = int(input("Age: ")
section = input("Section: ")

student = Student()
student.show_details()
  
