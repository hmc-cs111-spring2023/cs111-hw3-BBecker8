# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

A DSL built to help poker players keep track of data at the poker table in real time. This dsl would help reinvent poker analyis for poker players. Right now player rely on their memory to write down what happened on any given hand durring game. They may wait till break to add a particular interesting hand into thier notes, or keep a mental note of how a player plays durring a hand, or even wait many hours until the event has stopped or they got busted out to write down things that happened at the table all off of memory. Instead image a DSL for poker players that allows them to keep track of poker related events at the poker table, and even provide them with statistics so they can make their best move.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

This DSL is aproprite for poker player so that they can input events that happen at the table in real time and allows for more accurate data represention then when they add it to thier notes after the fact. Additionally I keeps all of a players notes, poker data, and suggestions all in one place. The need is for real time note / obervation taking while sitting at the poker table. It would allow the players to take accurate observation in real time but also not take away from their attention to the table. 

### Why you?

_What excites you about this idea? How did you come up with it?_

This idea exites me and other poker players because it combines this notion of a ststitical game with more accurate stastitics as well as provides the player the ability to keep track of past hands without having to recall memory from the last 4 hours of play. I was able to come up with this idea after interveiwing my dad who is a sofware engineer and a poker player. After having a long converstion about things he does at work and things that he does in his free time we narrowed in on poker. Since we both play poker we both found it difficult to keep track of things that happen at the poker table espessally since you can be so focused on the game. Additionally good pker player always write down intersting events that happen at the table such as big hands, how they busted out, and tells of oher players. This idea of a dsl that allows for real time tracking of these events came to life. 

### Domain

_Describe the project's domain in five words._

real time Language for poker analysis

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would be able to use natural laguage to describe poker hands and events or even small key words/ operations to decribe events at the table. Such as "in my hand I held As(Ace of spades) 2s(2 of spades) I raise from 10$ big blid to 30$ preflop There is one caller, the flop comes ..., the turn comes ..., the oponent in ___ position bet ..., I called ..., the river card was a ..."
Another possible way would to use short function calls such as:
newhand(), myHand(), opponet(position on table, what was their action), Ibet(), EndHand() ect... a bunch of poker related functions that store quick and easy info about the table. 
The goal would be to use a language that allows for quick execution by the user, so that their attention does not devide from the table for more then a few moments. 


### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The program would save user poker infromation within a data sructure or database when the user makes a command. The types of errors that would be possible could be from the use of natural language processing or a bug in the sysytem with storage. These errors can be comunicted through direct feedback upon a user command. Additionally since poker is a game of percentages feedback on play can be updated by providing statistics back to the player upon each command given to the system. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to determine poker statistics, these are simple math function that would provide the player with particular analysis on their play whether that be by hand or by game overall. What should be possible but more difficult is finding a laguage whether it be nautural, semi natural, or not that allows for the queickest and most optimal way for user to input into the system. I dont think anything here would be impossible but it will be increasingly difficult to determine a poker language that can be both used by the player/user and a language that is easier to develop via code.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I do not know of any type language at the moment that allows for a poker player to do such a thing in real time. Right now there are varios online tools that allow for player to calculate pot odds and other poker statsistics but nothing as a real time tool. 

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I belive most of this project would be spend on the development of the language  and less so on the development of the system. This project whould have to optimize user understanging of the language as well as user speed, and language difficulty. 

### Scope

_How big an idea is this? How ambitious is this project?_

I feel like this project is something that could be done within a smaller time span such as a semester I also feel like the uses for such could be very big within the poker world. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

I feel like this is a cool project to work on because it peaks my interst in poker, with that being said there are some negative connotations around poker and the class may not decide this is the best use for a DSL. However I think there are many aspects of this that would be interesting to intagrate such as an optimal speed DSL for poker players, a way to save and analyze a natural like langauge, and automation of data structures and or databases. 
