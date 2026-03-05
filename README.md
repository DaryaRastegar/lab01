# lab01

Exercise One: Create My First Java Program using IntelliJ

Questions:
What does this class do?
This class prints "Hello World" to the console.

Where are the classes generated and stored by IntelliJ?
out/
└─ production/
└─ lab01/
└─ MyFirstProgram.class

out\production\lab01\MyFirstProgram.class

Where do you see the messages after running the program in IntelliJ?
Run Console (Run Window)

What are the different ways of running this class in IntelliJ?
1. Run button

    - Click the green ▶ button at the top.

2. Right-click the file

    - Right-click MyFirstProgram.java
    - Click Run 'MyFirstProgram.main()'

3. Keyboard shortcut

    - Press Ctrl + Shift + F10
    - Press Ctrl + F5

4. Run from the gutter

    - Click the green triangle icon next to the main method.

What are some of the useful shortcut keys you found in IntelliJ?
| Shortcut       | Action            | Example / Notes                                |
| -------------- | ----------------- | ---------------------------------------------- |
| `Ctrl + Hover` | Quick Info        | Shows type/signature/docs of a class or method |
| `Alt + Enter`  | Quick Fix         | Generate code, fix issues, implement methods   |
| `Esc`          | Close popup       | Closes docs, tool windows, or console          |
| `Ctrl + E`     | Recent Files      | Quickly open recently used files               |
| `Ctrl + B`     | Go to Declaration | Jump to class, method, or variable definition  |



Exercise Two: Add a New Class to an Existing Project

Questions:

What happened to MySecondProgram class after you have fixed the error?
    It is now in the correct package folder, and IntelliJ can compile it.

    The class is recognized as ictgradschool.industry.introtojava.mysecondprogram.MySecondProgram.

What are packages used for?
    Packages organize classes into folders/modules.
    
    Avoid naming conflicts.
    
    Help manage large projects by grouping related classes.

Questions:
What does the keyword import do in Java?
It allows you to use classes from other packages without writing the full package path every time.

How would you resolve the compilation error without using the import keyword?
By writing the full package name of the class every time you use it:
    ictgradschool.industry.introtojava.mysecondprogram.MySecondProgram p =
        new ictgradschool.industry.introtojava.mysecondprogram.MySecondProgram();



Exercise Three: Evaluation of Expressions

What output do you think would be produced by each of the following code fragments? (You can work on this exercise on paper)

System.out.println((int)2.9 * 4.5);
9.0
System.out.println(Math.max(5,60) % Math.min(12,7));
4
System.out.println(0.2 * 3 / 2 + 3 / 2 * 3.2);
3.5

Exercise Four: The Basics - Variables, Debugging, Math, and Casting
