# Handbook for Best Coding Practices

## **Task Estimation**

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

### Three-point estimation

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


### Evaluate Importance and Priority

#### Prioritization Factors
*	[**Estimate for Your Resources,**](https://www.projectmanager.com/blog/5-tips-for-task-estimating) Different people will complete work  at different rates due to varying levels of skill, experience and confidence in their work. Work will progress faster if you assign the best people to work on tasks they know and understand. Save time on your project by using experienced resources and save on-the-job learning and mentoring for another time.
*	[**Cost of developing requirements,**](https://www.teamgantt.com/guide-to-project-management/how-to-estimate-projects) An essential factor to be considered by the product owner. Value and cost together indicate the Return on Investment (RoI) for the requirements.
*	Amount and **significance of functionality** that will be gained while working on the requirements.
*	Understanding the **level of risks** involved in introducing the new features.

#### Prioritization Techniques
Follow the _**relative weighting scheme**_ when trying to prioritise any task. It is a simple model where prioritization is done based on all the factors of the task. Major factors to be considered when weighing prioritization are:
*	The **value of the feature** and the negative impact that might be caused by the absence of the feature
*	Based on the collective judgment from product owner and the development team, a weight is assigned to each feature in the following way (a scoreboard from 1 to 9 is usually used)
     * Benefit from having the feature 
     * Loss for not having the feature 
     * Cost of producing the feature 
     * The risk incurred in producing the feature
     * The priority and rank are then determined by dividing the value score as below: 
     * (Benefit score + Penalty score) / (Cost score + Risk score)

#### Story Point Diagram
![Story Point Diagram](https://i0.wp.com/michaellant.com/wp-content/uploads/2010/05/StoryPriority.jpg)

## Coding Standards

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

## **Code Reviews**

### Code Review Workflow

To ensure we keep code review processing times low and make the most of our time both in development and as a team, it is important to follow a clear and efficient review structure, with excellent use of [git commands cheatsheet](https://gist.github.com/cferdinandi/ef665330286fd5d7127d).

 Communication is key, and collaborators should agree on regular review times and provide detailed feedback to ensure developers are complying with the coding standards. Ensure constructive, yet informative feedback that will be useful for further self-development of your colleagues.

#### Plan the review

When carrying out reviews refer to project tasks and the sub-tasks to identify the goals of your reviews. 
This will help you focus on the functionality that the code should deliver and ensure all expected standards are met. 

Know what you are looking for in the code - what should be included/used and what should be avoided

#### Review process

The goal of a review is to

* Ensure core functionality is delivered
* Identify as many bugs as possible before launching the code to production


 To keep reviews efficient, 
 
  they should be short and focus on smaller chunks of code rather than multiple files. This also applies to developers, who are expected to request reviews for smaller workloads. This will keep the reviewers attentive and achieve the best results.  

[These practices](https://www.perforce.com/blog/qac/9-best-practices-for-code-review) by Perforce, a software development company gives useful information for best code review processes. 

![Cricible team workflow](https://confluence.atlassian.com/crucible/files/298977486/299140917/2/1346046215515/Moderated+review.png)

[The Crucible Workflow](https://confluence.atlassian.com/crucible/defining-your-workflow-298977486.html)


[Microsoft Code Review Practices](https://www.slideshare.net/mgreiler/on-to-code-review-lessons-learned-at-microsoft)

![Code Review Processes Diagram](https://image.slidesharecdn.com/ontocodereviewlessonslearnedatmicrosoft-160921120651/95/on-to-code-review-lessons-learned-at-microsoft-7-638.jpg?cb=1474459748)

