# E4501 Tools For Analytics Final-Project: Tracking Squirrel Sightings

## Background
Eccentric billionaire Joffrey Hosencratz just purchased the web development company you work for. You’ve met him once in an elevator and he was impressed with your skill in developing web applications with the Django framework. He also relayed that his most recent trip to Sedona, AZ has left him in a bit of trouble. See, he fancies the show Rick and Morty and a particular scene coupled with a traumatic childhood squirrel experience and a bad crystal bath experience in Sedona has left him wanting.

## Web Application Introduction
An application that can import the 2018 Central Park Squirrel Census data and add, update, and view squirrel data to start keeping track of all the known squirrels and plans to start with Central Park.

## Dataset
This application use the [**2018 Central Park Squirrel Census**](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw) created by [**The Squirrel Census**](https://www.thesquirrelcensus.com/).
They count squirrels and present their findings to the public. This table contains squirrel data for each of the 3,023 sightings, including location coordinates, age, primary and secondary fur color, elevation, activities, communications, and interactions between squirrels and with humans.

## Management Commands
Import: A command that can be used to import the data from the 2018 census file (in CSV format). The file path should be specified at the command line after the name of the management command. 
```sh
python manage.py import_squirrel_data /path/to/file.csv
```
Export: A command that can be used to export the data in CSV format. The file path should be specified at the command line after the name of the management command. 
```sh
python manage.py export_squirrel_data /path/to/file.csv
```

## Views
### Map
A view that shows a map that displays the location of the squirrel sightings on an [**OpenStreets map**](https://www.openstreetmap.org/about/).

- Located at: /map
- Methods Supported: GET
- Will use the [**leafletjs**](https://leafletjs.com/) library for plotting



### Sightings
A view that lists all squirrel sightings with links to view each sighting.

[Sightings]

### Update
A view to update a particular sighting.

[Update]

### Add
A view to create a new sighting.

[Add]

### General Statistics
A view with general stats about the sightings.

[Stats]

## Contributors
Group name: Project 9

Section: 2

Contributors: Els Dai, Ping Hsun Lee

UNI: [**ed2912**](https://github.com/els0911), [**pl2775**](https://github.com/junglewill)

[**Link**] to our server
