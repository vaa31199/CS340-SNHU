# CS340-SNHU
A portfolio that contains the work I have completed for CS340 at Southern New Hampshire University.

# Course Reflection Questions
## How do you write programs that are maintainable, readable, and adaptable?
Writing focused code is useful for maintainability and readability. For example, instead of creating a monolithic block of code containing all of the functions, classes, and main, it might be better to organize the files into classes. With this scheme, an individual library could be tweaked/fixed, and then any code importing this library benefits from that fix/tweak.
## Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way?
The main advantage I can take away from having a separate module to handle the connections between the dashboard and the database is overall shorter and cleaner files. As I previously touched upon, including everything in one file, while a disk space saver, would make the code a bit crowded and tougher to work with; Separating them into two files keeps them both concise and their contents focused.
## How else could you use this CRUD Python module in the future?
Since I already know it works, it's 100% possible that I could wind up using this again at some point in the future. In the event a project I'm working on uses MongoDB, this module will be able to be used.

## How do you approach a problem as a computer scientist? 
Usually, development starts with me taking stock of what exactly needs to be done with the application in question and sorting everything by priority. Every single aspect is weighed based on how important it is to have that aspect of the project finished. Once everything has been looked at and classified, I usually start by tackling one of the important components and stay on it until it’s done. After that, I’ll take care of some of the smaller, less important items to give myself a little bit of a rest before moving back into another important task. This cycle continues until everything on the initial list is complete.
## Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? 
My approach to this specific assignment didn't differ much from the approach I use for all of my assignments, regardless of course. When you've got a system that works for you as well as this one, it's difficult to justify straying from it.
## What techniques or strategies would you use in the future to create databases to meet other client requests?
When creating a database, it's important to know exactly what information has to be stored in it and how to store it. In a previous course, I was instructed to pay significant attention to these aspects and always make sure to have them exactly correct before creating the framework for a database.

## What do computer scientists do, and why does it matter? 
In my opinion, computer scientists are problem solvers who use programming to find solutions to those problems effectively and efficiently. This matters because many of the problems they are faced with correlate to problems others in different fields are having; Therefore, computer scientists solving those problems also helps other fields of study eliminate issues and increase their work output.
## How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
A dashboard that interprets and visualizes data speeds up the time it would take for employees to do their work significantly by eliminating the need to manually search through their records. Sure, it may not matter much for certain kinds of setups where records are minimal, but once the amount of records starts to pile up, work would slow down to a near halt, and a faster way of finding necessary data is almost required for anything to be done.
