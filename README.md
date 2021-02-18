Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

[![Board Status](https://dev.azure.com/greatlittleapp/2e11dde8-082b-4796-ac4b-f51ba9458acf/b7ffe02e-b08b-4356-a5bc-1f2f0497f605/_apis/work/boardbadge/b39accad-d7bd-4049-87f7-3e6a0a637491?columnOptions=1)](https://dev.azure.com/greatlittleapp/2e11dde8-082b-4796-ac4b-f51ba9458acf/_boards/board/t/b7ffe02e-b08b-4356-a5bc-1f2f0497f605/Microsoft.RequirementCategory/)

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

