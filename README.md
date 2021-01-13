# LioranBoard Imgur
 **An extension to connect LioranBoard to Imgur. Can upload OBS screenshots to Imgur as well.**

**Main feature:** Take an OBS screenshot of any source/scene and instantly upload it to Imgur. Can use the Discord webhook extension to send screenshots to your Discord server as well. 

**Other features: **
Create albums
Upload media (pictures and videos) directly from your Transmitter to Imgur (the Imgur link will get saved in a variable in your Receiver, so you can easily post it in your Twitch chat) 
Retrieve media from a specified album
Search by tag to retrieve trending Imgur media

All uploaded media and albums are anonymous. You can save the deletehash into .ini file to be able to delete them later if needed. 

The extension contains a premade deck, ready to be used. I suggest to not edit any variable names, as there are a lot of dependencies within the buttons. 

**Known bugs** (as in Imgur API bugs that I cannot fix) :
Can choose album to upload to only for images. It does not work for videos.

*Note: The OBS screenshot to Imgur feature makes a brief connection to your OBS websocket to retrieve the image data. If you changed your websocket port, you will need to change it in the .lbe file as well. Just edit this line:  address: 'localhost:4444'* 
