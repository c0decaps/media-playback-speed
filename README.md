# media playback speed browser bookmarks
:octocat: Page is [here](), explanation and code can be found below

JS browser bookmarklet to change the browsers media playback speed.
The content of the booklets is the following: 
* audio :headphones: : e.g. ```javascript:(function(){document.getElementsByTagName('audio')[0].playbackRate=1.25;})();``` for an example ```playbackRate``` of ```1.25```
* video :clapper: : e.g. ```javascript:(function(){document.getElementsByTagName('video')[0].playbackRate=1.25;})();``` for an example ```playbackRate``` of ```1.25```

## technical details
this can be done by locating the (hopefully only) player by its html tag and adjusting its [```playbackRate```](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/playbackRate)

## troubleshooting
* Firefox: ![](resources/firefox.gif?raw=true)
* Chrome: ![](resources/chrome.gif?raw=true)
* Opera: Add a new site to the bookmarks and name it however you want. Ater it was created, edit the bookmark with a right click on it and change the sites url to the corrensponding option for your needs (see above)

## TODO
add functionality for audio, ideally with tabs for optical simplicity
