Meet App:

Link:  https://brocal82.github.io/meet/

Feature 1: Filter Events By City

As a user looking for events in a specific city,
I should be able to select a specific city from the filter menu,
So I can view only the events located in the selected city.

Feature 2: Show/Hide Event Details

As a user attending an event,
I should be able to click a toggle button,
So that I can expand or collapse the event details section to see more or less information about the event.

Feature 3: Specify Number of Events

As a user looking for events,
I should be able to input a specific number to specify the events to display,
so i can see the number of events in the listing page.

Feature 4: Use the App When Offline

As a user of the event application,
I should be able to access the app and view event data even when I lose internet connectivity or enable airplane mode,
So that I can still access event information.

Feature 5: Add an App Shortcut to the Home Screen

As a user of the mobile event application,
I should be presented with an option to add a shortcut so I can have quick access to the Meet App directly from my home screen.

Meet App 

1. Filter Events By City:

Given: You are on the events listing page.
When: You select a specific city from the filter menu.
Then: The events listing page displays only the events located in the selected city.

2. Show/Hide Event Details:

Given: You are viewing the event details page.
When: You click a toggle button.
Then: The event details section either expands or collapses, showing or hiding additional information about the event.

3. Specify Number of Events:

Given: You are on the events listing page.
When: You input a specific number to specify the desired number of events to display.
Then: The events listing page displays the specified number of events.

4. Use the App When Offline:

Given: You have previously accessed the event application and have an active internet connection.
When: You lose internet connectivity or enable airplane mode.
Then: The event application still works and data still accessible.

5. Add an App Shortcut to the Home Screen:

Given: You have installed the event application on your mobile device.
When: You long-press the app icon or access the app settings.
Then: You are presented with an option to add a shortcut to the home screen. After confirming, the app icon appears on the home screen for easy access.

6. Display Charts Visualizing Event Details:

Given: You are viewing the event details page.
When: You tap a "View Charts" button.
Then: The application shows data and visually charts about details from the event.


OBJETIVE:

The objective of this project is to build a serverless, progressive web application (PWA) using React and test-driven development (TDD) techniques. The application will use the Google Calendar API to fetch upcoming events. It aims to combine the benefits of serverless architecture and PWAs, offering features like instant loading, offline support, push notifications, and cross-platform compatibility.