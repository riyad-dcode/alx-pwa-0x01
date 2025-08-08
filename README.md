## API Overview

The api provides a complete and updated data for over 9 million movies, series and episodes and 11 million actors / crew and cast members. Collection of information for movies, tv-shows, actors. Including youtube trailer url, awards, full biography, and many other usefull informations.

## API Version

v1

## Available Endpoints

Titles: returns array of titles
Search: returns array of titles according to query parameters and keyword provided in path
Actors: returns array of actors according to filters provided
Utils: returs array of specific queries

## Request and Response Format

base_info: request basic informations about a movie or series
response: titleText: ... , id: ... , primaryImage: ... , titleType: ... , releaseDate: ... , genres: ... , runtime: ... , plot: ... , meterRanking: ... , ratingsSummary: ... , episodes: ... , series: ...

## Authentication

API Key and hostname is required to authenticate data access

## Error Handling

Use try catch to handle error resulting API request

## Usage Limits and Best Practices

10000 requests/hour
