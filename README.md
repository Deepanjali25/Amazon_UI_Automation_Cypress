# Project Name
# Amazon_UI_Automation-Cypress
Automation testing using Cypress to test amazon website features

#Test Cases
- Perform a UI automation to test a task - “Search & add a product to the cart & come till payments page ”
- Open amazon in the browser
- Search for a "dress"
- Select any "dress" from the search page
- Go to the product detail page & select the size
- Click on “ADD TO CART”
- Click on GO TO CART”
- Validate Order summary - Price & Quantity - Print & assert them
- Click “Proceed to buy”
- On the Login popup screen take a screenshot

#Steps to Setup
- Install NodeJS, Cypress
- create a new project and type 'npx cypress open' in the terminal at current folder path (This will create all required files to automate the process)
- Write the test cases

#Steps to run
- Run Cypress --> npx cypress open
- Run testCases --> spec.cy.js (fileName)
- Saved screenshot --> screenshots (folder)