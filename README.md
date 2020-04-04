# Three-point estimation

After splitting the tasks into sub tasks, you now must ask the team or person responsible for each sub task to provide a three-point estimation.

A three point-task estimation is the simple practice of estimating the worse, best and most realistic outcomes of tasks regarding time consumption.

* **B** = Best case estimate, the case where everything works perfect
* **W** = worse case estimate, the case where everything seems to go wrong
* **M** = Most realistic estimate, the most realistic estimate based on experience.


Now after calculating these three values we will put them into the formula below:

**Task Duration** == *(B + W +(4 * M)) / 6*

__Let’s show an example:__


**(** *All Numbers should be rounded to the nearest integer* **)** 

![Alt Text](https://kunalbhandari.files.wordpress.com/2014/01/beta-distrfibution.png)

Use three-point estimation for each task in your schedule, it will ensure that your task estimation is completed to the highest of standards.


[Read more here for some more detailed information](https://www.merixstudio.com/blog/three-point-estimation-software-development/ )

# Commenting and Documentation Standards
It is very important to add comments to your code, although it seems like a straightforward task comment **doesn’t** mean add a bunch of comments and random documentation anywhere while coding.

Commenting involves mentioning the right things to help yourself and your colleagues’ when coding. 

Firstly, we should describe **what** we are creating, **why** we are creating it and **what** our main **goal** is that we would like to achieve here. 

If there are any changes being carried out these should be logged by creating a changelog .md file and attach it to your component. *Eg:*

   ![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/changelog.png)


It is also good practice and we recommend you add **@See**, referencing the class, which will further help you and your colleagues’ to easily navigate to that class definition with just one click



![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/fn-referencing.png)

Adding **@TODOs** is also very important as it is common in coding for people to complete the general function of something and have plans to add additional improvements although not enough time at present and then come the end of the project, they have completely forgotten to add those improvements. 

**@TODOs** will help ensure you do not forget again. It is quite simple to implement, just mention what needs to be improved above the code, *example:*


![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/todo-example.png)


Lastly a *“Docblock”* is a special code comment; it offers an explanation for the porpose of the code such as return values, arguments and exceptions for a block of code.


A *“Docblock”* is a special code comment that offers an explanation of the purpose, arguments, return values, and throw exceptions for a block of code.

![Alt Text](https://lhuria94.github.io/assets/img/2017-07-26-coding-standards-that-matter/docblock-example.png)
