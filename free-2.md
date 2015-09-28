# Free project 2
A language for dictating problem sets and receiving problem set solutions via latex.

## The user and a language
This section describes who the project would serve and why a language might be a
good way to meet their needs.


### What's the need?
_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help 
them?_
The need is for professors and students to be able to communicate problem sets and solutions more easily and through technology. I would be helping both teachers and students. Right now, for a student that does their problem sets in latex, someone needs to pick up the problem set in hard copy or print it out, then write it up in latex, and then print out the typesetted version to hadn it in. With my idea this same student would be able to receive the problem set as latex, do it in latex, and then submit it in latex (potentially with a wrapper around latex to make it a bit easier?)


### Why a language?
_Why is a DSL appropriate for your user(s)? How does it address the need?_
A DSL is appropriate because it would work with latex and could be written by both teachers and students to communicate uniformly. It addresses the need by removing the need to print!


### Why you?
_What excites you about this idea? How did you come up with it?_
I hate printing my math homework every day. I came up with it when I was doing no-computer in conjunction with the ideas from past years.


### Domain
_Describe the project's domain in five words._
Students and professors of quantitatives.


### Interface (syntax)
_How might the user interact with the language? What does programming look 
like? Why is this the right way to interact with the problem domain?_ 
A user would interact with this language by either:
a) providing problems, due dates, hints, and resources through the language in order to dictate a problem set to students
or
b) providing solutions in wrapped-up latex.
Programming looks different depending on which interface is being used but im imagining it looking pretty much like english but with keywords and stuff.
This is the right way to interact with the problem domain because problem sets change every time but there is generally a fixed way of setting them up. This means that a language is probably a good solution because we can dictate the syntax without limiting the content.


### Operation (semantics)
_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_
When a program runs either students would be able to access a problem set or a grader would be able to have access to students solutions. A program interacts with the user through a log similar to latex I think and error messages are communicated through that. Errors might occur if keywords are omitted or something, and also students could be given feedback on wrong solutions through the language as well.


### Expressiveness
_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_
It should be easy to assign psets, do psets, and grade psets, but impossible to do pretty much anything else. I suppose you could use it for non-quantitative assignments but it wouldnt be as functional.


### Related work
_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well 
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_
I looked around on google and cant find anything similar. I think that there might not be a DSL here because it is a relatively small domain and not everyone does math homework using latex.


## The Project
This section examines whether the idea makes for a good CS 111 project.


### Suitability
_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_
I think that it would be largely language design because a programmer would have to decide exactly what programs would look like, how they would be implemented and design both sides. But there would be a significant amount of systems programming to execute the communication between the two sides.


### Scope
_How big an idea is this? How ambitious is this project?_
I think this is a pretty big idea because of the multiple interfaces. I think its pretty ambitious but achievable.


### Benefits and drawbacks
_Why might this be a good idea for a project? Why might this not be a good idea 
project?_
This might be a good idea because I think that, especially at schools like mudd, it would be solving a very real problem and save paper! It might not be a good idea for a project because it might have more application building aspects and less language design stuff (maybe).
