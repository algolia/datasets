# Ecommerce Federated

This dataset collection contains products (with [Query Suggestions](https://www.algolia.com/doc/guides/building-search-ui/ui-and-ux-patterns/query-suggestions/react/)), articles, and FAQ records as you would see in a federated search experience.

You can see a live demo using this dataset [here](https://codesandbox.io/s/github/algolia/autocomplete/tree/next/examples/two-column-layout) and learn how those dataset are put in motion in the ["Ecommerce federated guide"](https://www.algolia.com/doc/ui-libraries/autocomplete/guides/creating-an-advanced-ecommerce-experience/).

## Structure

### Products index

This index contains **fashion products.**

You can find the records and configuration (settings and [Rules](https://www.algolia.com/doc/guides/managing-results/rules/rules-overview/)) here:

- [`products.json`](./products.json)
- [`products_configuration.json`](./products_configuration.json)

#### Query Suggestions index

This index contains **Query Suggestions for products.**

You can find the records and configuration here:

- [`products_query_suggestions.json`](./products_query_suggestions.json)
- [`products_query_suggestions_configuration.json`](./products_query_suggestions_configuration.json)

#### Articles index

This index contains **articles related to some product brands.**

You can find the records in the [`articles.json` file](./articles.json).

#### FAQ index

This index contains **frequently asked questions.**

You can find the records in the [`faq.json` file](./faq.json).

## Import to your Algolia app

Please refer to the guide [Exporting and Importing Algolia Indices](https://www.algolia.com/doc/guides/sending-and-managing-data/manage-your-indices/how-to/export-an-algolia-index/) in order to learn how to import the data into your Algolia application.

## Credentials

If you want to use the dataset directly without pushing it to your own application, you can use the following credentials:

- Application ID: `latency`  
- API key: `6be0576ff61c053d5f9a3225e2a90f76`

Index names:
  - `autocomplete_demo_products`
  - `autocomplete_demo_products_query_suggestions`
  - `autocomplete_demo_articles`
  - `autocomplete_demo_faq`
