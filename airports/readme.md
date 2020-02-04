# Airports

This dataset hold the name and geo-location of all main airports in the world.

Each record contains a `.geoloc` key that you can use to try our [geo-search
feature][1].

## Schema

```json
{
  "name": "Hartsfield Jackson Atlanta Intl",
  "city": "Atlanta",
  "country": "United States",
  "iata_code": "ATL",
  "_geoloc": {
    "lat": 33.636719,
    "lng": -84.428067
  },
  "links_count": 1826,
}
```

## Demo

You can see an example of what could be built with this dataset
[here][2].

## Credentials

If you want to use this data directly, you can query our API directly with those
credentials:

Application ID: 'latency'
API Key:  '6be0576ff61c053d5f9a3225e2a90f76'
Index Name: 'demo-geosearch'


[1]: https://www.algolia.com/doc/guides/searching/geo-search/
[2]: https://preview.algolia.com/geo-search/
