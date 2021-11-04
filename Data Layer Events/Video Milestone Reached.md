# Video Milestone Reached

### 

## Javascript Code
```js
window.appEventData1104 = window.appEventData1104 || [];
appEventData1104.push({
  "event": "Video Milestone Reached",
    "video": {
        "categoryName": "<categoryName>",
        "milestone": "<milestone>",
        "secondsLength": <secondsLength>,
        "videoID": "<videoID>",
        "videoName": "<videoName>",
        "videoPlayerType": "<videoPlayerType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|categoryName|string|Category of the Video||||||||
|milestone|string|The milestone being tracked as an integer less than 100|25, 50, 77, 99|||||||
|secondsLength|integer|The total length of the video in seconds|36, 67, 178, 600||||0|||
|videoID|string|Video ID|YT456789, BC4567890, 876546789|||||||
|videoName|string|Video Name|Twitch\_FPS, Age of Empires, Halo|||||||
|videoPlayerType|string|Video Player Type|youTube, bright cove, JW Player, vimeo|||||||




