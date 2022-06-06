# Ecommerce Federated

The files in this folder contain products (with query suggestions), articles, and FAQ records as you would see in a federated search experience.

## Live demo

You can see a live demo of this dataset [here](https://codesandbox.io/s/github/algolia/autocomplete/tree/next/examples/two-column-layout).

## Structure

### Products index

This index contains **fashion products**.

You can find the records, settings and rules here:

- [`products.json`](./products.json)
- [`products_settings.json`](./products_settings.json)
- [`products_rules.json`](./products_rules.json)

#### Product query suggestions index

This index contains **query suggestions for products**.

You can find the records and settings here:

- [`products_query_suggestions.json`](./products_query_suggestions.json)
- [`products_query_suggestions_settings.json`](./products_query_suggestions_settings.json)

#### Articles index

This index contains fake **articles** related to some product brands.

You can find the records in the [`articles.json` file](./articles.json).

#### FAQ index

This index contains fake **FAQ**.

You can find the records in the [`faq.json` file](./faq.json).

## Credentials

If you want to use the dataset directly, without pushing it your application,
just use the following credentials:

Application ID: `latency`  
API Key: `6be0576ff61c053d5f9a3225e2a90f76`

Index names:
  - `autocomplete_demo_products`
  - `autocomplete_demo_products_query_suggestions`
  - `autocomplete_demo_articles`
  - `autocomplete_demo_faq`
