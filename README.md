# FRONT-END ASSESSMENT (DO NOT FORK THIS REPOSITORY)

## OBJECTIVE
Our objective with this step in the recruitment process is to better understand your technical skills.

## DELIVERY REQUIREMENTS
To use the Endpoints below, you will need to be authenticated, for this you will use [GITHUB authentication](https://docs.github.com/pt/developers/apps/building-oauth-apps).

- We would like you to deliver an application using the [GITHUB API](https://developer.github.com/v3/) consuming the following endpoints:

1. Endpoint user: https://api.github.com/users/USERNAME
2. Endpoint repos: https://api.github.com/users/USERNAME/repos
3. Endpoint starred: https://api.github.com/users/USERNAME/starred

- The application should consist of three main components:

1. The search field.
2. Results visualization.
3. Two buttons to execute a specific result.

- Some use cases:
1. When clicking on the repos and starred buttons, a simple list of each endpoint should be displayed as previously presented.
2. Given a specific user, it should be possible to navigate directly to the user's detail page without the need to perform a new search. Ex: http://localhost:3000/USERNAME
3. We would like to search for a user.
4. We would like to list the repositories of the searched user when clicking on the repos button.
5. We would like to list the most visited repositories by that user when clicking on the starred button.

## EXPECTED STACK FOR THE TEST
1. HTML 5 (Use of SEO, Semantics, Usability is desirable).
2. JAVASCRIPT (React.js, Performance).
3. CSS 3 (Use of SASS, LESS, Bootstrap is desirable, Scalability, Responsiveness, BEM CSS).

## TIPS:
- You can use any UI library of your choice ([Here is a curated list](https://github.com/anubhavsrivastava/awesome-ui-component-library)). 
- You must use the [React framework](https://react.dev/) for developing your application.
- You can use [Jest](https://jestjs.io/) to test the requests made.

**Mandatory Requirements**:

- Check best practices for CSS 3 and BEM CSS Methodology;
- Check best practices for React;
- Check best practices for HTML 5;

Try to make a simple but consistent delivery, using the experience and knowledge acquired during your career.
Don't worry about delivering something extremely complete or elaborate, we won't use this code in production.

## EVALUATION
The evaluation will be done as follows:

1. We will analyze and compile your code;
2. Run your application and execute tests to validate the functional fulfillment of the items above;
3. Verify if your code is clean (Clean Code), easy to understand, and maintainable;
4. During the interview, we may simulate a review of your code, we will go through the code with you to discuss your implementation decisions, the positive and negative points;
5. The balance between the positive and the negative will determine the technical recommendation or not of your hiring. (If you are close to achieving a positive recommendation, we will give you a deadline to correct and return);

**Everything** will be evaluated, do your best!
