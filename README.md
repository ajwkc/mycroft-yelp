# Yelp Restaurant Finder [![Build Status](https://travis-ci.org/btotharye/mycroft-yelp.svg?branch=master)](https://travis-ci.org/btotharye/mycroft-yelp) [![codecov](https://codecov.io/gh/btotharye/mycroft-yelp/branch/master/graph/badge.svg)](https://codecov.io/gh/btotharye/mycroft-yelp)
Finds restaurants via the Yelp API

## Description 
Finds restaurants via the Yelp API

## Examples 
* "I need a place to eat dinner"
* "Need a place to eat sushi"
* "find me a place to eat sushi"
* "find me a place to eat dinner"
* "more information" - Will give more information about the current restaurant using the context method
* "next restaurant" - Will go to next result and you can then ask for more information for the address and such (Future text message)

## Setting Up API Token
You will need to go to https://www.yelp.com/developers/v3/manage_app and create a app which will then give you a api token you will put into the home.mycroft.ai settings page for this skill.

The zip code is not required, if you don't put a zip code in it will use the location from the mycroft home settings.

## Screenshot Example
Here is what from the Mycroft CLI the response looks like currently, plans to have this come with all the info including the address and such as a text message using IFTTT webhooks.

![yelp screenshot](https://github.com/btotharye/mycroft-yelp/blob/master/yelp_ss.png)


## Credits 
btotharye
