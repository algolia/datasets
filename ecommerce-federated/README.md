# E-commerce Federated

This dataset collection contains products (with [Query Suggestions](https://www.algolia.com/doc/guides/building-search-ui/ui-and-ux-patterns/query-suggestions/react/)), articles, and FAQ records as you would see in a federated search experience.

You can see a live demo using this dataset [here](https://codesandbox.io/s/github/algolia/autocomplete/tree/next/examples/two-column-layout) and learn how those dataset are put in motion in the ["e-commerce federated guide"](https://www.algolia.com/doc/ui-libraries/autocomplete/guides/creating-an-advanced-ecommerce-experience/).

## Structure

### Products index (1787 records)

This index contains **fashion products.**

You can find the records and configuration (settings and [Rules](https://www.algolia.com/doc/guides/managing-results/rules/rules-overview/)) here:

- [`products.json`](./products.json)
- [`products_configuration.json`](./products_configuration.json)

#### Product schema

<details>
  <summary>Product schema (click to expand)
  ```json
{
  "available_sizes": [
    "one size"
  ],
  "brand": "Gabs",
  "category_page_id": [
    "Women > Bags",
    "Women > Bags > Wallets"
  ],
  "color": {
    "filter_group": "multicolor;https://res.cloudinary.com/hilnmyskv/image/upload/v1639065885/flagship_sunrise/color_wheel.svg",
    "original_name": "multi"
  },
  "created_at": 0,
  "description": "High-quality and special wallets from Gabs. The Italian Designer Franco Gabbrielli designs must haves for the modern and self-confident woman. This wallets surprise through smart designs and esthetic highlights.",
  "gender": "women",
  "hierarchical_categories": {
    "lvl0": "Women",
    "lvl1": "Women > Bags",
    "lvl2": "Women > Bags > Wallets"
  },
  "image_blurred": "LNSY]gV@%Nof_4ozMxafMxf7ofay",
  "image_urls": [
    "https://res.cloudinary.com/hilnmyskv/image/upload/v1638371371/flagship_sunrise/A0E200000002BGZ_0.jpg",
    "https://res.cloudinary.com/hilnmyskv/image/upload/v1638371372/flagship_sunrise/A0E200000002BGZ_1.jpg",
    "https://res.cloudinary.com/hilnmyskv/image/upload/v1638371373/flagship_sunrise/A0E200000002BGZ_2.jpg"
  ],
  "list_categories": [
    "Women",
    "Bags",
    "Wallets"
  ],
  "name": "Gabs – Wallet “Gmoney”",
  "objectID": "A0E200000002BGZ",
  "parentID": "GMON17STUDIO",
  "price": {
    "currency": "EUR",
    "discount_level": -100,
    "discounted_value": 0,
    "on_sales": false,
    "value": 106.25
  },
  "product_type": "Wallets",
  "related_products": [
    {
      "available_sizes": [
        "one size"
      ],
      "brand": "Gabs",
      "category_page_id": [
        "Women > Bags",
        "Women > Bags > Wallets"
      ],
      "color": {
        "filter_group": "multicolored;#http://",
        "original_name": "multi"
      },
      "created_at": 0,
      "description": "High-quality and special wallets from Gabs. The Italian Designer Franco Gabbrielli designs must haves for the modern and self-confident woman. This wallets surprise through smart designs and esthetic highlights.",
      "gender": "women",
      "hierarchical_categories": {
        "lvl0": "Women",
        "lvl1": "Women > Bags",
        "lvl2": "Women > Bags > Wallets"
      },
      "i18n": null,
      "image_blurred": "LZR:4,WA%fkD_NkDMxjYMyj@oyWV",
      "image_urls": [
        "https://res.cloudinary.com/hilnmyskv/image/upload/v1638370878/flagship_sunrise/A0E200000002BFW_0.jpg",
        "https://res.cloudinary.com/hilnmyskv/image/upload/v1638370879/flagship_sunrise/A0E200000002BFW_1.jpg",
        "https://res.cloudinary.com/hilnmyskv/image/upload/v1638370880/flagship_sunrise/A0E200000002BFW_2.jpg"
      ],
      "list_categories": [
        "Women",
        "Bags",
        "Wallets"
      ],
      "name": "Gabs – Wallet “Gmoney”",
      "objectID": "A0E200000002BFW",
      "parentID": "GMON17STUDIO",
      "price": {
        "currency": "EUR",
        "discount_level": -100,
        "discounted_value": 0,
        "on_sales": false,
        "value": 106.25
      },
      "related_products": null,
      "reviews": {
        "bayesian_avg": 0.972972972972973,
        "count": 36,
        "rating": 1
      },
      "sku": "A0E200000002BFW",
      "slug": "gabs-wallet-GMON17STUDIO-162-multi",
      "units_in_stock": 0,
      "updated_at": 0,
      "url": "",
      "variants": [
        {
          "abbreviated_size": "one size",
          "in_stock": true,
          "sku": "A0E200000002BFW"
        }
      ]
    }
  ],
  "reviews": {
    "bayesian_avg": 1.955555555555556,
    "count": 44,
    "rating": 2
  },
  "sku": "A0E200000002BGZ",
  "slug": "gabs-wallet-GMON17STUDIO-182-multi",
  "units_in_stock": 0,
  "updated_at": 0,
  "variants": [
    {
      "abbreviated_size": "one size",
      "in_stock": true,
      "sku": "A0E200000002BGZ"
    }
  ]
}

  ```
</details>

### Query Suggestions index (713 records)

This index contains **Query Suggestions for products.**

You can find the records and configuration here:

- [`products_query_suggestions.json`](./products_query_suggestions.json)
- [`products_query_suggestions_configuration.json`](./products_query_suggestions_configuration.json)

#### Query suggestion schema

<details>
  <summary>Query suggestion schema (click to expand)
  ```json
{
  "autocomplete_products": {
    "exact_nb_hits": 6,
    "facets": {
      "analytics": {
        "hierarchical_categories.lvl0": [],
        "hierarchical_categories.lvl1": []
      },
      "exact_matches": {
        "hierarchical_categories.lvl0": [
          {
            "count": 6,
            "value": "Accessories"
          }
        ],
        "hierarchical_categories.lvl1": [
          {
            "count": 6,
            "value": "Accessories > Women"
          }
        ]
      }
    }
  },
  "hierarchical_categories.lvl0": [
    "Accessories"
  ],
  "hierarchical_categories.lvl1": [
    "Accessories > Women"
  ],
  "nb_words": 3,
  "objectID": "multi altea women",
  "popularity": 0,
  "query": "multi altea women"
}
  ```
</details>

### Articles index (99 records)

This index contains **articles related to some product brands.**

You can find the records in the [`articles.json` file](./articles.json).

```json
{
  "date": "2021-01-31T23:00:00.000Z",
  "image_url": "https://media.istockphoto.com/photos/online-shopping-and-fashion-store-website-with-add-to-cart-button-in-picture-id1287186681?b=1&k=20&m=1287186681&s=170x170&h=94ANJ0PdHLaEx0IXmsBGvBAoE8KBFQLWCVmv1V6YJW8=",
  "objectID": "94",
  "title": "Review: Regi A. Spring 2021 collection"
}
```

### FAQ index (15 records)

This index contains **frequently asked questions.**

You can find the records in the [`faq.json` file](./faq.json).

```json
{
  "description": "<b><p>Id sit fugiat aliquip.</p></b><p>Exercitation eiusmod cupidatat reprehenderit est exercitation cupidatat dolor adipisicing. Nulla incididunt eu pariatur cillum ut id quis dolor pariatur ad ullamco et. Aliqua cupidatat adipisicing sunt aute aliquip ut aliquip ullamco incididunt minim est. Nostrud pariatur anim occaecat est anim reprehenderit voluptate ipsum labore labore. Pariatur ad sint culpa exercitation consectetur do ea in qui fugiat labore laborum.</p>
<p>Nulla nulla ut tempor dolor consequat. Laboris ut magna qui nulla. Duis nostrud labore quis ea pariatur dolor exercitation magna laboris elit esse ut aliquip dolore. Ea officia eiusmod incididunt laborum aliqua Lorem proident laborum officia eu voluptate ex. In tempor mollit amet est eu nostrud nisi proident sint voluptate irure tempor velit elit aute. Reprehenderit id ut ipsum amet labore officia tempor quis nulla mollit aliqua. Qui minim fugiat duis ea reprehenderit cupidatat.</p><i><p>Minim eu nisi officia irure tempor ipsum labore sunt duis reprehenderit. Adipisicing minim reprehenderit non. Incididunt elit laboris ipsum. Dolor ea commodo do aliqua nulla eiusmod enim laboris est veniam nulla excepteur eu. Consequat ipsum veniam id tempor Lorem veniam sunt culpa pariatur tempor amet.</p></i>",
  "list_categories": [
    "account",
    "actions"
  ],
  "objectID": "8",
  "title": "Change my password"
}
```

## Import to your Algolia app

Please refer to the guide [Exporting and Importing Algolia Indices](https://www.algolia.com/doc/guides/sending-and-managing-data/manage-your-indices/how-to/export-an-algolia-index/) to learn how to import the data into your Algolia application.

## Credentials

To use the dataset directly without pushing it to your own application, you can use the following credentials:

- Application ID: `latency`  
- API key: `6be0576ff61c053d5f9a3225e2a90f76`

Index names:
  - `autocomplete_demo_products`
  - `autocomplete_demo_products_query_suggestions`
  - `autocomplete_demo_articles`
  - `autocomplete_demo_faq`
