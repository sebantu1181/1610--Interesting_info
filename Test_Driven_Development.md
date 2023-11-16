# Test Driven Development

Test-Driven Development (TDD) is a software development approach in which test cases are developed before writing the actual code. 
The TDD process follows a cycle of repetitive steps, known as the **"Red-Green-Refactor"** cycle, and is designed to improve: 
  - code quality,
  - maintainability, and
  - reliability.


## Three Main Phases in TDD cycle: 

1. Red: Write a failing test
   - In this step, the developer writes a test that checks a specific piece of functionality or behavior that is not yet implemented.
   - Since there is no code to satisfy the test, it initially fails
2. Green: Write the minimum code to pass the test
   -  In this step, the developer writes the minimum amount of code necessary to make the test pass.
   -  The focus is on implementing the required functionality and no more.
3. Refactor: Improve the code without changing its behavior
   - After the test has been successfully passed, the developer refactors the code to improve its structure, readability, or efficiency.
   - The goal is to enhance the code without altering its external behavior.


> This cycle is repeated iteratively, with additional tests and code being added incrementally.

### Benefits of Test-Driven Development include:

* **Early Detection of Issues**: TDD helps catch defects early in the development process, as tests are written before the code is fully implemented.
* **Improve Code Quality**: The process of writing tests and code incrementally often results in cleaner and more maintainable code.
* **Confidence in Changes**: Developers can make changes or add new features with confidence, knowing that existing tests will quickly identify any regressions.
* **Documentation**: Tests serve as executable documentation, providing examples of how the code should behave.
* **Incremental Development**: TDD supports an incremental and iterative development process, allowing for continuous improvement.


> TDD is closely associated with automated testing frameworks, where tests can be easily run and verified.

#### Testing Frameworks for Test-Driveb Development include:

* JUnit for Java
* pytest for Python
* NUnit for .NET
* Etc...



[<< Back](Acceptance_Testing.md)
