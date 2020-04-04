# Handbook for Best Coding Practices

## Coding Standards

### General Programming Practices

It is important to realise that your programming choices will reflect the quality
of your code and impact the productivity levels of your colleagues. Multidots - an agency specialising in web development for content publishers [coding standards guideline](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/) highlights the importance of code quality and coding standards for improving efficiency, minimising risk of project failure, reducing complexity and simplifying debugging processes.


#### Naming Conventions

* Use meaningful variable names throughout your code
* Maintain a consistent naming style for classes, functions and files
* Names should be explanatory of the object or the functionality of the methods that carry them. 

#### Formatting and Layout

To work together as a team, it is important that each developer effectively formats code,  tools and ensures code is well-segmented and easy to read. 

* Use auto-linters provided by the developement environemnt your team is using
* Use block separation to make files more readable

For all programming languages refer to general [guidelines](https://firefox-source-docs.mozilla.org/code-quality/coding-style/index.html) for coding and formatting styles recommended by the Firefox developement team.

#### Developement Style

##### Reusability

It is encouraged to become familiar with reusable coding patterns and apply them in all developement stages throughout projects. It will
* Reduce the amount of code we have to write
* Increase team efficiency
* Allow us to maximise resources and developement times

Refer to [Perforce's Code Reuse Strategy](https://www.perforce.com/blog/qac/challenge-code-reuse-and-how-reuse-code-effectively) for further recommendations on the best practices to apply. 

##### Component driven

Component driven development is one of the best patterns for code reusability. 

It ensures

* Consistency for both front end and back end
* Less code, which also means less debugging

Further information about component based developement patterns can be found on [Jack Pritchard's CDD Insights Article](https://whatjackhasmade.co.uk/component-driven-development). 


##### Refactoring

Overly complex structures and unnecessary code can be avoided by effective refactoring practices which should be done by all developers before code review. 

Consider

* Project structure that will shape the file structure choices
* Single task functions to simplify code and encourage code reusability
* Parameters and how to make best use without over-parametarising methods

Avoid

* Long classes - split into more classes
* Overly-nested and long functions
* Long parameter lists






