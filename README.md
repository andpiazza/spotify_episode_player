# spotify_episode_player
A player for a Spotify podcast episode to be embedded on html and css

## HTML code
````
<div class='embed-container'>
    <iframe src='https://embed.spotify.com/?uri=spotify:episode:1ZEli2zi0i4EeNkzh36QYy' frameborder='0' allowtransparency='true'></iframe>
</div>
````

## CSS code
Formats only the player, full width
````
.embed-container {
    position: relative;
    padding-bottom: 15.5%;
    height: 100%;
    overflow: hidden;
    max-width: 100%;
    /*height: 10px;*/
}
    .embed-container iframe,
    .embed-container object,
    .embed-container embed {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
````

## iFrame Code - Widget implementation
````
<iframe src="https://open.spotify.com/embed/show/1jCRjU0EzcMftMTYTadoyY" width="250" height="300" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
````

## References
* [Fiddle HTML and CSS](http://jsfiddle.net/qa73L/993/)
* [Spotify API - Widgets Documentation](https://developer.spotify.com/documentation/widgets/guides/adding-a-widget/)
