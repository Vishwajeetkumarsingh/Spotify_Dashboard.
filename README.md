# Most Streamed Spotify Songs 2023
- Link to the Interactive Dashboard <a href="https://www.novypro.com/project/most-streamed-spotify-songs-2023-">Click Here!</a>


## Task List:
- Download dataset
- Enrich Dataset with GenAI/Python
- Make Glass morphism Background
- Load into PowerBI
- Create DAX
- Make HTML code for Album Art
- Make Deneb Heatmap
- Make Deneb Donut

## About the dataset:

The dataset consists of the following features:

| Feature               | Description                                           |
|-----------------------|-------------------------------------------------------|
| track_name            | Name of the song                                      |
| artist(s)_name        | Name of the artist(s) of the song                      |
| artist_count          | Number of artists contributing to the song             |
| released_year         | Year when the song was released                       |
| released_month        | Month when the song was released                      |
| released_day          | Day of the month when the song was released           |
| in_spotify_playlists  | Number of Spotify playlists the song is included in   |
| in_spotify_charts     | Presence and rank of the song on Spotify charts       |
| streams               | Total number of streams on Spotify                    |
| in_apple_playlists    | Number of Apple Music playlists the song is included in|
| in_apple_charts       | Presence and rank of the song on Apple Music charts   |
| in_deezer_playlists   | Number of Deezer playlists the song is included in    |
| in_deezer_charts      | Presence and rank of the song on Deezer charts        |
| in_shazam_charts      | Presence and rank of the song on Shazam charts        |
| bpm                   | Beats per minute, a measure of song tempo             |
| key                   | Key of the song                                       |
| mode                  | Mode of the song (major or minor)                     |
| danceability_%       | Percentage indicating how suitable the song is for dancing |
| valence_%             | Positivity of the song's musical content              |
| energy_%              | Perceived energy level of the song                    |
| acousticness_%        | Amount of acoustic sound in the song                  |
| instrumentalness_%    | Amount of instrumental content in the song            |
| liveness_%            | Presence of live performance elements                |
| speechiness_%         | Amount of spoken words in the song                    |
| Cover_URL             | Web URL of the cover art                              |

- Link for the Dataset <a href="https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023">(Click Here!)</a>. The dataset is from Kaggle.

## Home Page
<p align="center">
  <img src="images/Dashboard_image..png" width="100%" />
</p>


## Visual Used:
- Slicers: Date, Track, Artist, Year.
- Card: Average streams per Year, Top Song vs AVG
- Card(New): Track, Artist, Release Date, Streams, No. of artists
- Clustered Bar Chart: Tracks by No. of Streams
- Custom Visual: Heatmap with Columns(Deneb)

## Learnt things from this project:
- Built Custom visuals like heatmap with columns using Deneb, Custom Donut chart with Deneb. This <a href="https://youtu.be/qR2MkqdgjDk?si=rEY7uf-mtyGLLuiW">Video</a>  explains in detailed implementation of Heatmap Visula.
- Created a Custom Image chart using HTML.
- Experimented with color palette and maintained consistent colors throughout the dashboard. To get the colour Pallete <a href="https://www.color-hex.com/color-palette/53188">refer here!</a>


## Some Important Insights from the Dashboard:
- The track with the most number of streams was `Blinding Lights`, followed by `Shape of You` and `Someone You Loved`.
- The lowest streamed song was `Que Vuelvas`.
- The number of songs per year increased drastically after `2011`.
- The month with the highest number of tracks was `Jan`.
- The week with the highest number of tracks was `Fri`.
