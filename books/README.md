# Books Dataset

The books.json is a subset from the openlibrary [books datasets](https://openlibrary.org/developers/dumps)

## Sample JSON and description of fields.

```JSON
  {
    "author": "editors, Naila Kabeer, Geetha B. Nambissan, Ramya Subrahmanian.",
    "book_url": "https://openlibrary.org//books/OL18767739M",
    "by_statement": "editors, Naila Kabeer, Geetha B. Nambissan, Ramya Subrahmanian.",
    "contributions": [
      "Kabeer, Naila.",
      "Nambissan, Geetha B., 1955-",
      "Subrahmanian, Ramya."
    ],
    "cover_image_url": "https://covers.openlibrary.org/b/id/5439666-L.jpg",
    "covers": [
      5439666,
      5439528,
      5435087,
      5434954,
      5003991,
      4710652
    ],
    "created": "2008-10-19T12:53:34.198322",
    "description": {
      "type": "/type/text",
      "value": "Papers presented at the Workshop: Needs vs. Rights? : Social Policy from a Child-Centred Perspective, held in New Delhi in July 1999; with special reference to India and Bangladesh."
    },
    "dewey_decimal_class": [
      "379.2/6/0954"
    ],
    "genres": [
      "Congresses."
    ],
    "isbn_10": [
      "076199601X",
      "0761996257"
    ],
    "language": [
      "eng"
    ],
    "last_modified": "2023-11-15T19:45:13.669787",
    "latest_revision": 12,
    "notes": {
      "type": "/type/text",
      "value": "\"This book is the outcome of a workshop 'Needs vs. Rights? Social Policy from a Child Centred Perspective' held in New Delhi in July 1999\"--Pref.\n\nIncludes bibliographical references and index."
    },
    "number_of_pages": 412,
    "objectID": "2283384001",
    "publish_country": "ii ",
    "publish_date": 2032,
    "publish_places": [
      "New Delhi",
      "Thousand Oaks, Calif"
    ],
    "publishers": [
      "Sage Publications"
    ],
    "subjects": [
      "Educational equalization -- India -- Congresses.",
      "Educational equalization -- Bangladesh -- Congresses.",
      "Child labor -- India -- Congresses.",
      "Child labor -- Bangladesh -- Congresses.",
      "Children's rights -- India -- Congresses.",
      "Children's rights -- Bangladesh -- Congresses."
    ],
    "subtitle": "needs versus rights?",
    "title": "Child labour and the right to education in South Asia"
  }
```

| Field Name | Description | Example Value |
| :--- | :--- | :--- |
| **author** | The individual(s) credited with creating the book, often the editors in this case. | editors, Naila Kabeer, Geetha B. Nambissan, Ramya Subrahmanian. |
| **book_url** | The web address for the book's page on the Open Library website. | [https://openlibrary.org//books/OL18767739M](https://openlibrary.org//books/OL18767739M) |
| **by_statement** | A formal statement attributing authorship or editorship. | editors, Naila Kabeer, Geetha B. Nambissan, Ramya Subrahmanian. |
| **contributions** | A list of all individuals who contributed to the work. | Kabeer, Naila. |
| **cover_image_url** | The URL for the large version of the book's cover image. | [https://covers.openlibrary.org/b/id/5439666-L.jpg](https://covers.openlibrary.org/b/id/5439666-L.jpg) |
| **covers** | A list of internal identification numbers for different versions of the book's cover art. | 5439666 |
| **created** | The timestamp indicating when the record for this book was first created. | 2008-10-19T12:53:34.198322 |
| **description** | A brief summary or context for the book's content. | Papers presented at the Workshop... |
| **dewey_decimal_class** | The book's classification number in the Dewey Decimal Classification system. | 379.2/6/0954 |
| **genres** | The category or style of the publication. | Congresses. |
| **isbn_10** | A list of the 10-digit International Standard Book Numbers associated with the book. | 076199601X |
| **language** | The primary language the book is written in. | eng |
| **last_modified** | The timestamp of the most recent update to the book's record. | 2023-11-15T19:45:13.669787 |
| **latest_revision** | The version number of the book's record. | 12 |
| **notes** | Additional information about the book's origin or content. | "This book is the outcome of a workshop..." |
| **number_of_pages** | The total page count of the book. | 412 |
| **objectID** | A unique identifier for the object in the database. | 2283384001 |
| **publish_country** | The country where the book was published. | ii |
| **publish_date** | The year the book was published. | 2032 |
| **publish_places** | The cities where the book was published. | New Delhi |
| **publishers** | The company or companies that published the book. | Sage Publications |
| **subjects** | A list of topics and themes covered in the book. | Educational equalization -- India -- Congresses. |
| **subtitle** | The secondary or explanatory title of the book. | needs versus rights? |
| **title** | The main title of the book. | Child labour and the right to education in South Asia |