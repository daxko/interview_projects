# Daxko Interview Project

The project is a simple ordering system that allows someone to order a specified quantity of items from a list.

The purpose of this exercise is to evaluate a general knowlege of C#, ASP.NET MVC, JavaScript, and good coding practices.  On interview day, you will be presenting your project to a team of engineers.

**NOTE:** we want to respect your time and do not expect you to go all out and spend many hours perfecting this project. Find the right balance of actually performing a refactor for the higher priority parts of the code vs. being prepared to discuss the other parts that you would want to refactor given more time.

## Scenario

You are tasked with adding some new functionality to a fake legacy application. This fake application was poorly coded intentionally (for the sake of this interview project). It violates many of the SOLID principles and has a lot of issues with maintainability. Feel free to refactor the code however you see fit as you add the new functionality and be prepared to discuss your changes with us.

### User story: As someone who orders multiple products at the same time, I would like to be able to type in the quantity for each item then press the "Add to Order" button once and have the contents of my cart be refreshed without doing a full page reload (read: AJAX).

![](new_order_screen.png)

Come prepared to have a friendly and fun conversation with other developers about what you did to the product and why you chose to do it that way.

## Technical notes

*   The OrderRepository is meant to be an abstraction over the database layer. There is no reason to setup a database and actually save data. We don't expect you to do that in this exercise unless you particularly want to show off something around data storage.
*   There is no need to add functionality to make this project complete other than the user story you are tasked (for example, deleting items you add to your order). However, feel free to refactor anything that is within the project already to get it to what you would consider a "clean" state (NOTE: this isn't a requirement, but at least come prepared to discuss parts of the system you would have like to have refactored but was not a top priority).
*   Feel free to use any tools or libraries that you see fit.
*   Don't worry about supporting IE.
*   Bonus points if you use React for satisfying the AJAX requirement in the user story (this is our preferred UI library for new features). Feel free to use another UI library if do not know React but know Vue, Angular, etc better.


## Interview Day

* You will be presenting from your computer and sharing your screen over Zoom.
* You will be given about 30 minutes to discuss your project with a team of engineers.  Please come prepared to walk through your code, give us a demo of the code, discuss your approach and what other changes you would have made to the project if you had more time.



## Something not clear?

Feel free to contact [ctucker@daxko.com](mailto:ctucker@daxko.com?subject=Daxko%20Interview%20Project%20Question) if you have any questions about this project.
