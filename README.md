# Project Overview

This project is web-based application that reads RSS feeds.The task is to use a testing suite - [Jasmine](http://jasmine.github.io/), to validate the code for errors.


## Testing

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.


## feedreader.js

 This is the spec file that Jasmine will read and contains all of the tests that will be run against this application.
 Tests are independent of one another.


## What tests have been performed?

- tests to make sure that the allFeeds variable has been defined and that it is not empty.
- loops through each feed and determines if the URL is defined and not empty.
- loops through each feed and determines that each feed has a name and not empty.
- ensures the menu element is hidden by default.
- validates proper functioning of the hamburger menu toggle.
- tests that there is at least one entry in feed.
- tests that new content is loaded by loadFeed().


## Steps to run the application

To start the app, open `index.html` in your browser.

The tests were written in the `feedreader.js` file. The test results appears at the bottom of the `index.html` page.

If there are 0 failures - all spects (tests) have passed.

## Additional aspects

Code is formatted as described in the [Udacity JavaScript Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html).

Review the Feed Reader Testing - [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric).
