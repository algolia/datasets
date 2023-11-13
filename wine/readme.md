# Wine (1024 records)

This directory contains the list of all Bordeaux wine, in case you want to do
a search on wine.

It was extracted from [Totalwine.com][1].

```json
{
  "name": "Chateau Brane Cantenac",
  "year": 2009,
  "type": "red",
  "domain": "Margaux",
  "quantity": 750,
  "price": 84,
  "quality": 95,
  "image": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGYAAA..."
}
```

## Live demo

You can see a live demo using this dataset at [wine-search.now.sh][2], and more information on how it was built at [this repository][3].

## Credentials

To directly target the index without pushing it to your own
application, you can use the following credentials:

Application ID: '1AWHE68HXJ'
API Key: '6629baea240a4d197e7c8fe6df069037'
Index name: 'wine-search'

[1]: http://www.totalwine.com
[2]: https://wine-search.now.sh
[3]: https://github.com/algolia/hack-bdx
