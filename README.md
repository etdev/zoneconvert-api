[![Code Climate](https://codeclimate.com/github/etdev/zoneconvert/badges/gpa.svg)](https://codeclimate.com/github/etdev/zoneconvert)  [![Build Status](https://circleci.com/gh/etdev/zoneconvert.svg?&style=shield&circle-token=12036235fb756d54fc438f47e0ca70ea6c08dc07)](https://circleci.com/gh/etdev/zoneconvert)

# ZoneConvert API
Sinatra API for [Zoneconvert](https://github.com/etdev/zoneconvert), a simple tool for converting a date/time from one time zone to another.  Answers the question "I want to remember to do X at 8:00PM Tokyo time, but what time is that for me, here in Los Angeles?"

# API Info
Requires both Google Maps and Mapquest API keys.  Store the following data in ``api/geocode.yml``

```yaml
data:
  - base_url_mq: "http://open.mapquestapi.com/geocoding/v1/address"
  - base_url_g: "https://maps.googleapis.com/maps/api/geocode/json"
  - api_key_mq: "<Your mapquest api key>"
  - api_key_g: "<Your google api key>"
```
