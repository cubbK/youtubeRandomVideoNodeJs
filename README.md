


## YouTube Data API does not provide a possibility to get a random video. This module aims to solve this problem.


[![Beerpay](https://beerpay.io/cubbic/youtubeRandomVideoNodeJs/badge.svg?style=flat)](https://beerpay.io/cubbic/youtubeRandomVideoNodeJs)
[![Flattr](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=cubbic&url=https://www.npmjs.com/package/youtube-random-video&title=youtube-random-video&language=javascript&tags=npmjs&category=software)


## Istall:
```
npm install -g youtube-random-video
```
## Usage:
```javascript

var youtube = require('youtube-random-video');


youtube.getRandomVid(key, function(err , data){
  //key is your youtube api key
  //data is a JSON object
})
```
