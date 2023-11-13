# E-commerce (10 000 records)

The files in this repository holds a list of the most commonly bought items on
Bestbuy. You can use this dataset to see how Algolia would improve the search
workflow of your e-commerce website.

```json
{
  "name": "TomTom - GO 500 5\" GPS with Lifetime Map and Traffic Updates",
  "shortDescription": "Preloaded base maps of the U.S., Puerto Rico, Canada and Mexico; 5\" capacitive touch screen; text-to-speech voice guidance; lifetime map and traffic updates",
  "bestSellingRank": 9316,
  "thumbnailImage": "http://img.bbystatic.com/BestBuy_US/images/products/1502/1502983_s.gif",
  "salePrice": 249.99,
  "manufacturer": "TomTom",
  "url": "http://www.bestbuy.com/site/tomtom-go-500-5-gps-with-lifetime-map-and-traffic-updates/1502983.p?id=1219052962668&skuId=1502983&cmp=RMX&ky=2d3GfEmNIzjA0vkzveHdZEBgpPCyMnLTJ",
  "type": "HardGood",
  "image": "http://img.bbystatic.com/BestBuy_US/images/products/1502/1502983_sc.jpg",
  "customerReviewCount": 4,
  "shipping": "Free shipping",
  "salePrice_range": "201 - 500",
  "objectID": "1502983",
  "categories": [
    "Portable GPS"
  ]
}
```

## Query suggestions (2120 records)

```json
{
  "instant_search": {
    "exact_nb_hits": 59,
    "facets": {
      "exact_matches": {
        "categories": [
          {
            "value": "Cell Phones",
            "count": 57
          },
          {
            "value": "All Cell Phones with Plans",
            "count": 42
          }
        ],
        "hierarchicalCategories.lvl0": [
          {
            "value": "Cell Phones",
            "count": 57
          }
        ],
        "hierarchicalCategories.lvl1": [
          {
            "value": "Cell Phones > All Cell Phones with Plans",
            "count": 42
          }
        ],
        "hierarchicalCategories.lvl2": [
          {
            "value": "Cell Phones > Prepaid Phones > All Prepaid Phones",
            "count": 3
          }
        ]
      },
      "analytics": {
        "categories": [
          {
            "attribute": "categories",
            "operator": ":",
            "value": "Cell Phones",
            "count": 1
          }
        ],
        "hierarchicalCategories.lvl0": [],
        "hierarchicalCategories.lvl1": [],
        "hierarchicalCategories.lvl2": []
      }
    }
  },
  "nb_words": 2,
  "popularity": 5,
  "query": "iphone 8",
  "objectID": "iphone 8"
}
```

## Live demo

You can see a live demo of this dataset [here][1].

## Credentials

To use the dataset directly, without pushing it your application,
just use the following credentials:

Application ID: 'latency'
API Key: '6be0576ff61c053d5f9a3225e2a90f76'
Index name: 'instant_search'


[1]: https://preview.algolia.com/instantsearch/
