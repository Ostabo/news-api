# news-api

This Repo caches top headlines from newsapi.org  
Find the list of available countries <ins>[here](https://ostabo.software/news-api/)</ins>

This is updated every 2 hours.
Note that GitHub Actions will be delayed, depending on current load. Therefore, updates don't come in exactly at the top of the hour.

## Usage

```
GET https://ostabo.software/news-api/{country-code}/data.json

GET https://ostabo.software/news-api/us/data.json --> US
```
