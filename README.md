[![CircleCI](https://circleci.com/gh/bndw/wifi-card.svg?style=svg)](https://circleci.com/gh/bndw/wifi-card)

# WiFi Card

Print a neat little card with your WiFi info and stick it on the fridge.

It looks like this:

<img width=400 src="https://user-images.githubusercontent.com/4248167/83356910-05361c00-a31e-11ea-8735-95852b82ddcf.png">

## Running locally

Run the latest Docker image on http://localhost:8080

```
docker run --rm -p 8080:80 bndw/wifi-card:latest
```

Or run the live-reload server on http://localhost:8080

```
make dev
```
