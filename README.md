# PPL-ass-file
Complete list of PPL **ass**ignment file

You have to shove these in your assignment file, it can be pdf or docx

| **Assignment** | **Date** |
| :--- | :---: |
| <a href="#inheritance">Inheritance</a> | 09/08/21 |
| <a href="#overloading-and-overriding"> Overloading and Overriding </a> | 16/08/21 |
| <a href="#abstract-class"> Abstract Class </a> | 30/08/21 |
| <a href="#user-defined-package"> User-defined Package </a> | 07/09/21 |
| <a href="#access-modifier"> Access Modifier </a> | 09/09/21 |
| <a href="#array"> Array </a> | 17/09/21 |
| <a href="#string"> String </a> | 23/09/21 |
  
<h2 id="inheritance">Inheritance</h2>

<details>
  <summary> 1.  What will be the oputput of following JAVA program </summary>

```java
class Base {
    public void show() {
        System.out.println("Base::show() called");
    }
}

class Derived extends Base {
    public void show() {
      System.out.println("Derived::show() called");
    }
}

public class Main {
    public static void main(String[] args) {
      Base b = new Derived();;
      b.show();
    }
}
```
</details>

<details>
  <summary> 2.  Write a program that inherits a class named Alien ... </summary>

  Write a program that inherits a class named Alien and Pirates from a parent class Human. The human class has its own features like the Human can sleep, walk, talk,etc. the Alien and Pirates class inheriting these functionalities as well as they have their characteristics.
</details>

<details>
  <summary> 3.  Which of the following is true about inheritance in Java? </summary>
     
  - Private methods are final.
  - Protected members are accessible within a package <br> and inherited classes outside the package.
  - Protected methods are final.
  - We cannot override private methods.
</details>
  
<h2 id="overloading-and-overriding"> Overloading and Overriding</h2>

Any **TEN** questions from these [40 questions](https://javaconceptoftheday.com/java-practice-questions-on-method-overloading-and-overriding/)

<h2 id="abstract-class"> Abstract Class </h2>
<details>
  <summary> 1.  Create an abstract class 'Parent' with a method 'message'... </summary>
  
Create an abstract class 'Parent' with a method 'message'. It has two subclasses each having a method with the same name 'message' that prints "This is first subclass" and "This is second subclass" respectively. Call the methods 'message' by creating an object for each subclass.
</details>

<details>
  <summary> 2.  Create an abstract class 'Bank' with an abstract method 'getBalance'... </summary>
Create an abstract class 'Bank' with an abstract method 'getBalance'. $100, $150 and $200 are deposited in banks A, B and C respectively. 'BankA', 'BankB' and 'BankC' are subclasses of class 'Bank', each having a method named 'getBalance'. Call this method by creating an object of each of the three classes.
</details>

<details>
  <summary> 3.  We have to calculate the percentage of marks obtained in three subjects... </summary>
We have to calculate the percentage of marks obtained in three subjects (each out of 100) by student A and in four subjects (each out of 100) by student B.
  
Create an abstract class 'Marks' with an abstract method 'getPercentage'. It is inherited by two other classes 'A' and 'B' each having a method with the same name which returns the percentage of the students.
The constructor of student A takes the marks in three subjects as its parameters and the marks in four subjects as its parameters for student B.
  
Create an object for eac of the two classes and print the percentage of marks for both the students.
</details>

<details>
  <summary> 4.  Create an abstract class 'Animals' with two abstract methods 'cats' and 'dogs'... </summary>

Create an abstract class 'Animals' with two abstract methods 'cats' and 'dogs'. Now create a class 'Cats' with a method 'cats' which prints "Cats meow" and a class 'Dogs' with a method 'dogs' which prints "Dogs bark", both inheriting the class 'Animals'. Now create an object for each of the subclasses and call their respective methods.
</details>

<h2 id="user-defined-package"> User-defined Package </h2>

1. Make a `package`, with a method to add two numbers. Import it to use it in another class.
2. Any **5** questions from [here](https://www.examtray.com/java-questions/java-package-interview-mcq-questions-and-answers)

<h2 id="access-modifier"> Access Modifier </h2>

1. Make a `protected` access method to calculate factorial in a package.
2. What is copy constructor? what are advantages of copy constructor? Implement it.
3. What is Private constructor? what are advantages of copy constructor? Implement it.

<h2 id="array"> Array </h2>

Any **15** questions from [Related Topics](https://www.javatpoint.com/array-in-java) at bottom.

<h2 id="string"> String </h2>

Any **10** <a href="https://www.javatpoint.com/java-string"> String methods </a> implementation in one or more program(s).
