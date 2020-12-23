# Moodify

Moodify is an interactive digital platform that uses your music to generate mood playlists customized to your specifications. You can use Moodify right now at [bit.ly/Moodify](bit.ly/Moodify).

## Problem
We created Moodify because we saw a gap in the market for playlist creation: Spotify’s pre-curated mood playlists aren’t personalized, there’s no way to automatically make a playlist, and Spotify has an abundance of audio data about their music available through their API, but it’s largely inaccessible without coding. 

## How it Works
1. Moodify connects to your Spotify account, and you select playlists that you want to draw music from. 
2. Moodify sorts all the songs in those playlists based on certain audio features (detailed [here](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)) that define a mood. 
3. The best-fitting songs are added to the new mood playlist.

## Audio Feature Visualization
![visualization](https://github.com/ryanbbrown/moodify/blob/master/visualization.png?raw=true)

In these charts, you can see that energy (orange bar) is much higher for the workout playlist as compared to the sad playlist, while the opposite is true for acousticness (blue bar). These are examples of audio data we would use in our algorithm to identify a particular mood.

---

*Moodify was created as a product for Texas Convergent’s Data Analysis build team, and on demo day it won “best tech” out of 16 teams. Our pitch deck can be accessed [here](https://docs.google.com/presentation/d/1Pgp-dAD6iWmNNCP29KKCCfbY7YP035VXur6w7aOtTfY/edit?usp=sharing).*
