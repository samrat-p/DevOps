## CI / CD
To manage production capable applications we need to use CI/CD.
Continuous integration to Continuous Delivery to Continuous Deployment that is how the process goes.
Most used tool used in CI/CD is **Jenkins**.  Jenkins is a pipeline management tool for production based applications.
Before talking about jenkins lets understand what is Continuous integration.
before CI/CD a developer has to write lenghty code for applications and push it for the testing to see there is any bug or not. Developers had to wait long time to know their bugs and even after fixing the bug devs had to push the code again and wait for the results. Thats when CI/CD is comes to use.
By implementing CI/CD you make a pipeline to the jenkins server. A jenkins server is a virtual testing server. In a jenkins pipeline what happens is whenever a dev writes a code or changes the code the jenkins server takes that particular code , compile the code and jenkins server will make a bulid and push it for testing so everytime a developer writes a code, in a very short time the dev's gonna know there is any bug or not.
**Continuous Intregration** isn't just about compiling the code, its also **compile, code review, unit testing, Intregration testing, application packaging**.
In **Continuous Delivery** the bulid will push to the test server for UAT (User acceptance Test) like End to end test. ( Inside the test server bulid will go and all the testing will be done to check basics things like functions,log in,log out and stuff.)
In **Continuous Deployment** after testing the bulid , it will straight go to the deployment server for  final release.

