> A data analytics assignment I did at Monash University. View the Dashboard [here](https://charts.kal.im)

## Chart Toppers

### What the ARIA charts and Hottest 100 say about Australia's changing music tastes

Music charts around the world give insights into the ever changing music tastes of the population which they represent. In Australia, the [Australian Recording Industry Association](https://www.aria.com.au/) (ARIA) have been publishing weekly rankings of tracks and albums selling in the Australian market under the name of the **ARIA Charts** since 1970. [Triple J](https://www.abc.net.au/triplej/), a national Australian radio station intended to appeal to listeners of alternative music, also host an annual ranking event titled the **Triple J Hottest 100**, a vote-driven chart of the 100 most popular songs amongst its listeners. 

Our team aims to investigate how Australian music tastes have changed over time by comparing the audio features of tracks from the yearly ARIA and Triple-J Hottest 100 charts from 1970-2019. We will be using the Spotify API to map the tracks from the charts to its corresponding Spotify URI, allowing us to analyse individual tracks against key attributes: duration, key, mode, time signature, acousticness, speechiness, danceability, energy, loudness, valence/happiness and tempo. 

The documentation for the endpoint we are using to get the analysis data is available [here](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/).
We are sourcing the ARIA charts and Triple J Hottest 100 rankings from these sites: 

- https://www.aria.com.au/charts/2019/singles-chart
- https://en.wikipedia.org/wiki/Triple_J_Hottest_100

This dashboard uses Plotly to allow you to interact with our graphs. Use the tools when hovering over charts to select and filter attributes or focus in on time ranges!
