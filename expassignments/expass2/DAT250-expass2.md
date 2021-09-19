**Report**

Link to the repo: https://github.com/eivindszalay/dat250-expass2

I have resolved most of the problems I had last week. I've chosen to include the old report still, but this is the current one.

**What I did**
*Part 1*
- Cloned the repo from https://github.com/timKraeuter/dat250-jpa-example.
- At first I didn't manage to configure the project to run the main. After deleting and reinstalling IntelliJ it worked.
- After a lot of trouble inspecting the database, I found out it the "Database Tools and SQL" plugin was not enabled.
- After enabling the plugin, I created new apache derby db from sources; the testdb. I've added a screenshot of the inspection.
- Continued with the tutorial and created classes Family, Person, Job and JpaTest. I've added a screenshot of inspecting relationshipdb and the passed tests.


*Part 2*
- For part 2 i used the same project as in part one, and created a new package part2 no.hvl.dat250.jpa.basicexample where I created the new classes. 
- In main I call the method part2() which instanciates all the objects and creates an Entity Manager which handles the persistence.
- I've included screenshots of the database, 1 overview and 1 for each table.
- I've added a screenshot of the visualisation of the database to show the linking is correct.

**Problems**
- See the first report for details about problems I encountered.