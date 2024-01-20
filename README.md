# youtube-uploader
Support for [video-group-merger](https://github.com/mnbvmnbv2/)

---

It was moved to this separate repo for clarity.

- Supports chunked upload
- You need to setup youtube api credentials: https://console.cloud.google.com/apis/credentials
- Both OAuth and API keys need to be placed in /Keys folder
- You must enable YouTube Data API v3 in the API project you create

I have encountered that the youtube API is limiting both in number of uploads and authentication
(4 instead of 10 per day with manual upload, and you steed need to authenticate per video anyway).