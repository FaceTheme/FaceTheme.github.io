# Setting Menu <!-- {docsify-ignore-all} -->

<img src="./_images/flor/2.png">

> Example for adding on-off menu item

```js run
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Flor - HTML5 Video Player</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="./video-js-7.14.1/video-js.min.css" rel="stylesheet">
	<link href="./video-flor/videojs-flor.css" rel="stylesheet"/>
</head>
<body>
	<video id="video_player" class="video-js" controls preload="none" width="800" height="450" poster="./assets/poster.jpg" data-setup='{}'>
		<source src="https://d2zihajmogu5jn.cloudfront.net/elephantsdream/hls/ed_hd.m3u8" type="application/x-mpegURL" />
		<p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
	</video>
	<script src="./video-js-7.14.1/video.min.js"></script>
	<script src="./video-flor/videojs-flor.min.js"></script>
	<script>
		(function(window, videojs) {
			var videoPlayer = window.videoPlayer = videojs('video_player');
			var flor = window.flor = videoPlayer.flor();
		}(window, window.videojs));
	</script>
</body>
</html>
```