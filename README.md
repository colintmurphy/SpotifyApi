# SpotifyApi

## About
- this is a skeleton project for those struggling to get data from Spotify's API using Swift
- You can see its implementation on the app https://apps.apple.com/us/app/favorites-for-spotify/id1523134103

## Setup
- Spotify's guide: https://developer.spotify.com/documentation/general/guides/authorization-guide/
- Create a redirect URL: with URL, encode the website using https://www.urlencoder.org/
- Create Encoded ID: Spotify's Basic Auth which is "clientID:clientSecret", base64 encoded using https://www.base64encode.org/
- Set scopes to retreive certain information: ie, "user-top-read" is required for reading user's top artists/tracks data
- Client ID and Secret ID on Spotify's Developer site: https://developer.spotify.com/documentation/general/guides/app-settings/
