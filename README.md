# C# QUIZ

*IMPORTANT*: Do not use Visual Studio to answer the coding questions.

- What is an interface?

- What is polymorphism?  Describe an example?

- What is the difference between a class and an object?

- What are the four pillars of OOP?

- What is an abstract class?

- What is the difference between an abstract class and an interface?

- TRUE or FALSE: an abstract class can be instantiated?

- TRUE or FALSE: an abstract class can have a constructor?

- Is a string a value type or a reference type?  

- What is the package management system used in Visual Studio?

- After the following method executes and is completed what will be the value of the Name property of the Employee parameter object?

````

public static void UpdateEmployee(Employee employee)
{
    employee.Name = "Harry Potter";
}

````

- Will the Employee parameter object in the following method become null after the method executes and is completed?  Why or why not?

````

public static void NullEmployee(Employee employee)
{
    employee = null;
}

````

- In the *Employee.cs* file in this folder, create a class named Employee with the properties to hold the following info:
  - first name
  - last name
  - hire date
  - email

- In the *Program.cs* file in this folder, create an Employee object from the class defined above.  Give this object the following information:
  - first name: Harry
  - last name: Potter
  - hire date: 1/1/2015
  - email: harry.potter@gmail.com

- Take the Employee class created from the previous example and override the ToString() method to return a string representation of the properties.  Use string interpolation.

- Create a static method on the Employee class named CloneEmployee that takes an Employee object as a parameter and returns a deep copy.  Demonstrate using this method in the *Program.cs* file in this folder.

- Create a method on the Employee class that returns the number of days an employee has been employed.  Demonstrate using this method in the *Program.cs* file in this folder.

- In the *Program.cs* file in this folder, create a list of Employee objects.  Add three Employee objects to the list.  Iterate over the list of objects and call each object's ToString() method on each iteration.
