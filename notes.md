## Setup Process
Tom’s ReadMe (has instructions for the testing framework)

- Make a Repo
- create-react-app map-journal && cd map-journal
(Creating A react app)
- Doesn’t initialise a repo although it has a git ignore file. Hence you have to add a git repository
- Run Npm start to check file

- Setup testing framework
- Setting up enzyme (Create react has jest inside it already)
- install Chai enzyme@beta (Expecttion ones, convenient helpers to perform all kinds of code)
- install Chai [Versions of react the latest don’t have chai or mocha, so u need to download a beta version]
- install Sinon
- install sinon chai
- Src/SetupTests.js : mocha-enzyme-chai
- [App.test.js (line 11-1)
- Write a sample test, expect 1+2 = 3.
- npm test to run the sample test (to see if it passes and fails)
- Yay testing frameworks are setup!
- Get rid of unnesscary files (app.css, index.css , logo.svc)
- Writing to see if our react ends up on the page after delete files. Realised that we were requiring files that were deleted. Oops
- Strip it down, lewis says
- git checkout -b (nameofroute ~ change into notes route so that someone else can take notes) 
