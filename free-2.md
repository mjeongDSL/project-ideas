# Free project 2

### Legislative Language

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.

This language is for policy making and legislators. The way that laws are written today includes vague and ambiguous language with many different ways to say the same thing. Also, intentions of laws are lost with time because they are not worded correctly. This language seeks to codify laws perhaps even verifying with logic that the law does not conflict with other laws.

### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_

Laws often use different words to describe the same thing (retail store? clothing outlet? non-durable consumer goods store?) Laws at different levels, state/county/federal, are written in different ways because they need to satisfy different criteria to pass. This langauge would help legislators, or more likely interns, find relevant laws when they are drafting legislation. Currently, they are querying for the list of terms that they think are similar to what they are looking for. With a computer-based language, users would be able to quickly find relevant laws.


### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is appropriate because the current language is English, which has a large number of colloquially-defined and ill-defined terms that can cause confusion in the future. Also, the DSL should seek to reduce the length of the legislations. It is hard to tell from the verbose language used today what is and isn't being changed. 


### Why you?
_What excites you about this idea? How did you come up with it?_

This idea excites me because laws affect our every day lives and it takes many people to go through even one bill to disseminate how it translates to the everyday person.

(and now that I think about it this could apply to patents and other legal texts)

### Domain
_Describe the project's domain in five words._

Law making and law validating

### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 

When a legislator wants to write a bill, they would enter in statements on lines. Each line would be like a logic predicate or rule. The program would ideally look closer to natural language with some odd syntax. This is the right way to interact because legislators are used to large texts and this is just to make the texts more bearable. 

### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When a program runs, each rule will be converted into a set of logic statements and tested against the current set of rules. The program will find conflicts and ask the user which one they would like to keep. It will then output the results of the rules comparison.

### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be very easy to write out laws that alter laws that already exist. It should also be easy to build new laws and define new terms. It should be possible but difficult to change many laws at one time since it will be hard to build self-consistent laws as they grow in size. It will probably be difficult or impossible to write in loops since looping control flow is difficult doesn't match the needs of legislature.

### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I don't believe there is another DSL other than the spoken/written language that the laws are written in. 


## The Project
This section examines whether the idea makes for a good CS 111 project.

I don't think this would be a good CS111 project because building this language would require a fair bit of research into laws and how they are created.
However, if there was a way to do this project with only a fair amount of research, then I think it would be an interesting project for this class.

### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Most of the time would be spent on the language aspects since the focus of the langauge is to serve legislators when they build laws. 

### Scope
_How big an idea is this? How ambitious is this project?_

I think this is a fairly big idea since there are a lot of terms, and laws cover multiple domains that each have their own jargon and syntax.

### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_

This would be a good idea for those who are interested in legislation. If the scope of this project was reduced to laws that pertain to a certain field, then this would probably be a good project. It might not be a good idea project because it may be simple to implement a language that can then be expanded to fit the needs of legislators.