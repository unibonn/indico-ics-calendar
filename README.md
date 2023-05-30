# Installation
0.) Navigate to the installation folder.

1.) Install [Fullcalendar](https://fullcalendar.io/). (The current version has been tested for fullcalendar-6.1.7.)\
This can be done using `npm`:
```
npm install fullcalendar --prefix .
```
You also need to install the iCalendar package:
```
npm install --save @fullcalendar/icalendar ical.js --prefix .
```

2.) Download the template from this repository:
```
wget https://raw.githubusercontent.com/unibonn/indico-ics-calendar/main/mycalendar.html
```

3.) Create a directory for storing the ics-files:
```
mkdir ics
```

4.) Place the ics-file that you want to display inside `<fullcalendar-folder>/ics`. (The current default name is `feed.ics`.)

5.) Start a webserver inside the fullcalendar folder:
```
python3 -m http.server
```

6.) View the webserver in your browser and navigate to `<fullcalendar-folder>/examples/mycalendar.html`.
