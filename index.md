# CS6730-Final-Project

<script
  type="module"
  src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"
></script>

## Introduction

<p>
The goals of this project are to assess whether TikTok is a good indicator of overall music popularity and to examine how data characteristics on TikTok may contribute to a song's popularity. We intend to do this by analyzing data of songs on TikTok as well as Spotify, and see if different features of that data, when visualized, reveal correlative insights to us about the songs. Some examples of features that can lead to a correlation to popularity could be the energy and loudness of a song, which are data collected and included in our dataset. We will use the visualizations and analysis to communicate to the viewers what exactly a song being popular on TikTok means for its general popularity. We will also show whether or not certain features contribute more to a song’s overall popularity. Currently, we have an intensity visualization which shows popularity and loudness of songs, looking for a potential correlation, as well as a radial chart that shows how the most popular and least popular songs correlate with different features of the music, revealing correlations. We intend to expand with more detailed visualizations and analysis as the project progresses.
</p>

## Correlating Song Features with Track Popularity

<p>
  In the visualization below, we use a histogram to group the songs into bins according to track popularity. From this, we can see how the average feature values in each bins differ which allows us to analyze how these features correlate to changes in track popularity. In the chart, we can see how the most popular songs are louder in general as it is a less negative decibal. Songs that have less speechiness tend to be more popular while for energy and danceability, these features stay around the same level across all popularity bins.
</p>
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/TikTok_Songs/Sheet10"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>
## Correlating Song Features with Artist Popularity
In this visualization, we use a scatter plot to map the relationship between each of the 4 features with artist popularity. This is done to see if trends that exist at the song level also exist at the artist level. When comparing artist popularity to these features, it can be seen that for loudness, the least popular artists have significantly less louder songs. This same trend can be seen in energy where the least popular artists generally make lower energy songs. For danceability, there seems to be no definite trends as the more popular songs have a wide range of danceability levels. For speechiness. most of the more popular artists have low speechiness while the outlier less popular artists have a significantly higher level of speechiness. 
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/TikTok_Songs/Dashboard2"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>

## Comparing Features from the Most Popular and Least Popular songs

<p>
  In the visualization below we have created a radial chart that has the song
  features as its axes, which are Energy, Valence, Acousticness, Speechiness,
  Instrumentalness, Danceability. We averaged the top 5 most popular songs and
  created a chart and did the same with the bottom 5 popular songs and overlayed
  them to see the correlation, we can see that more viral songs have a lot more
  energy and valence while the lower popular ones tend to have a lot of speech
  and acoustic qualities to them.
</p>
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/lebron_17750753180420/Sheet1"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>
## Artist Popularity
This interactive bubble chart quantifies artist dominance on TikTok. The size of each bubble shows the dominance of an artist in the charts, more hits they have, larger they are. The color intensity represents the average virality of their tracks, this allows us to see that the darker colored circles have a higher average ranking on the chart. Use the filter on the right to compare the trends of 2020 against 2021 and identify the artists who have been wildly successful in either or both years. 
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/StephCurry_17756816904900/Sheet1"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>
## Comparison of Attributes on Spotify vs. TikTok
<p>
  Comparing Song Attributes Between Spotify and TikTok: In the visualization
  below, we map the selected musical attribute to the vertical position of each
  point, where each line represents a single song that trended on both Spotify
  and TikTok. This slope chart allows us to see how a song’s profile changes
  between platforms by toggling the attribute menu.
</p>
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/shared/6JD3PC7W7"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>
## Correlation Heatmap for Tik-Tok Songs
<p>
This correlation heat map allows us to see how different features of the music data correlate with each other. For example, we can see strong positive correlation between Loudness and Energy, and also see strong negative correlation between Acousticness and Energy. This helps us see how songs on TikTok tend to trend in general, and we can also use the correlations with track popularity to see what features correlate more positively vs negatively with track popularity on TikTok.
</p>
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/CorrMap/Sheet1"
  toolbar="bottom"
  hide-tabs
  width="100%"
  height="700"
>
</tableau-viz>
