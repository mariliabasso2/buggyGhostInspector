# buggy

Docs attached:
- Test Plan / Strategy / Bug Report - PDF (if visualizing the file in Gitbub make sure you click on "view more pages" as the document has 10 pages)
- Buggy_Automation - Cypress - zip file
- Ghost Inspector - Json File
- Sample of Cypress files - in case can't download zip file

As I’m not familiar with C# and have a tight deadline for this trial, I ended up choosing 2 different approaches:
 
**1. Cypress**   
Cypress is an end-to-end testing framework for web applications. It is an open-source JavaScript-based testing tool that allows developers/testers to       write and run automated tests for web applications. Its ease of use, intuitive syntax, and fast test execution times.
      - Download the “buggy_automation” file
       - main files for this test automation are:
         Login.cy.js
         Models.cy.js
To install cypress, I have used the following sequence:
  Using the Visual Studio terminal, commands
  1. npm install cypress --save-dev
  2. npm install -g npm (if don’t have npm installed)
  3. npm start       
  4. npx cypress open   (to open cypress)    
  5. Follow instructions given by cypress installer


**2. Ghost Inspector (Codeless tool)**
  1. Sign Up for https://ghostinspector.com/
  2. Go to your Dashboard
  3. Create a new suite
  4. Import the json file attached here
  5. You should be able to save and run the test
