# Family Managment App

I'm looking to build an app that can be integrated with something on a monitor in my home (maybe Apple TV?) and work with iPhone and Apple Watch. The goal of this app is to help my neurodivergent family of multiple generations keep track of ourselves, our homes, and our fur babies. 

## Features that should be added:
- Schedule
  - “Norm”: weekly dr appts (PT, therapy), grocery shopping, away from the house
  - “One off”: Special shopping trips (hardware), visiting people
  - “Chores”: taking trash to the corner, laundry, cleaning bathrooms
- Lists
  - “Weekly”: food, toilet paper
  - “Subscription”: Blue Apron, Grove
  - “Projects”: building projects specific trips
  - “Backfill”: Filters for air purifiers
- Information
  - Pet information: medications, procedures, food, birthdays
  - Human information: birthdays, medications, sizes
  - Vehicle information: registration, license plate numbers, gas, service dates
  - Clothes: sizes, items, etc
- Tracking
  - Health: Copilot exercise, PT, pet health (exercise minutes)
  - Learning: Ayla learning things
  - Projects: Garden, houses, river
- Prep for next activity
  - Example: I’m going to go to Trader Joes, are there packages I need to take to the post office?
- Give me an idea
  - Based on what food/ingredients I have, what can I make? ([MealAPI](https://www.themealdb.com/api.php))
  - Based on what Ayla has been doing, what projects/activities should we do?
  - Based on how we’ve been physically feeling, what exercise should we do?
  - Based on random things around the house, what projects should we do?

## Goals:
- A one stop shop for your day
- Wake up - look at what needs to be done that day
- Have 10 minutes? Look at what could be done
- Gamification
- Help with neurodivergence
- Help with sustainability of good habits
- Optimize the state of the house >> freedom for people

## Technical features:
- You can dig deeper for information
- Amounts, expiration dates, sizes, 
- Displaying the time that things actually take (minutes, hours, days, weeks, etc)
- Notifications

## Assumptions:
- Specific time deadlines for each day will yield better results and less stress
- I will need a variable to guide the schedule based on these deadlines

## Integrations:
- Google calendar (others?)
- iOS (phone/watch) for notifications and quick “check off” of tasks
- Apple TV/web app for displaying on  monitor in house
- Philips Hue for proactively and automatically turning lights on/off
- Nest for proactively and automatically turning cameras and thermostat on/off
- Anylist OR create own version
- Weather

## Resources:
- [Apple TV App](https://developer.apple.com/library/archive/documentation/General/Conceptual/AppleTV_PG/index.html#//apple_ref/doc/uid/TP40015241)
- [Google Calendar API](https://developers.google.com/calendar/api)
- [Philips Hue API](https://developers.meethue.com/)
- [Nest API](https://developers.nest.com/reference/api-overview)
- [Anylist](https://blog.anylist.com/2020/09/anylist-widgets-for-ios/)

## MVP:
- Daily schedule - [Figma](https://www.figma.com/file/RHZg9Wbq6gaXDfCMzZvOsf/Basic-Family-Management-App-Schedule?node-id=0%3A1)
- Profile on people and humans
- Starting to take an inventory of the house
