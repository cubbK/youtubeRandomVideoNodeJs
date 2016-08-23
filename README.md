


## YouTube Data API does not provide a possibility to get a random video. This module aims to solve this problem.

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
