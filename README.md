# Random Nature Cam

# https://tranquilmarmot.github.io/random-nature-cam

This repo is just an `index.html` that has a script that hits https://explore.org/'s (undocumented) API to get a list of webcams.

It them chooses a random webcam and sets the body of the page to be just a YouTube stream of that webcam.

## Optional Query Params

### `refreshInterval`

Time, in milliseconds, to wait between choosing a different random feed.

**Default:** 65000 (every minute-ish)

### `camGroupId`

`camGroupId` query parameter can be used to choose which cam group to grab a camera from.

(You'll have to reverse-engineer explore.org's API calls to figure out new cam group ids)

**Default:** 79 ("currently-live")
