# CLI Twitter status update bot

* Author: Luka Pusic <luka@pusic.com>
* Github: https://github.com/lukapusic/twitter-bot

## Description
This script logs into your Twitter account and posts a tweet, all without the official API.

## System requirements
* Unix like OS (Linux, Mac OS X...)
* curl

## Instructions
* Modify username and password.
* Apply executable permissions ```chmod +x ./tweet.sh```
* Usage: ```bash tweet.sh [tweet]```

## Changelog

#### 12/15/2011
* The script now throws an error if there is no tweet text provided.

#### 10/27/2012
* The script is fixed now, fully supports SSL and logouts properly.

#### 12/2/2014
* Adjusted the script to twitter changes. Removed --sslv3 curl parameter, changed the way we parse authenticity token. Tested on OSX.

#### 4/6/2015
* Fixed login form url.

#### 10/16/2016
* Fixed login form url.
* Fixed login form parameters.
* Added failed login checks.

## Known issues
* When Twitter updates their website the script stops working. Do not use this script for critical applications.
* Two step authentication and login verifications are not supported.

## License
[CC-BY-NC](https://creativecommons.org/licenses/by-nc/2.0/), [Luka Pusic](https://pusic.com)
