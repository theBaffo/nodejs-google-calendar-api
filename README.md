# nodejs-google-calendar-api

A simple example of usage of the [Google Calendar API](https://developers.google.com/calendar) for NodeJS.

The example is mostly based on the [following quickstart](https://developers.google.com/calendar/quickstart/nodejs), but instead of listing existing events the application creates / update an event in the primary calendar.

To run the example, you need to create your own authorization credentials for a desktop application (see [here](https://developers.google.com/workspace/guides/create-credentials)) and save them in the root of the project in a file called 'credentials.json'.