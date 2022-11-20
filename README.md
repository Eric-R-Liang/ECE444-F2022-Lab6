# ECE444-F2022-Lab6
Final deployed heroku app link: <br>https://ece444-lab6-flaskr.herokuapp.com <br><br>
URL to the test functions in Project 1: <br> https://github.com/Group12-TripleFour/Project1/blob/main/Education_Pathways/tests/test_comparison.py

## What are the pros and cons of TDD?
Pros of TDD:
* **Avoiding unnecessary complexity in production code** - following the principles of TDD, developers only need to implement features that pass the designed test cases. This way, any unnecessary complications in the final production code can be properly avoided. 
* **Simplifying code review** - due to the natural back and forth cycles in TDD, most bugs should already be addressed in the testing phase. Hence, there is likely less debugging required after features have been successfully developed, thus simplifying the code review process. 
* **Modularizing code structure** - during the process of TDD, every microfeature is considered one at a time. Tests are written first to help drive the implementation of the feature and lay out all the requirements. Thus, the production code becomes easier to check and leads to a more modular design. 

Cons of TDD:
* **Inherent developer's biases** - depending on the angles that developers examine the microfeature, there can be edge cases that are neglected by the developers which leads to the presence of unaddressed bugs in the final production. Furthermore, developers can also introduce bugs in the test cases, which leads to wrongful implementations of the microfeature. 
* **Time consuming** - due to the nature of TDD, developers need to write test cases before they implement any feature of the app, even if some seem to be trivial. This can prolong the development phase to some degree. 
* **Robustness of tests** - as requirements change during the maintenance phase of the application, new tests need to be introduced or old tests need to be redeveloped in order to meet the new criteria ensure robustness.
