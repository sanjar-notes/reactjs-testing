# 4. Structure of tests

##### Test files
Designate test files by ending them with `.test.js` or `.test.jsx`. The prefix part is usually the component being tested.
Example: test file for `MyComponent.jsx` should be named `MyComponent.test.jsx`.

##### Running tests
To run all tests, simple run the command `npm run test`. This will run all test files of the project.

To run selected tests run the command `npm run test MyComponent.test.jsx`.

##### Structure of a test block
Each test, fundamentally consists of these phases, in order:
1. Preparing global store (Redux, for example) and props.
2. Rendering the component.
3. Locating elements that need to be tested
4. Interacting with the elements
5. Asserting the values of the result