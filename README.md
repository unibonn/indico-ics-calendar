# Installation
1.) Download [Fullcalendar](https://github.com/fullcalendar/fullcalendar). (The current version has been tested for fullcalendar-6.1.7.)

2.) Install iCalendar inside the fullcalendar folder:
```
npm install --save @fullcalendar/icalendar ical.js --prefix .
```

3.) Move `mycalendar.html` to `<fullcalendar-folder>/examples`.

4.) Create `<fullcalendar-folder>/examples/ics`.

5.) Place the ics-file that you want to display inside `<fullcalendar-folder>/examples/ics`. (The current default name is `feed.ics`.)

6.) Start a webserver inside the fullcalendar folder:
```
python3 -m http.server
```

7.) View the webserver in your browser and navigate to `<fullcalendar-folder>/examples/mycalendar.html`.
