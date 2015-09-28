# Free project 1

### Shared Spaces

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

This project serves a group of people who share a set of spaces and need to use the spaces at various times. Examples include kitchenes, lab spaces, and study room. This language would ideally be good for any user to reserve a space or designate the space as 'occupied'.

Or - the DSL may be for people who want to build applications that groups of people would want.

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

Shared spaces are often managed by some form of scheduler but the interfaces we use for them are nonintuitive and rather poor. 

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is appropriate for our users because an interface to relate locations, time, and people is difficult to express in a general programming language.
I think SQL would be a good candidate for solving this problem, but it would be less natural than one designed just for this purpose.

### Why you?
_What excites you about this idea? How did you come up with it?_

I thought of this because one problem I face is going out to buildings only to find out that all of the spaces are already taken.

### Domain
_Describe the project's domain in five words._

Occupation checking and building layouts

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

A user would put together a building layout that could then be used to indicate which rooms are occupied. The program could either be a drag and drop interface or a 2D drawing tool. I believe that it is easier to place things spatially since that is how we experience buildings.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When a program runs, it will produce a tool or application that has the building layout and the ability to indicate that rooms are occupied along with other information.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be very easy to generate a building layout to match one in real life using a map. It should be possible to try and construct one from scratch but tedious and difficult. It is probably impossible to run "Hello World".

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There are spreadsheet-style ways to do this, but they are unintuitive and clunky.

## The Project
This section examines whether the idea makes for a good CS 111 project.

I think the most difficult part will be implmenting the graphical language. A type version of this language should be easy... perhaps this is like the glass-blowing project where the graphical will output text that is the actual program.

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I would say it is 60-40 just because the graphical interpretation is going to be difficult. The language aspects could be applied to the in-between text language which will move more of the time would go to language aspects.

### Scope
_How big an idea is this? How ambitious is this project?_

It really comes down to whether the in-between text language is used or the graphical language that I envision people using. The text-only language seems feasible in the time we have in class.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is a good idea for a project because it has built-in project scale control (the implementor can decide later if they want to do the graphical interface).
This may be a poor project if the implmentor does not think this project is an interesting problem to solve. It very well may be that this problem is too small to require a DSL.
