# 100 Days Of Code - Log

### Day 0: 31 October 2018

**Today's Progress**: 
  - Started challenge.
  - Start with Javascript ES6.

**Thoughts:** 
My work is focussed on server-side development or back-end batch processing.  Here's my goals for this challenge:
  - ES6+ for Javascript
  - Node.js
  - Front-end development with JS framework like React or Vue.js
  - Progressive web apps
  - Docker

### Day 1: 1 November 2018
  - Getting npm working with VS Code with JQuery Intellisense.
  - Capturing key presses with JS.  It's possible to get the function keys (except F7 in Firefox) to response and cancel their default behaviour, so F5 can be used as a shortcut in the page without refreshing.

### Day 2: 2 November 2018
  - Created a sample webpage that captures the function keys (F1-F12) and overrides their default browser behaviour.  They can be used to trigger events within the page.
  - Published to GitHub pages: https://rundevcycle.github.io/js-keymapper/app.html

### Day 3: 4 November 2018
  - Clean up encapsulation of js-keymapper so it is a module with private properties.

### Day 4: 5 November 2018
  - Start another small project for JavaScript modules/classes with more properties.  
  - Setting up `eslint` for verifying code quality.

### Day 5: 6 November 2018
  - Adding more logic to JavaScript GS1 transcoder, applying what I've learned about strings and custom JS objects.

### Day 6: 7 November 2018
  - Add more logic to GS1 decode. 
  - Adjusting ESlint rules.

### Day 7: 8 November 2018
  - Looking into unit test frameworks for JavaScript.
  - Tweak GS1 decode logic a bit more.

### Day 8: 9 November 2018
  - Start a new project for a jigsaw puzzle app.
  - Having trouble getting eslint installed locally.  When it installs dependencies during eslint --init, 
    it deletes the eslint binary from the node packages .bin folder.

### Day 9: 10 November 2018
  - Setting up gulp for the GS1 project.  
  - Had to use gulp@next (4.0.0) due to high vulnerabilities with 3.9.1.

### Day 10: 12 November 2018
  - Adding mocha to GS1 project so I can start adding unit tests.
  
### Day 11: 13 November 2018
  - Breaking GS1 project logic into modules.  
  - Using the modules allows for mocha unit tests.
  - However, web page is now broken.  Need to investigate modules further.

### Day 12: 15 November 2018
  - Move mocha tests out of node.js and into a test runner web page.  The web page will run the tests
    with the mocha library and display the results in the page.
  - Clean up the src scripts to remove the module export and require().  They now load and run in a web page again.

### Day 13: 17 November 2018
  - Adding a page to decode a GS1 barcode into separate fields.
  - Start using Bootstrap to structure the HTML.

### Day 14: 19 November 2018
  - Adding some more fields to the decoder page.
  - Playing around with Revealing Module Pattern, but reverted changes.

### Day 15: 20 November 2018
  - Add secondary purchase fields to the decoder page.

### Day 16: 21 November 2018
  - Display all raw fields from the GS1 databar decoder.
  - Start adding methods to format data for presentation.  I want to revisit the gs1Coupon class and rework it a bit.
  
### Day 17: 22 November 2018
  - Splitting logic for formatting GS1 values into a separate module.
  - Getting a better understanding of when to use modules and when to use pure POJO classes.

### Day 18: 25 November 2018
  - Reviewing GS1 specs.
  - Too tired to spend a lot of time tonight on this.

### Day 19: 26 November 2018
  - Adding a bit more logic to the GS1 formatter.
  - I think it's time to move on to something else.  I want to learn JavaScript, not deal with application-specific logic that doesn't help with my goal.

### Day 20: 3 December 2018
  - Back from vacation.  
  - After reviewing where I left off, I decided to start with FreeCodeCamp and focus on the Javascript course there.

### Day 21: 4 December 2018
  - Continuing through the Javascript curriculum on FreeCodeCamp.

### Day 22: 5 December 2018
  - Continuing with FreeCodeCamp's Javascript course.

### Day 23: 6 December 2018
  - Finished the first chapter of the FreeCodeCamp Javascript course.
  - Started the second chapter on ES6.
  - Currently at 116 / 1,409 challenges.
  
### Day 24: 8 December 2018
  - Finished the second chapter (ES6) of FreeCodeCamp's Javascript course.
  - Next chapter is on regular expressions.
  - Progress is 135/ 1,409 challenges.
