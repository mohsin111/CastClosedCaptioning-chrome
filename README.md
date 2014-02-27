# Closed Captioning

This Google Cast demo application shows how to control closed captioning for a receiver app using a custom namespace. Chromecast supports both WebVTT and TTML for closed captioning. This sample uses WebVTT files.

## Dependencies
* Chrome browser.
* Google Cast Extension: https://chrome.google.com/webstore/detail/google-cast/boadgeojelhgndaghljhdicfkmllpafd

## Setup Instructions
* Get a Chromecast device and get it set up for development: https://developers.google.com/cast/docs/developers#Get_started
* Register an application on the Developers Console (http://cast.google.com/publish). Select the Custom Receiver option and specify the URL to where you are hosting the closedcaptioningreceiver.html file (You can use Google Drive to host your files: https://googledrive.com/host/0B716ywBKT84AMXBENXlnYmJISlE/GoogleDriveHosting.html). You will get an App ID when you finish registering your application.
* Setup the project dependencies
* Insert your App ID in the closedcaptioning.js (look for applicationID in that file)
* Put all the files on your own web server.
* Open a browser and point to your page at http://[YOUR_SERVER_LOCATION]/closedcaptioningsender.html

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs
* Design Checklist (http://developers.google.com/cast/docs/design_checklist)
* If you find any issues, please open a bug here on GitHub

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE

## Google+
Google Cast Developers Community on Google+ [http://goo.gl/TPLDxj](http://goo.gl/TPLDxj)