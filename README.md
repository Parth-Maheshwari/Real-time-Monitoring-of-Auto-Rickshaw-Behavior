# Real-time-Monitoring-of-Auto-Rickshaw-Behavior

Made an Android App for monitoring and booking of Auto Rickshaws for IITB campus

The application was developed using Android Studio 3.0.1, which can allow bookings and storing the details of customers and drivers is developed. In this app, we have used Google maps API for Google Maps Android,
Google Places, Google Maps Directions, and Google Maps Roads. We have used Firebase for real time storage database and for authentication of customer or driver (which is open source and free up to 10GB
of storage). Geofire, which includes open source libraries, used to perform real time querying on the firebase database to allot a driver to customer based on distance between them and routing to the
destination.

The location of the customer or driver is on the app and database every second with the help of GPS and internet of the user device. However, the time gap can be set to 5 seconds if the battery drains too
quickly. We cannot get the location if the driver logs out of the app.
