

How to use/features of web aplication

Our website uses two APIs: The Google Maps API and the Ticketmaster API to display events to the user as a list view and as well as a map view.
The user is able to navigate through the list view and open a detailed view of the event or can view just the map with different event locations. All the views on our website have been made responsive using bootstrap and we have also added animations to some of our views using an open source css library called animate.css 

- We have divided our web application according to different views:
- The landing page is the background cover page with an image which has a button embedded on it saying "Enter Website". The user clicks the website to change it's view to another one.
- The next view has a navigation bar which lists "Event List" and "Map view" to switch between different views. In addition, the search filters are present on the second view based on country code,city and category, music, sports(basketball, baseball) etc. If the user clicks the filter without enetering any text in the filter, it will lead him to the events list that are occuring in North America(TicketMaster API events).
- For the subsequent view, event detail view is entered by clicking any of the events on the event list. The detailed view will show the image of the event, location of the specific event on the map (provided by the Google Maps API), and the details of the event like date, start time, event promoter, ticket price range, venue. There is another button called "Go Back" where the user clicks to go back to the event detail view wherever they started from initially rather than the front of the view.
- The last view is the map view of the navigation bar where the user will see all the location of the events based on the filter. For example, if the user types music in the "enter event category" and toronto in the "enter country code", it will show the the music events in toronto. At any time, the user can switch between views using the navigation bar button on the right.
