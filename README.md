# ILIAD OGC SensorThings API 
OGC SensorThings API for ILIAD ocean twin project.
Source data is modelled according to the Ocean Information Model (OIM).
Data is retrieved from a semantic store (Virtuoso triplestore).

| :warning: Methods require 'application/json' in accept header, i.e., -H "accept: application/json"   |
|:-----------------------------------------------------------------------------------------------------|

## Table of Contents
- [ILIAD OGC SensorThings API](#iliad-ogc-sensorthings-api)
  - [Table of Contents](#table-of-contents)
  - [Base Resource Path](#base-resource-path)
  - [Observations](#observations)
    - [Retrieve all Observations](#retrieve-all-observations)
    - [Retrieve a specific Observation](#retrieve-a-specific-observation)
    - [Retrieve Observations for a specific Datastream](#retrieve-observations-for-a-specific-datastream)
  - [Datastreams](#datastreams)
    - [Retrieve all the Datastreams](#retrieve-all-the-datastreams)
    - [Retrieve a specific Datastream.](#retrieve-a-specific-datastream)
    - [Retrieve Datastream for a specific Observation](#retrieve-datastream-for-a-specific-observation)
  - [Features of Interest](#features-of-interest)
    - [Retrieve all FeaturesOfInterest](#retrieve-all-featuresofinterest)
    - [Retrieve a specific FeatureOfInterest](#retrieve-a-specific-featureofinterest)
    - [Retrieve Observation for a specific FeatureOfInterest](#retrieve-observation-for-a-specific-featureofinterest)
  - [Observed properties](#observed-properties)
    - [Retrieve all the Observed properties](#retrieve-all-the-observed-properties)
    - [Retrieve a specific ObservedProperty](#retrieve-a-specific-observedproperty)
    - [Retrieve the ObservedProperty of a specific Datastream.](#retrieve-the-observedproperty-of-a-specific-datastream)
  - [Sensors](#sensors)
    - [Retrieve all Sensors](#retrieve-all-sensors)
    - [Retrieve a specific Sensor](#retrieve-a-specific-sensor)
    - [Retrieve the Sensor of a specific Datastream](#retrieve-the-sensor-of-a-specific-datastream)
  - [Things](#things)
    - [Retrieve all Things](#retrieve-all-things)
    - [Retrieve a specific Thing](#retrieve-a-specific-thing)
    - [Retrieve the Thing of a specific Datastream](#retrieve-the-thing-of-a-specific-datastream)
  - [Locations](#locations)
    - [Retrieve all Locations](#retrieve-all-locations)
    - [Retrieve a specific Thing](#retrieve-a-specific-thing-1)
  - [HistoricalLocations](#historicallocations)
    - [Retrieve all Locations](#retrieve-all-locations-1)
    - [Retrieve a specific Thing](#retrieve-a-specific-thing-2)


## Base Resource Path
```
https://w3id.org/iliad/api/v1.0
```
## Observations
### Retrieve all Observations
```
https://w3id.org/iliad/api/v1.0/Observations
```
### Retrieve a specific Observation
```
https://w3id.org/iliad/api/v1.0/Observations(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Observations(3-10-361-Rhopilema%2520nomadica)
```
### Retrieve Observations for a specific Datastream
```
https://w3id.org/iliad/api/v1.0/Datastreams(id)/Observations
```
For example:
```
https://w3id.org/iliad/api/v1.0/Datastreams(3-jellyFishAbundanceProperty)/Observations
```

## Datastreams
### Retrieve all the Datastreams
```
https://w3id.org/iliad/api/v1.0/Datastreams
```
### Retrieve a specific Datastream.
```
https://w3id.org/iliad/api/v1.0/Datastreams(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Datastreams(3-jellyFishAbundanceProperty)
```
### Retrieve Datastream for a specific Observation
TBD


## Features of Interest
### Retrieve all FeaturesOfInterest
```
https://w3id.org/iliad/api/v1.0/FeaturesOfInterest
```
### Retrieve a specific FeatureOfInterest
```
https://w3id.org/iliad/api/v1.0/FeaturesOfInterest(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/FeaturesOfInterest(1-18)
```
### Retrieve Observation for a specific FeatureOfInterest
```
https://w3id.org/iliad/api/v1.0/FeaturesOfInterest(id)/Observations
```
For example:
```
https://w3id.org/iliad/api/v1.0/FeaturesOfInterest(1-18)/Observations
```

## Observed properties
### Retrieve all the Observed properties
```
https://w3id.org/iliad/api/v1.0/ObservedProperties
```
### Retrieve a specific ObservedProperty
```
https://w3id.org/iliad/api/v1.0/ObservedProperties(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/ObservedProperties(jellyFishAbundanceProperty)
```
### Retrieve the ObservedProperty of a specific Datastream.
TBD

## Sensors
### Retrieve all Sensors
```
https://w3id.org/iliad/api/v1.0/Sensors
```
### Retrieve a specific Sensor
```
https://w3id.org/iliad/api/v1.0/Sensors(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Sensors(1)
```
### Retrieve the Sensor of a specific Datastream
TBD

## Things
### Retrieve all Things
```
https://w3id.org/iliad/api/v1.0/Things
```
### Retrieve a specific Thing
```
https://w3id.org/iliad/api/v1.0/Things(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Things(1)
```
### Retrieve the Thing of a specific Datastream
TBD

## Locations
### Retrieve all Locations
```
https://w3id.org/iliad/api/v1.0/Locations
```
### Retrieve a specific Thing
```
https://w3id.org/iliad/api/v1.0/Locations(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Locations(1)
```

## HistoricalLocations
### Retrieve all Locations
```
https://w3id.org/iliad/api/v1.0/HistoricalLocations
```
### Retrieve a specific Thing
```
https://w3id.org/iliad/api/v1.0/HistoricalLocations(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/HistoricalLocations(1)
```

For more information about OGC API please refer to:
* [GitHub repository](https://github.com/opengeospatial/sensorthings).
* [Test implementation](https://developers.sensorup.com/docs/#observations_get).

