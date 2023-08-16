Meet App

Link:  https://brocal82.github.io/meet/

This application has been built using React on the frontend and AWS Lambda on the backend. It showcases a dynamic list of events sourced from the Google Calendar API. Users have the ability to filter events based on the city or event count.

Prerequisites:
Install Node.js

Installation:
Clone the repository.
Navigate to the project directory in the terminal.
Run npm install to install the necessary dependencies.

Technologies Used:
React
Jest
React testing library
Puppeteer

Development Server:
Run npm run start for a development server.
Navigate to http://localhost:3000/meet_app.
The application will automatically reload if you change any source files.

Build:
Run npm run build to build the project.
Build artifacts will be stored in the dist/ directory.

Deployment:
Run npm run deploy to deploy to GitHub Pages.


FEATURE 1: Filter Events by City

  Scenario 1: Filter events by city.

    Given the main page with search options has been opened,
    When the user enters a city,
    Then the application should display upcoming events for that city.

  Scenario 2: Display all events by default.

    Given the main page with search options is open,
    When the user opens the app without specifying a city,
    Then a list of all events for all available cities should be shown.

  Scenario 3: Select a city from suggestions.

    Given the user is typing a city like "Berlin" in the city textbox and the suggested cities list is visible,
    When the user selects a city (e.g., "Berlin, Germany") from the list,
    Then the selected city should replace the current city ("Berlin, Germany") and the user should see a list of upcoming events in that city.


FEATURE 2: Show/Hide Event Details

  Scenario 1: Collapse event details by default.

    Given the user opens the app,
    When the user receives a full list of events,
    Then all events should be collapsed by default.

  Scenario 2: Expand an event to see details.

    Given the user gets a list of events,
    When the user selects an event's details,
    Then the details of the chosen event will be displayed.

  Scenario 3: Collapse an event to hide details.

    Given the user sees event details,
    When the user presses a button to hide event details,
    Then the details of that event will be hidden.

FEATURE 3: Specify Number of Displayed Events

  Scenario 1: Default number is 32 when not specified.

    Given the user has not specified or filtered any number,
    When the user sees the list,
    Then the default number of displayed events should be 32.

  Scenario 2: Change the number of events displayed.

    Given the user has events displayed,
    When the user chooses to change the number of events displayed,
    Then the number of events displayed should update to the selected number.

FEATURE 4: Use the App When Offline

  Scenario 1: Show cached data when there's no internet connection.

    Given the user has no internet connection,
    When the user accesses the app,
    Then the app should show cached data stored inside the app.

  Scenario 2: Show error when user changes settings (city, time range) without internet connection.

    Given the user has no internet connection,
    When the user tries to access new event information (change city, etc.),
    Then the app should display an error.

FEATURE 5: Add an App Shortcut to the Home Screen

  Scenario 1: User can install the app as a shortcut on their device home screen.

    Given the user wants to install the app,
    When the user selects to install the app as a shortcut,
    Then a shortcut should be created on the user's home screen.

FEATURE 6: Display Charts Visualizing Event Details

  Scenario 1: Show a chart with the number of upcoming events in each city.

    Given the user is on the event details page,
    When the user clicks a button to view a chart comparing events in all cities,
    Then a chart displaying the number of upcoming events for each city should be shown.


Use of Serverless Functionality in the Meet App:

The Meet App can leverage serverless functions for event notifications, real-time data processing, user authentication, event recommendations, and scalability. By harnessing serverless technology, the app can efficiently manage backend processes, offer personalized experiences, and scale seamlessly based on user demand.