# cs340

How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

I write programs that are maintainable, readable, and adaptable by adhering to object-oriented programming principles like modularity and encapsulation.  Additionally, adhering to industry standard best practices regarding comments help keep the code readable.  In this case, it was useful for the CRUD module because I didn't need to refactor it several times as it was used throughout the course; making it modular and flexible in the first place allowed me to use it easily for each assignment.  With some minor modification to connect to other MongoDB instances, I could use this same module in the future to interface with any MongoDB docstore.

How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

In this case, the problem was one of presentation.  No new information was created when the CSV was loaded into MongoDB or when the dashboard was set up to query for specific things.  The same results, roughly, could have been accomplished with the original CSV dataset and Excel, or by manually running MongoDB queries once the dataset was ingested.  The point, then, was to remove that technical burden from the client in favor of a simple interface that would easily provide the information they found useful.

What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

In this case, my goal was to close the gap between technical capabilities, available data, and accessibility to the end user.  It is not reasonable to expect everyone to be able to use tools like MongoDB effectively, but the value added by effectively leverage those capabilities in conjunction with large datasets is potentially immense.  As a computer scientist, I make those capabilities available to users in a way that they will find useful and intuitive without needing to worry about the technical details.
