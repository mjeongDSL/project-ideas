# No computer project


## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

Schematics serve designers, engineers and machinists who are trying to produce a specific part. The American National Standards Institute (ANSI) has a standardized system for describing a part using a schematic. This system involves a vocabulary and syntax to clearly relay only important information. If a part is not well described, the final part and the original design will differ and this discrepency generates inefficiencies in the production cycle.

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

Schematics meet the needs of engineers who need to model a specific part and the needs of machinists who need a precise set of rules to create a part. Without schematics, verbal or written descriptions would be lengthy while pictoral descriptions would be vague and misunderstood. 

### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

The DSL is appropriate because while it creates a barrier of information to part designs, it allows domain-users to quickly understand the specifics of a part. It uses many symbols and a strict syntax so that anyone familiar with the ANSI standard will be able to quickly understand every defined aspect of the part.

### Why you?
_What excites you about this idea? How did you come up with it?_

While schematics were not my idea, I believe the standards came about as a way of unifying various pictoral systems so that anyone could understand any schematic without having to know a specific regional system. This, and many other industrial standards, are ways that non-computer DSLs help people describe ideas that would be difficult with just a picture or words.

### Domain
_Describe the project's domain in five words._

Part design, specification, and manufacture.

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

In the past, users drafted schematics and read them on paper. Nowadays, it is similar but in a digital form. Schematics look like multiple views of the same part. Schematics are the right way to interact because the people who use schematics need the level of specificity that schematics provide.

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

While there is no program to run, the interpretation of the part from the machinist's perspective is to take the schematic and then decide the proper operations for producing that part. When a machinist makes a mistake, the part must be redone or adjusted from the original plan. When a designer makes a mistake, the mistake will not be realized until the part is produced (or when the machinist catches the error).

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Showing the details of a part is easy in this language. Any three-dimensional object can be fully described in this language. It is impossible to do describe _how_ a part should be made, or what machines to use.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Yes, there is an auxiliary component called a process router. The process router describes how a part should be made but not what the dimensions or materials should be. 

## The Project
This section examines whether the idea makes for a good CS 111 project.

This would be a really cool CS111 project (to create a better schematic system) but I do not think it would be well suited for this class.

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

90% of the time would have to go to the language aspect. This language has the only goal of describing, with specificity, a physical object. 

### Scope
_How big an idea is this? How ambitious is this project?_

Fairly large, the only way to improve upon what exists is to do extensive research into what designers, engineers, and machinists are struggling to do in the current language, and should not be.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This is a good idea for a project because the impact scope is large. An improved schematic system would be difficult, since it is such a large undertaking to improve a system that many consider easy to use.

