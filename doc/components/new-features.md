# New Features

Each new feature should contain:

- goals (what should be built)
- models (business logic)
- views (buttons, UI elements)

### -2 Record Trail

Record the entire trail if the user decided a spontaneous record.

### -1 History and Favorites

- old hikes
- saved pins
- saved locations
- saved trails
- drawn trails
- old records

### 0. Live Tracking

Acts as a pre-requirement. Its only goal is to send user location to the server.

- start recording types
  - start of a hike
  - record
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

- ro-alert
- SOS
- 112
- salvamont

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
