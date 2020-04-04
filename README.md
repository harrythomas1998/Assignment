# Handbook for Best Coding Practices

### **Task Estimation**

### **Work Breakdown Structures**

**WBS** (Work Breakdown Structure) describes what tasks need to be completed in a project. However, it does not include factors such as timelines or resources. The goal of the WBS is to focus the team on what has to be done.

When you're breaking down what has to be done it is important to remove verbs from each level. You are not describing the tasks necessary to complete what has to be done, you are just describing them. Find out more [here](https://www.guru99.com/an-expert-view-on-test-estimation.html )


Some of the benefits of WBS include:
*   **Project Schedule:** Once you define all the tasks required to complete the project, as well as their hierarchical relationships, it will be much easier to assign resources and set deadlines.
*   **Accountability:** Since all elements in a WBS are mutually exclusive, it helps create accountability. A team assigned to a single work package is solely accountable for its completion. This reduces overlaps in responsibility.
*   **Commitment:** The WBS gives teams a very high-level overview of their responsibilities. Since each team is responsible for a specific component at a time, it helps make them more committed to completing their assigned tasks.
*   **Reduces ambiguities:** WBS involves the project manager, team members and relevant stakeholders. This encourages dialog and so everyone knows exactly what they have to do. This way there is ambiguity.

If you want to read further click [here](https://www.workamajig.com/blog/guide-to-work-breakdown-structures-wbs?hs_amp=true)

![WBS Diagram](bdt.png)

## Three-point estimation

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

### Coding Standards

It is important to realise that your programming choices will reflect the quality
of your code and impact the productivity levels of your colleagues. Multidots - an agency specialising in web development for content publishers [coding standards guideline](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/) highlights the importance of code quality and coding standards for improving efficiency, minimising risk of project failure, reducing complexity and simplifying debugging processes.

### General Programming Practices

#### Naming Conventions

* Use meaningful variable names throughout your code
* Maintain a consistent naming style for classes, functions and files
* Names should be explanatory of the object or the functionality of the methods that carry them. 

#### Formatting and Layout

To work together as a team, it is important that each developer effectively formats code,  tools and ensures code is well-segmented and easy to read. 

* Use auto-lint provided by the development environment your team is using
* Use block separation to make files more readable

For all programming languages refer to general [guidelines](https://firefox-source-docs.mozilla.org/code-quality/coding-style/index.html) for coding and formatting styles recommended by the Firefox development team.

### Developement Style

**Reusability**

It is encouraged to become familiar with reusable coding patterns and apply them in all development stages throughout projects. It will
* Reduce the amount of code we have to write
* Increase in team efficiency
* Allow us to maximise resources and development times

Refer to [Perforce's Code Reuse Strategy](https://www.perforce.com/blog/qac/challenge-code-reuse-and-how-reuse-code-effectively) for further recommendations on the best practices to apply. 

**Component driven**

Component driven development is one of the best patterns for code reusability. 

It ensures

* Consistency for both front end and back end
* Less code, which also means less debugging

Further information about component-based development patterns can be found on [Jack Pritchard's CDD Insights Article](https://whatjackhasmade.co.uk/component-driven-development). 


**Refactoring**

Overly complex structures and unnecessary code can be avoided by effective refactoring practices which should be done by all developers before code review. 

*Consider*

* Project structure that will shape the file structure choices
* Single task functions to simplify code and encourage code reusability
* Parameters and how to make the best use without over-parameterising methods

*Avoid*

* Long classes - split into more classes
* Overly-nested and long functions
* Long parameter lists

