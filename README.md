### What is this repository for? ###

* nodejs-developer-exercise-2 is a node.js repository used as an exercise to assist with node.js developer recruiting

### How do I get set up? ###

* Install
	- git clone https://bitbucket.org/elminda/nodejs-developer-exercise && cd nodejs-developer-exercise-2 && yarn
* How to run the script
	- yarn runReview
* How to run tests
	- yarn test
	- tarn test:watch (run tests and watch files for changes)

### Contribution guidelines ###

* Writing tests
	[chai] (http://www.chaijs.com/)
	[rewire](https://www.npmjs.com/package/rewire)
	[sinon](https://www.npmjs.com/package/sinon)

* Other guidelines

### Who do I talk to? ###

* Owners: Noga Gal <gal@elminda.com> and Yehoshua Jacobson <joshua@elminda.com>

### The Task Instructions: ###

  *	Refactoring: the file “reviewSubjects.js” was written in 2015 with ECMA Script 5.1 standard and uses nodejs version 4.
  	Refactor it so it would use a more advanced syntax.
  *	Make the tests green again:
  	The test file “reviewSubjects.spec.js” is broken and the unit tests are failing. Fix it so that  all 9 unit tests will pass successfully.
  *	push you changes to a feature branch. do not create a pull request.

### Bonus tasks: ###

  * Refactor “reviewSubjects.js” to use typescript
  * Add more tests to “reviewSubjects.spec.js” to reach 100% code coverage.