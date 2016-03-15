# TDD Excercies

Here you will find example TDD exercises, the projects are all self contained and have the nessesary starting blocks for someone to complete the excerise.

### Exercises

* [Talky Numbers] - Write a function which, when given a number, returns the English word. So for example Enter 10, the program returns “ten”, Enter 1, program returns “one” and so on and so on.

### Doing the exercises

First write a test – it will inevitably fail because you have not yet implemented the underlying method, but this helps to show that you understand the expected interface.

Then implement the method in a way that the test will pass. Run the test to prove this.

Refactor the code
 - Check for duplication
 - Check method names etc
 - Clarify constructs

Re run the tests to prove that refactoring has not broken the code

Repeat; update the test method to test the next step and check if it fails

### How to begin

* Refine Scope (numbers are infinite!)
* Base cases and exceptions
* Focus on only writing the code needed to pass the test
* Iterative Improvements

Pick a maximum, decide integers, decide if you are doing –ve or not, look for recursion
BUT – keep it small. 

### Tech

* [Java 8] - Core language
* [Maven] - Build language

### Installation

You need Java 8 and Maven installed:

```sh
$ mvn clean install
```

### Todos

- Add more TDD exercises
