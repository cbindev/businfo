# Bus Feedback at RIT

This is a simple static page intended to provide RIT bus system users with information and collect their feedback.

## Advanced Usage and embedding

If you would like to embed this form in a project of yours, there are some advanced features that you may find useful to take advantage of.

First, to protect yourself against future planned changes to the main ritbus.info site, it is recommended that embedding and linking that is intended to point to the reporting form be directed to the https://ritbus.info/report page

Second, if your project already has access to information about RIT's official bus route numbers, route names, and/or stop names, you can include additional URL parameters to help pre-fill the first page of the form to make things easy for the people using this form through your site!

The available URL parameters are:
- `category` - This specifies which type of report this is, matching the text on the buttons for this form field, for example: `category=Report%20a%20delay%20or%20small%20issue`
- `route` - This field will pre-fill the route value in the form. It is expected to be of the format `ROUTE_NUMBER - ROUTE_NAME`, for exampme: `route=1%20-%20Off%20Campus%20Express`
- `stop` - This field will pre-fill the stop value in the form. Example: `stop=Gleason%20Circle`

These parameters can be combined together if desired to fill in all three values.

If you have integrated this form into a project of yours, let us know by filing a pull request to update this README to link to your project! We would love to learn about all the cool ways in which our form is being shared with students!

## Projects embedding this form
- https://rit-bus.app

## Future Plans
The initial scope of this website is to collect feedback using a Tally form system. In the future and as part of the club's Imagine RIT Project, the following information might or might not be provided:

- Links to current schedule timetables
- Tips for first time riders
- Real time tracking, if available
- Referrals to other apps (Transit, Passio, etc)
- Documents related to the shuttle system's operation and historical service patterns

## Affiliation Disclaimer
**This website is not an official university resource**, and operates independently in collaboration with RIT Student Government. Changes to this website are overseen by Urbanism at RIT, a student-run and student-led organization on campus. In the event of an emergency on the RIT shuttle system, contact Public Safety at (585) 475-3333.
