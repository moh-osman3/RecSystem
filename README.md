Note: data files are too large to upload directly for github
Data Source: Spotify Million Playlist Dataset

Goal: Given a base playlist, can I figure out "similar" songs to add to playlist?

Testing:  Take a playlist and remove 30% of the songs.  Then see how many of the removed songs I can accurately add to the playlist.

Layer 1: Find "similar" playlist based on song intersection with base playlist

Layer 2: Find "similar" songs to add using spotify api

Weights: Use # of followers to create weighting scheme for playlist importance
