# Public datasets

Welcome to the Algolia repository of datasets.

The goal of this repository is to help you build something with Algolia, even
if you don't have data of your own. Maybe you just want to try the API, or
maybe you got inspired by some of those datasets to build something of your
own.

## What you'll find in this repository

### Ready-made indices

Each directory of the repository holds `json` files that contains both the
actual records and the index configuration. You can use them to push data to
your own application on configure your settings through the API.

Most of them also come with credentials to directly query this data from our
servers. In that case you won't need to push anything, but you will also be
limited to querying as the API key we share only allows reading data, not
updating it.

### Links to publicly available raw datasets

But there is much more data out there than what is in those files. That's what
we've compiled a list of interesting potential datasources. They will each
come in their own format (sometime a `zip` file to download, sometimes an API
to query).

They're here to give you ideas a of what you could build with Algolia. If you
ever build something with any of those datasources, let us known, we'd love to
see what you did. If you ever know of another good data source, we're open to
Pull Requests as well :)

#### Academic Papers

http://academictorrents.com/

15.49TB of research data available on torrent format

#### Archive.org

https://archive.org/

Non-profit library of millions of free books, movies, software, music, and websites.

#### Amazon

https://aws.amazon.com/datasets/

Datasets publicly hosted on AWS and available. Including population of Japan,
Wikipedia page traffic, metadata about a million songs, social graph of Marvel
Super-Heroes, Open StreetMap and much more.

#### Awesome JSON Datasets

https://github.com/jdorfman/awesome-json-datasets

A curated list of awesome JSON datasets that don't require authentication. It
has a lot of choice, from food to gaming to quotes. Some links may be outdated.

#### Awesome Public Datasets

https://github.com/awesomedata/awesome-public-datasets

Another extensive list of links to various datasets and APIs.

#### APIs

Here is a Gist referencing curated APIs that would contain interesting data
https://gist.github.com/soopa/8225112

And a dedicated repo: https://github.com/toddmotto/public-apis

#### CommonCrawl

http://commoncrawl.org/

7 years of crawled data on the web, million of pages and trillions of links
between them. Sort of an open source Google index

#### Gallica

http://gallica.bnf.fr/

French National Library (BNF) online archives.
Books, maps, press

#### IMDB

http://www.imdb.com/interfaces

List of all actors, movies, shows, etc from IMDB.

#### Kaggle

https://www.kaggle.com/datasets

Large list of datasets for machine learning

#### Marvel

- https://github.com/pixelastic/marvel/tree/master/records
- https://community.algolia.com/marvel-search/

List of all super-heroes and super villains of the Marvel universe. Extracted
from sources (Wikipedia, [Marvel API](http://developer.marvel.com/),
[DBPedia](http://wiki.dbpedia.org/) and aggregated in Algolia records.

#### N-grams

http://commondatastorage.googleapis.com/books/syntactic-ngrams/index.html

List of n-grams extracted from the Google Books corpus. Not a regular dataset,
but still worth noting.

#### OpenStreetMap

http://wiki.openstreetmap.org/wiki/Downloading_data

Open source alternative to Google Maps. Geolocated point of interestes, streets,
etc.

#### Project Gutemberg

https://www.gutenberg.org/

Public domain books, available as both HTML and ebooks. They do not all follow
the same format, so custom parsing is needed.

#### Photography

https://github.com/pixelastic/landscapes-data/tree/master/data/earthporn

All landscape photography published on
[r/earthporn](https://www.reddit.com/r/earthporn) up until Dec 12th, 2022.
Includes popularity and LQIP (low quality image placeholder).

#### Public APIs

https://github.com/public-apis-dev/public-apis
https://publicapis.dev/

A collaborative list of public APIs for developers. Be careful not to use the
deprecated [public-apis/public-apis](https://github.com/public-apis/public-apis)
repository (see [this issue for details](https://github.com/public-apis/public-apis/issues/3104))


#### Vogue

http://dh.library.yale.edu/projects/vogue/

All issues of the Vogue magazine, from 1892 to 2016. Including covers and pages.
About 6TB of data.

#### Wikipedia

https://dumps.wikimedia.org/

Downloadable extracts of Wikipedia. In Wikitext, with metadata as embedded XML.
