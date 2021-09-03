# NYC Events

JSON compilation of free and low-cost events in NYC. Events have been pulled from the following sources:

* [NYC Parks](https://www.nycgovparks.org)
* [NYPL](https://www.nypl.org)

## Get the Data

The events data can be accessed in 2 ways:

1. Download a zip of this repo and start using the `events.json`
2. Using the link below for the events JSON served thru a CDN with jsDelivr

https://cdn.jsdelivr.net/gh/kimpenguin/nyc-events-json/events.json

## Update Frequency

TBD depending on usage.

## Tech Details

The events have been parsed from RSS feeds, cleaned, and standardized. The code to generate the data was written in python and could be deployed as a serverless function.