# Schedulent

Schedulent is a project focused around putting recurring tasks into systems that allow to-do's but don't create routine todo's.

## Development Setup

- Set up an app for Basecamp at [https://integrate.37signals.com/](https://integrate.37signals.com/)
- Copy .env.development.sample to .env.development
- Place the Client ID and Client Secret for the app into .env.development as BC_CLIENT_ID and BC_CLIENT_SECRET respectively
- On the commandline run `rake secret`
- Copy the output into .env.development as SECRET_KEY_BASE

## Use Case

In Basecamp, create a to-do list each day for a morning routine. This will include tasks added to the to-do list in schedulent.

After the list's expiry period, remove the to-do's that don't get done.

## Required features

- Create To-do lists
- Add tasks to to-do lists
- Create schedules
- Add schedules to To-do lists
- Authentication (OAuth -> [Basecamp](http://basecamphq.com))

## Possible Future Features

- Boilerplate schedules (daily, weekly, weekdays, monthly, quarterly, etc.)
- [Google Calendar](http://google.com/calendar)
- Omnifocus
- [HighRise](http://highrisehq.com)
- API
- iOS app (probably Ionic)