# React Coding Challenge
This code challenge tests your skills in react.js (using Typescript, Javascript), testing and modular design. The purpose of the application is to correctly interact with an API, and render all the messages coming from an api. Different messages will be coded different colors and require slightly different rendering. The rules are described in detail below.

1.- login in to the api with the provided credentials

2.- Access the API, and implement the following methods



This challenge already includes an API response. It is not required or expected for you to make any changes to this interaction.

The 3 status that we provide you are:

0 = not readed
1 = readed

Acceptance Criteria
Reports should be rendered in a table-like structure. The newest reports should appear at the top of their respective columns.
Provide test coverage of the components.


The messages should be color coded depending on the status of the report. The appropriate color per status is:

not_readed: #F56236
readed: #FCE788


Each time a message with the status not readed is received, a snackbar containing the message should also appear at the top right of the application. The message should disappear in 2 seconds, when another message takes its place, or when the user clears it via the provided button located in the notification message.

A user should be able to clear all reports at any point.

A user should be able to clear a specific report in a specific column

A user should be able to start and stop incoming reports. By default the messages should be running and displaying on the grid. The start/stop button should update depending on the state of the feed.

A user should see a count of specific reports in each column

Use material-ui components and styled-component styles

Write meaninful and useful unit tests. jest is already included in the project

Use functional components

Improve code structure. Your implementation should be more like how you do it for any production grade application development

Define Typescript, Javascript types where necessary

Please submit your code either via Github or Gitlab

Use React context API and hooks to showcase your understanding of these React features

Pay attention to performance of your page rendering

"idoven.ai Coding Challenge" is part of the design. Make sure that you dont miss that header

Applicants are provided this challenge with nan expextation of deadline. Please take the time you need to complete the challenge to the best of your ability within the allowed 7 days.
