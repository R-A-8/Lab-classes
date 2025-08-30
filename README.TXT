Project: lab-classes
Authors: David J. Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 1.

The purpose of this project is to illustrate object interaction and to examine
some simple code. See chapters one and three of the book.

To use this project, create some Student objects, then create a LabClass object.
Add the students to the class using the "enrolStudent" method. Print a class
list.

22. A window opens with the result, which gives the student's name. At the top it says "Return the full name of this student."
24. A window opens with the result, which gives the number of students currently enrolled in the class (which is currently 0).
29. Instructor: "Mr.Instructor"; Class: "A-123"; Time:Friday, 8am".
31. What are the types of the following values?
   0 = int
   “hello” = string
   101 = int
   -1 = int
   true = boolean
   “33” = string
   3.1415 = float/double
32. I would add a "private String name;" at the top of the circle's code.
33. I wrote "private String send;" at the top of the student class code
    I wrote this code based on the studentId code and the one I did in question 34:
/**
     * Send something
     */
    public Student( String aMessage)
    {
        send = aMessage;
         
    }
    Since I didn't need a return message, I didn't write one.

34. I wrote "private int average" to the top of the student class code.
    To make the method appear, I wrote this code(Based on the code for the studentId, studentName, etc.):
    /**
     * Give an average
     */
    public Student(int firstNumber, int secondNumber)
    {
        average = firstNumber;
        average = secondNumber; 
    } 
   To make it give a return, I wrote this code, also based on the return for the studentName:
    /**
     * Return the average of the numbers.
     */
    public int getAverage()
    {
        return average;
    }
  
35. It's an object and its class would be books or textbooks. My textbook is a specific example from the category(class) that is textbooks/books.
36. I think an object can have multiple classes. For example, if I take a specific airplane(like a blue private jet), its class could be "airplanes" in general, but it could also be "modes of transportation".

For both questions 33 and 34, I'm not sure if I created a "method", because the "method" would appear when I right-clicked on the class, not on the object. I think it might be because I wrote the private int and private string at the top of the code, but I'm not sure how to fix it.
