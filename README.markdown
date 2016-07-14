# CLI Twitter status update bot

* Author: Luka Pusic <luka@pusic.com>
* Github: https://github.com/lukapusic/twitter-bot

## Description
This script can log into your Twitter account and post a new tweet, all without the official API.

## System requirements
* Unix like OS (Linux, Mac OS X...)
* curl

## Instructions
1. apply executable permissions ```chmod +x ./tweet.sh```
2. usage: ```bash tweet.sh [tweet]```

## Changelog

#### 15.12.2011
* The script now throws an error if there is no tweet text provided.

### 27.10.2012
* The script is fixed now, fully supports SSL and logouts properly.

### 2.12.2014
* Adjusted the script to twitter changes. Removed --sslv3 curl parameter, changed the way we parse authenticity token. Tested on OSX.

## Known issues
* Sometimes when Twitter updates their website the script stops working, so don't rely on it 100%.

## License
[CC-BY-NC](https://creativecommons.org/licenses/by-nc/2.0/), [Luka Pusic](http://pusic.si)
