# Upload from Ionic directly to DigitalOcean Spaces via AWS JS SDK

## Status: Not yet functional

## Ideal Use Case
Upload directly into spaces, then pass the file url to our backend to move to a permanent "bucket" / space.

## Issues:
* CORS configuration on DigitalOcean Spaces doesn't allow for upload from browser
* API Key/Secret doesn't seem to be specific to a single bucket/space. This means that even if we do manage to get the upload working, we won't be able to move the file to a secret location later.
