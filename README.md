1.  I automated the end points which mention in below URL.
(https://restful-api.dev/)
2. I have implemented these endpoints using cypress technology.
3. To run the test cases first clone the repositery from the Github.
4. Then open the project file through the Visual Stuido Code. (EndPointAutomation)
5. Go to terminal and execute below command. 
(run npm install) 
6. Run the below command in Terminal to open the cypress test runner.
(.\node_modules\.bin\cypress open)
7. Then you have to select the 'E2E Testing' option.
8. Then select any browser and tap on the 'Start E2E Testing' button.
9. Then you can see 4 test suites ( under that there are 12 test cases.)
10. You can select all the test suites one by one and included test cases will be automatically run.
11. Else you can run all the endpoints by running below command in terminal.
(./node_modules/.bin/cypress run --headed)
12. Else you can run all the endpoints in hedless mode by running below command in terminal.
(npx cypress run)