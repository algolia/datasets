# Wikipedia Images Dataset Documentation

This dataset contains metadata for images from Wikipedia pages along with their associated context information.

## Sample JSON and description of fields.

```json
{
    "context_page_description": "Morgan Stanley is an American multinational investment bank and financial services company headquartered at 1585 Broadway in the Morgan Stanley Building, Midtown Manhattan, New York City. With offices in more than 42 countries and more than 60,000 employees, the firm's clients include corporations, governments, institutions, and individuals. Morgan Stanley ranked No. 67 in the 2018 Fortune 500 list of the largest United States corporations by total revenue...",
    "hierarchical_section_title": "Morgan Stanley",
    "image_url": "https://upload.wikimedia.org/wikipedia/commons/6/61/Morgan-stanley-building.jpg",
    "mime_type": "image/jpeg",
    "original_height": "1600",
    "original_width": "1200",
    "page_changed_recently": "true",
    "page_title": "Morgan Stanley",
    "page_url": "https://en.wikipedia.org/wiki/Morgan_Stanley",
    "resolution": "large"
}
```

## Field Descriptions

| Field | Description |
|-------|-------------|
| context_page_description | The excerpt or summary text from the Wikipedia page where the image appears |
| hierarchical_section_title | The title of the section where the image is located within the page |
| image_url | Direct URL to the image on Wikimedia Commons |
| mime_type | The MIME type of the image file |
| original_height | Height of the original image in pixels |
| original_width | Width of the original image in pixels |
| page_changed_recently | Boolean indicator if the page has been modified recently |
| page_title | Title of the Wikipedia page |
| page_url | URL of the Wikipedia page where the image appears |
| resolution | Qualitative description of the image resolution (e.g., "large", "medium", "small") |
