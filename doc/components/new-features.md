# New Features

Each new feature should contain:

- goals (what should be built)
- models (business logic)
- views (buttons, UI elements)

### -2 Emergency Contancts

Each user uploads a dedicated list of trusted contancts. These will be notified in case of emergency.
These can be either:

- another Varful account
- email
- number

### -1 Record and Live Tracking

To "record" means to collect data from the user while he travels on the path.

Types:

- spontaneous recording (the user agrees before starting)
- scheduled recording (a notification is sent, the user must accept it)

When starting the trail, the application logs:

- carrier (mobile operator)

Once per half a minute the application logs:

- media
  - photos
  - videos
- location
  - longitude
  - latitude
  - altitude
- map
  - pace
  - battery

When finishing the trail, the application displays:

- duration
- distance
- elevation
- trail
- pace

Its only goal is to send user location to the server.

- share types
  - private - only communicate with the server for security purposes
  - protected - share location by choice with other users within our features
  - public - the location will be visible on the map
- interaction types
  - view profile
  - message user
  - see current location/hike/trail
  - see alerts of the current session
  - see statistics (see "Statistics" feature)
  - save location
  - add to drawn trail
  - get directions

### 0. History and Favorites

Create user browsable lists for:

- saved locations
- old hikes
- saved trails
- drawn trails
- saved pins
- old records

### 1. Alerts

Mark the map with no internet zones

When live, or not (asked the source of information).
Different retention times.

Different levels of alerts.

- critical
  - missing person
  - severe medical emergency
  - aggressive animal encounter
  - active wildfire
  - avalanche risk
  - flash flood
  - severe lightning storm
  - active rockslide
- warning
  - no internet zone
  - blocked trail by fallen tree or boulder
  - washed out or collapsed path
  - deep hole or crevasse
  - broken bridge
  - slippery ice or deep snow
  - missing trail markers
  - venomous animal or dangerous insect nest
  - active hunting area
  - high wind
  - flooded trail section
- information
  - mountain hut or refuge
  - Salvamont or mountain rescue post
  - potable water spring
  - cellular signal hotspot
  - intersecting logging or paved road
  - found object or dropped equipment
  - rest shelter
  - scenic viewpoint
  - heavy trail traffic
  - minor terrain degradation

#### Graph

The goal is to access our platform

1. cell tower - his provider
2. cell tower - any provider

- emergency LEO
- StarLink LEO
- Mesh

- send to all nearby phones
- cache in all nearby phones (if needed)
- first to get access to send the server data, send it

### 2. Statistics

Give multiple share options including to not share at all

Implement live map tracking of users: to see the exact live location of other users. Every hiking user that activates its location sharing, will be visible on the map.

achieved by calling specific APIs based on the provided coordinates

- statisics
  - pace
  - elevation
  - completion percentage

### 3. Community

#### Goals

#### Business Logic

#### Implementation

- update the terns and conditions
- update the privacy policy

Media Uploading

- locations, photos, videos
- posts integrations
- blogs integrations

- expected return type

- Search and Rescue - SAR
- Public Regulated Service - PRS
- remind to turn on ro-alert
- barometer
- accelerometer
- fall - are you okay emergency screen activated
- offline - weather
- coverage map for users
- log signal strength
- build the dead zone
- daylight warnings
- low battery
- group/guides - extra
  - warning fires when hiker something
- offline alerts
- closest place and directions to places with coverage
- bluethoot - group hikes for stats
- breadcrumb upload
- EWSS - would cover the gap RO-ALERT leaves on the ridges
- OSNMA - gps can be
