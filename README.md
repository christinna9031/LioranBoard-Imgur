# LioranBoard Imgur
 **An extension to connect LioranBoard to Imgur. Can upload OBS screenshots to Imgur as well.**

**Main feature**  
Take an OBS screenshot of any source/scene and instantly upload it to Imgur. Can use the Discord webhook extension to send screenshots to your Discord server as well. 

**Other features**  
Create albums  
Upload media (pictures and videos) directly from your Transmitter to Imgur (the Imgur link will get saved in a variable in your Receiver, so you can easily post it in your Twitch chat)  
Retrieve media from a specified album  
Search by tag to retrieve trending Imgur media  
Upload Image from URL

All uploaded media and albums are anonymous. You can save the deletehash into .ini file to be able to delete them later if needed. 

**Known bugs**    
Can choose album to upload to only for images. It does not work for videos.

**IMPORTANT**: Please follow the instructions in the premade buttons that are provided after you install the extensions. I suggest to not edit any variable names, as there are a lot of dependencies within the buttons.    

*Note: The OBS screenshot to Imgur feature makes a brief connection to your OBS websocket to retrieve the image data. If you changed your websocket port, you will need to change it in the .lbe file as well. Just edit this line:  address: 'localhost:4444'*     


**How to install an extension:**
1. Download the .lbe extension file
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)
