`drake` for Workflow Happiness
==============================

This is an intro to the [`drake`](https://github.com/ropensci/drake)
package for data pipeling.

The talk is split into two parts: slides and a [live coding
walkthrough](https://github.com/aedobbyn/nyc-fires/blob/master/live_code.Rmd).

The live code Rmd is meant to be stepped through in an R session rather
than knit. It’s motivated by the [NYCFireWire Twitter
account](https://twitter.com/NYCFireWire) with an assist from
[Gritty](https://youtu.be/FNt0anp7WK8?t=8) at a [burner
account](https://twitter.com/didntstartit).

It relies on the [rtweet](https://github.com/mkearney/rtweet) and
[ggmap](https://github.com/dkahle/ggmap) packages, so to be able to run
it in full you’ll need a [Twitter API access
token](https://rtweet.info/articles/auth.html) and [Google Maps
Geocoding API
key](https://developers.google.com/maps/documentation/geocoding/intro#Geocoding).

All functions used in both parts live in
[`didnt_start_it.R`](https://github.com/aedobbyn/nyc-fires/blob/master/didnt_start_it.R).

The best resource on `drake` remains the [`drake`
Manual](https://ropenscilabs.github.io/drake-manual/) 😄
