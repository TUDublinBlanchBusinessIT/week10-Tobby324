# Week 10 - Tennis Club Login: Laravel Mix & FullCalendar

## Note on Repository History

This repository contains the Week 10 lab work built on top of the Week 7 Tennis Club Login application. The Week 7 codebase was used as the starting point for Week 10, which is why earlier commits from Week 7 appear in the commit history.

## Week 10 Work Summary

The following features were added as part of the Week 10 lab:

### Blog 1 - Setting up Front End Dependencies with Laravel Mix
- Installed Node.js dependencies using npm
- Configured webpack.mix.js for Bootstrap and jQuery bundling
- Compiled assets into public/js/app.js and public/css/app.css

### Blog 2 - Adding FullCalendar with Laravel Mix
- Installed FullCalendar packages via npm
- Created calendar.js with FullCalendar imports
- Created CalendarController and display view
- Added calendar route to web.php

### Blog 3 - Getting JSON Events from Database
- Created event database view in MySQL
- Created Event model class
- Added JSON endpoint to CalendarController
- Updated calendar display to load events from database

### Blog 4 - Adding Modal Form to Create Bookings
- Created modalbooking.blade.php with Bootstrap 5 modal
- Added dateClick event to FullCalendar
- Modal pre-populates date and time on click

### Blog 5 - Finalising the Modal Booking Form
- Updated modal title to "New Booking"
- Finalised booking form submission
