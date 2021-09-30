**Report Experiment Assignment 4**

**Experiment 1**

*What I did*

I cloned the repository and imported it to IntelliJ. I had some troubles running it initially, I think due to the fact that the repo was set up as an Eclipse project. Anyway, as a workaround, I set up a new maven project from scratch and copied over the source files and the pom.xml files. When running App class I could enter both http://localhost:8080/hello and http://localhost:8080/counters in my browser so it seems to have worked.

I registered a use in Postman and ran the requests "GET localhost:8080/counters" and "PUT localhost:8080/counters" with "{
    "red": 3,
    "green": 2
}" as the body.

*Technical problems*
- The cloning and importing of the first repository did not go smoothly. The project was created for Eclipse, which has a different setup to IntelliJ. 

**Experiment 2**

Link to the repository containing the code: https://github.com/eivindszalay/TODO_REST_API.git

*What I did*

* I created a TodoService to handle the todos.
* In the App class I define and implement all the CRUD opeartions.
* When the users posts a new todo, a new url is created.
* It is only possible to get and put todos that are already posted.
* "get http://localhost:8080/todos" lists all the todos. 
* I implemented a class StandardResponse to give information about the response.


*Technical problems*

Had some inital problems with the setup, but I followed this, https://sparkjava.com/tutorials/maven-setup, tutorial to get the Spark project up and running.

