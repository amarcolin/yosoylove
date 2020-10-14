# Shoutcast HTML5 Player With Chromecast Support
https://amarcolin.github.io/yosoylove/
Responsive web player with lyrics for SHOUTCast streaming. 

![Responsive Web Player for SHOUTCast](https://i.imgur.com/vUJD4EX.png)

## Required:
- PHP >= 5.3
- cURL

## Installation
- Just put the files in your server
- **Configure your player in the file *script.js* in the *js* folder**
    - Set the name of your web radio
    - Set your streaming URL (without `/` in the end)
    - Set your API key of Vagalume for the lyrics([See how to get your API key](https://api.vagalume.com.br/docs/))

### HTML5 Player for SHOUTCast streamings with info like:
- Current song
- Historic of played songs (Not tested in SHOUTCast V1)
- Cover art of the current song ([iTunes API](https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/))
- Lyrics of the current song ([Vagalume API](https://api.vagalume.com.br/docs/))
- Responsive design

## Keyboard Controls 
- `M` - mute/unmute
- `P` and `space` - play/pause
- `arrow up` and `arrow down` - increase/decrease volume
- `0 to 9` - volume percent

Based on https://github.com/gsavio/player-shoutcast-html5 and https://github.com/stestagg/dashcast
