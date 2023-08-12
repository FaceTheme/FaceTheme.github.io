# Flat

> Flat Skin Retina for JW Player

<img src="./_images/flat/preview.avif">

## Features

- Now support JW Player 8.x
- Premium Skins for JW Player 8: Free, Premium, Enterprise, Ads
- Skin for JW Player 8 that is the most popular video player on the web, live on over 2 million sites
- Skin with Flat Style
- Retina Ready & Fully Responsive
- Unlimited colors – any colour you like
- 8 Different Demos
- HTML5 & CSS3
- Support and updates
- Wishlist Support
- Well Documented
- SVG files included and Well Documented

<img src="./_images/flat/2.png">

## Downloads

> [Flat Skin Retina for JW Player](https://codecanyon.net/item/flat-skin-retina-for-jw-player/12752001)

## Include the skin on the page

```html
<link rel="stylesheet" type="text/css" href="//yoursite.com/yourstyles/flat.min.css>
<script type="text/javascript" src="./jwplayer/jwplayer.js" ></script>
<script type="text/javascript">jwplayer.key="YOUR_JW_PLAYER_KEY";</script>
```

and

```javascript
var videoPlayer = jwplayer('player_example').setup({
    width: 640,
    height: 360,
    file: "/uploads/example.mp4",
    image: "/uploads/example.jpg",
    skin : {
        controlbar: {
          "icons": "#ffffff",
          "iconsActive": "#1abc9c" 
        },
    }
});
```

**Move the timeslider in-line with other controls**

```javascript
videoPlayer.on('ready', function() {
    // Move the timeslider in-line with other controls
    const playerContainer = videoPlayer.getContainer();
    const buttonContainer = playerContainer.querySelector('.jw-button-container');
    const spacer = buttonContainer.querySelector('.jw-spacer');
    const timeSlider = playerContainer.querySelector('.jw-slider-time');
    buttonContainer.replaceChild(timeSlider, spacer);
});
```

## Setting Custom Colors

- `skin.controlbar.text`
  - The color of any plain text in the control bar, such as the time.
- `skin.controlbar.icons`
  - The default, inactive color of all icons in the control bar. This option also controls the color of the play, pause, and replay icons in the inactive and complete states.
- `skin.controlbar.iconsActive`
  - The color of hovered or selected icons in the control bar.
- `skin.controlbar.background`
  - The background color of the control bar and the volume slider. The default background is transparent.
- `skin.timeslider.progress`
  - The color of the bar in the time slider filled in from the beginning of the video through the current position. The buffer region of the control bar is 50% of the opacity of this color. The color of the volume slider is also controlled by this option.
- `skin.timeslider.rail`
  - The color of the base of the timeslider, known as the rail.
- `skin.menus.text`
  - The color of inactive, default text in menus and the Next Up overlay.
- `skin.menus.textActive`
  - The color of hovered or selected text in menus. This option also controls the text color in the Discover overlay and the hover state text color in the Next Up overlay.
- `skin.menus.background`
  - The background color of menus and the Next Up overlay.
- `skin.tooltips.text`
  - The text color of tooltips.
- `skin.tooltips.background`
  - The background color of tooltips.

## Changelog

- Flat Skin Retina for JWPlayer 8.13.8 – 09 May 2020.
- Flat Skin Retina for JWPlayer 8.12.4 – 02 February 2020.
- Flat Skin Retina for JWPlayer 8.3.0 – 06 May 2018.
- Support JW 7.9.3 and timeSliderAbove – 24 February 2017.
- Support JW 7.7.1 and Icons by Base64 – 14 October 2016.
- Support add brand logo on control bar – 02 May 2016.
- Launch: The launch of the Flat Skin Retina for JW7 project – 02 September 2015.

## Reference

- JW Player [Documentation](https://docs.jwplayer.com/platform/docs)
- JW Player [Support](https://support.jwplayer.com/hc/en-us/requests/new)
- JW Player [Pricing](https://jwplayer.com/pricing/)
- Learn more about Using JW Player [Skins](https://docs.jwplayer.com/players/reference/skin)
- Learn more about JW Player [CSS Skin Reference](https://docs.jwplayer.com/players/reference/css-skin-reference)
- Learn more about [Styling and Behavior](https://docs.jwplayer.com/players/reference/css-skin-reference) (JW Web Player)
- Learn more about [Add custom icons](https://docs.jwplayer.com/players/docs/jw8-add-custom-icons) (JW Web Player)
- Design Branded Skins with JW7 [Designer Kit](https://jwplayer.com/blog/jw7designerkit/)
- [Icons font generator](https://icomoon.io/app/) using SVG files
- [PX to EM](http://pxtoem.com) conversion made simple
- Online [CSS Minifier/Compressor](http://cssshrink.com)
- Free Online [LESS Compiler](http://less2css.org)
- Free Offline [LESS Compiler](https://github.com/dikei/less2css)
- [Learn LESS](http://tutorialzine.com/2015/07/learn-less-in-10-minutes-or-less/) in 10 Minutes (or Less)
- LESS for [Notepad++](https://github.com/azrafe7/LESS-for-Notepad-plusplus)
- Online [CSS Minifier/Compressor](http://cssshrink.com)
- JW Player Innovation: [Research, Roadmap, Experiments](https://jwplayer.com/news/)
- JW Player [Source Code](https://github.com/jwplayer/jwplayer/releases)
- How to [build](https://github.com/jwplayer/jwplayer/blob/master/README.md#building-the-player) JW Player from source

## Support

If you have any questions that are not answered in this userguide, or any bugs to report, please contact me via email through my CodeCanyon profile. Contacting through CodeCanyon will prove that you purchased the file.