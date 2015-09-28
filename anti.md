# Anti project

### Restaurant Ordering

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

The language is for patrons of a restaurant to order food. This language would not be a good way to meet their needs because restaurant customers do not come to the same restaurant often enough to warrant learning a new language and new customers would be put-off by the learning curve.

Thinking on this idea further, it makes more sense for this DSL to be for non-programmers to build a customized ordering system for their customers.

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

This language would allow a restaurant to accept orders more quickly and accurately than the ambiguous language of English. People order in colloquial terms with many different terms meaning the same things. Waiters then have to translate the English into the kitchen's terms. This language would unify the back and front so that waiters no longer have to translate between the back and front.

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is inappropriate because each user will only use the language a few times in their lives. The other side of the coin is that the language will be so great that those who learn the language will only go to restaurants that also use the language.

### Why you?
_What excites you about this idea? How did you come up with it?_

I think we already use a vague, ill-defined langauge to order at restaurants. Waiters would be able to focus more on customers if they are less worried about getting orders incorrect.

### Domain
_Describe the project's domain in five words._

Ordering at restaurants through waiters.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

The user would type out their orders, instead of interacting with their waiters. The waiters would still come by and answer questions about the menu, but ultimately the customers will go through a computer to enter orders.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The program will interpret the order (the code) and then relay the appropriate messages to the kitchen. The program indicates when the order is successfully accepted or otherwise. The program could also keep track of the ingredients supply since it would be possible to build in recipes for each of the items.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be very easy to make orders with specific instructions. It should be possible but very difficult to request items that are not on the menu. It should be impossible or very difficult to communicate with the kitchen beyond orders.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are some order management systems or point-of-sale systems for restaurants. However, waiters are often still interpreting orders to the POS system. This DSL seeks to provide a way for restaurant owners to implement a custom interface for their customers so that waiters do not have to implement orders.

## The Project
This section examines whether the idea makes for a good CS 111 project.

The more I think about this project the more I think it would be a valid CS111 project. However, I think it would be too difficult for the time that we have to complete this project.

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

They should spend 60% making sure that their DSL is accessible to some restaurant owners, and 40% on the building of the codebase. I suggest high percentage for accessibility because restaurant owners are people who don't mind getting their hands dirty and learning a new domain. I think they would be a user base that would contribute to the language if they could.

### Scope
_How big an idea is this? How ambitious is this project?_

This is fairly large project, since it would require building a functional 'default' application on top of the language to ensure that non-programmers can at least use basic functionality. 

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is probably a good project, if there was demand for it. I believe restaurants don't like to add systems or change once they open unless there is new management or a refurbishment of the restaurant. So, the user base may be extremely slow to adopt the DSL.
