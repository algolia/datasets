# Podcast Dataset Documentation

podcasts.json contains 43831 podcast in english language.

## Sample JSON and description of fields.

```JSON
{
    "url": "https://feeds.megaphone.fm/WMHY2232473209",
    "title": "CNN 10",
    "lastUpdate": "2025-05-24T10:49:28+00:00",
    "link": "https://www.cnn.com/audio",
    "itunesId": 1766786641,
    "originalUrl": "https://feeds.megaphone.fm/WMHY2232473209",
    "itunesAuthor": "CNN Audio",
    "itunesOwnerName": "CNN",
    "explicit": false,
    "imageUrl": "https://megaphone.imgix.net/podcasts/642870d2-5a7b-11ef-a320-db1aac295786/image/e8eb2af686ee4473dca257657d185647.jpg?ixlib=rails-4.3.1&max-w=3000&max-h=3000&fit=crop&auto=format,compress",
    "itunesType": "episodic",
    "generator": "",
    "newestItemPubdate": "2025-05-23T13:19:00+00:00",
    "language": "English",
    "oldestItemPubdate": "2024-08-19T14:34:39+00:00",
    "episodeCount": 173,
    "popularityScore": 9,
    "createdOn": "2024-09-19T21:02:39+00:00",
    "updateFrequency": 1,
    "host": "megaphone.fm",
    "newestEnclosureUrl": "https://www.podtrac.com/pts/redirect.mp3/chrt.fm/track/E31CC9/traffic.megaphone.fm/WMHY7897171496.mp3?updated=1747838403",
    "description": "<p>Explaining global news to a global audience: This is the mission of CNN 10, a 10-minute educational news show that appears as a daily digital video and audio podcast. CNN 10 serves a growing audience interested in compact on-demand news broadcasts ideal for explanation seekers on the go or in the classroom.</p>",
    "newestEnclosureDuration": 665,
    "objectID": "2611a6e5-d996-5bef-9c23-ad2f02bcf785",
    "categories": [
        "education",
        "news",
        "daily"
    ],
    "IsActive": true,
    "itunesLink": "https://itunes.apple.com/lookup?id=1766786641"
}
```

Below table describes the fields belonging to single entry of podcast in `podcasts.json` file.

| Field Name               | Type      | Description                                                                                                    | Example Value                                                                                                   |
|--------------------------|-----------|----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| url                      | string    | The RSS feed URL of the podcast.                                                                               | https://feeds.megaphone.fm/WMHY2232473209                                                                       |
| title                    | string    | The title of the podcast.                                                                                      | CNN 10                                                                                                          |
| lastUpdate               | string    | The ISO 8601 timestamp of the last update to the podcast metadata.                                             | 2025-05-24T10:49:28+00:00                                                                                       |
| link                     | string    | The website or landing page for the podcast.                                                                   | https://www.cnn.com/audio                                                                                       |
| itunesId                 | integer   | The unique iTunes podcast ID.                                                                                  | 1766786641                                                                                                      |
| originalUrl              | string    | The original RSS feed URL (may be same as `url`).                                                              | https://feeds.megaphone.fm/WMHY2232473209                                                                       |
| itunesAuthor             | string    | The author as listed in iTunes.                                                                                | CNN Audio                                                                                                       |
| itunesOwnerName          | string    | The owner name as listed in iTunes.                                                                            | CNN                                                                                                             |
| explicit                 | boolean   | Whether the podcast contains explicit content.                                                                 | false                                                                                                           |
| imageUrl                 | string    | URL to the podcast's cover image.                                                                              | https://megaphone.imgix.net/podcasts/642870d2-5a7b-11ef-a320-db1aac295786/image/e8eb2af686ee4473dca257657d185647.jpg |
| itunesType               | string    | The type of podcast (e.g., episodic, serial).                                                                  | episodic                                                                                                        |
| generator                | string    | The software used to generate the feed (may be empty).                                                         | ""                                                                                                              |
| newestItemPubdate        | string    | ISO 8601 timestamp of the newest episode's publication date.                                                   | 2025-05-23T13:19:00+00:00                                                                                       |
| language                 | string    | The language of the podcast.                                                                                   | English                                                                                                         |
| oldestItemPubdate        | string    | ISO 8601 timestamp of the oldest episode's publication date.                                                   | 2024-08-19T14:34:39+00:00                                                                                       |
| episodeCount             | integer   | Total number of episodes in the feed.                                                                          | 173                                                                                                             |
| popularityScore          | integer   | A score representing the podcast's popularity (scale may vary).                                                | 9                                                                                                               |
| createdOn                | string    | ISO 8601 timestamp when this podcast entry was created in the dataset.                                         | 2024-09-19T21:02:39+00:00                                                                                       |
| updateFrequency          | integer   | Estimated update frequency (e.g., episodes per week).                                                          | 1                                                                                                               |
| host                     | string    | The hosting platform or domain.                                                                                | megaphone.fm                                                                                                    |
| newestEnclosureUrl       | string    | URL to the audio file of the newest episode.                                                                   | https://www.podtrac.com/pts/redirect.mp3/chrt.fm/track/E31CC9/traffic.megaphone.fm/WMHY7897171496.mp3?updated=1747838403 |
| description              | string    | HTML or plain text description of the podcast.                                                                 | Explaining global news to a global audience...                                                                  |
| newestEnclosureDuration  | integer   | Duration of the newest episode in seconds.                                                                     | 665                                                                                                             |
| objectID                 | string    | Unique identifier for the podcast entry in the dataset.                                                        | 2611a6e5-d996-5bef-9c23-ad2f02bcf785                                                                            |
| categories               | array     | List of categories or tags for the podcast.                                                                    | ["education", "news", "daily"]                                                                                  |
| IsActive                 | boolean   | Whether the podcast is currently active.                                                                       | true                                                                                                            |
| itunesLink               | string    | Direct link to the podcast on iTunes.                                                                          | https://itunes.apple.com/lookup?id=1766786641                                                                   |
