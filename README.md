# Commenting and Documentation Standards
It is very important to add comments to your code, although it seems like a straightforward task comment **doesn’t** mean add a bunch of comments and random documentation anywhere while coding.

Commenting involves mentioning the right things to help yourself and your colleagues when coding. 

Firstly, we should describe **what** we are creating, **why** we are creating it and **what** our main **goal** is that we would like to achieve here. 

If there are any changes being carried out these should be logged by creating a changelog .md file and attach it to your component. *Eg:*

   ![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/changelog.png)


It is also good practice and we recommend you add **@See**, referencing the class, which will further help you and your colleagues’ to easily navigate to that class definition with just one click



![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/fn-referencing.png)

Adding **@TODOs** is also very important as it is common in coding for people to complete the general function of something and have plans to add additional improvements although not enough time at present and then come the end of the project, they have completely forgotten to add those improvements. 

**@TODOs** will help ensure you do not forget again. It is quite simple to implement, just mention what needs to be improved above the code, *example:*


![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/todo-example.png)


Lastly a *“Docblock”* is a special code comment; it offers an explanation for the porpose of the code such as return values, arguments and exceptions for a block of code.


![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/docblock-example.png)
