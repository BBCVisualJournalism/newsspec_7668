# Newsspec-7668

WW1 Timeline

## Installation

grunt

grunt images

grunt translate

## Issues

Debug mode is not available due to the changes in architecture required in this project (e.g. missing jQuery version).
Videos will not work in the stage environment, unless the video has a matching MAP page on stage (unlikely). Similarly, placeholder images for videos will not load in the local environment because of cross-domain issues. Both should work in tandem on live.
Videos require two clicks on mobile devices, owing to data-usage restrictions that prevent autoplay from working.

## Changes to the architecture

In order to get videos working correctly, some changes to the default iFrame scaffold architecture have been made. [These changes are outlined here](https://github.com/BBCVisualJournalism/newsspec_8387/wiki/Changes-to-the-default-iFrame-Scaffold-architecture).

## iFrame scaffold

This project was built using the iFrame scaffold v1.4.3

## License
Copyright (c) 2014 BBC
