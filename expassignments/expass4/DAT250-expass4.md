**Report**

*What I did*

Experiment 1

I cloned the repository and imported it to IntelliJ. I had some troubles running it initially, I think due to the fact that the repo was set up as an Eclipse project. Anyway, as a workaround, I set up a new maven project from scratch and copied over the source files and the pom.xml files. When running App class I could enter both http://localhost:8080/hello and http://localhost:8080/counters in my browser so it seems to have worked.

I registered a use in Postman and ran the requests "GET localhost:8080/counters" and "PUT localhost:8080/counters" with "{
    "red": 3,
    "green": 2
}" as the body.

*Technical problems*
- The cloning and importing of the first repository did not go smoothly. The project was created for eclipse, which has a different setup to IntelliJ. 