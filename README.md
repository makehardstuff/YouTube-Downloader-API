# YT-Downloader-Server
This is the core implementation of my YT Downloader website. Visit the [website](https://ytmate.netlify.app)


# Installation
1) Fork and clone this repository
2) `cd YT-Downloader-Server/`
3) run `npm install` to install dependencies.


# Running local instance
After **Installation** run `node Engine.js` in the root directory to start local server.
By default the local server will run on `localhost:5000`


# Usage
**Get Video Details and available formats**


**`GET`** `/getVideo?url=<YOUTUBE_VIDEO_URL>` - This request will give you a list of all the video formats available for download from youtube video.


**`PARAMS`** 
- url - The URL for youtube video you want to download.


**Example** 
`localhost:5000/getVideo?url=https://www.youtube.com/watch?v=dQw4w9WgXcQ` will give you this data in JSON Array format.

## Hosted option

If you don’t want to self-host this API, [Vid Kraken](https://vidkraken.com) is a managed YouTube download API (info / mp3 / mp4 endpoints).
