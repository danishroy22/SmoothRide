# SmoothRide

SmoothRide is an Android application designed to help users navigate safely by alerting them of road conditions, such as potholes, using real-time location data and markers on a map.
The app utilizes Google Maps and Firebase for data storage and retrieval.

## Features

- **Real-Time Location Tracking**: Users can view their current location on a Google Map.
- **Pothole Alerts**: Users receive audio alerts when approaching potholes marked on the map.
- **Custom Marker Icons**: Different colors for markers based on the severity of the potholes.
- **Snap to Road**: The app uses Google Roads API to snap user location to the nearest road.

## Technologies Used

- **Android**: Java for the Android app development.
- **Firebase**: For storing and retrieving pothole data.
- **Google Maps API**: For displaying the map and markers.
- **Google Roads API**: To accurately position user locations on the nearest road.

## Prerequisites

- Android Studio
- Java Development Kit (JDK)
- Google Maps API Key
- Firebase project setup with Firestore or Realtime Database

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/danishroy22/smoothride.git
   cd smoothride
