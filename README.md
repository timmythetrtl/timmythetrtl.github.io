# Tekken Lab Assistant

## Gif Gathering

So we’ll get to the html aspect in a bit, but first I’m going to show how I go about collecting the gifs in the first place.

The one thing you’ll need in order to customize the file for your own needs is a means of recording your screen. I personally use the software that came with my graphics card, but of course there are plenty of other options. Unfortunately the process is going to be a bit more tedious if you’re not on PC, but if you’re smart about how you streamline the process you can make it a lot easier.

I start by going into my replays and selecting a match to analyze. Obviously the best choice is going to be a match against an opponent you had a particularly tough time against, but really every match you play is going to be a learning experience so I personally believe it’s best to do this with as many matches as you can.

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/2c79b1fd-79a4-4ebe-9e39-aded9c055838)

Next, simply find a spot in the match that makes you think to yourself “I could’ve responded to that better” or “I don’t know how to counter that”. 

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/9682ff62-e343-41d1-8b77-5ca2db714005)

Then you use the in-game feature to take control of your character (this is bound to the left and right thumbsticks) during the replay and essentially just try out different options until you figure out how to deal with whatever you’ve selected. Once you’ve figured it out, you start recording your screen and capture a short clip of the opponent throwing out the move and you responding to it accordingly. I personally have the start/stop recording button bound to a key combination just to make the process faster.

And that’s the recording process. Ideally this is something you’d repeat multiple times throughout a single replay, and then go on to do this for other replays as well.

Gif of trimming the video

Next what you do is take each clip and trim it down so that it only contains the necessary footage. I just use the default Windows 10 photos program since they’re pretty small clips. After that you make the gifs.

I personally use the software Shutter Encoder since it lets me convert gifs on my desktop. I’ve created a preset that converts each clip into a 320x180 20fps gif (just look up how to do this), and I’ve edited the preferences to automatically go to that preset on startup. 

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/b0769749-a989-40f3-882b-b7039ba6d342



Then I just ctrl select every clip I want to convert, right-click, select “send to”, and choose Shutter Encoder. With all the stuff I’ve set up beforehand all I have to do now is press start function, and within like 30 seconds all of the gifs are done. At this point you can just delete the old videos.

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/4811a2fd-512f-4fbb-856f-21c2b96c725f

The final step of the gif gathering process is to go into the **** folder and place each gif into it’s corresponding character folder.

### Customizing HTML
Now for the easy part. The first step is to open the index.html file in a text editor of your choice. I’d recommend something like notepad++ or VS Code. 

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/03891fab-4b6b-4844-9ba2-55fe2130bd50

Each section is going to be labeled in the code, so all you have to do is navigate to the character you’re labbing and follow these steps (it might be easier if you use ctrl+f to search for your desired section). Let’s go to Lee for this example.

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/42bbf55d-e524-4968-bd0f-f01995e1afe4

The current download is going to be filled with my personal notes. If you want to add to these you’ll have to copy this chunk of code and paste it right above this line that contains the word ‘clear’, and now you get a new spot to log a move. 

https://github.com/timmythetrtl/Tekken-Lab-Assistant/assets/89177115/e29f2bbc-60e7-40dd-aa7a-c3a3db5935f5

Next you go into the folder for the character you choose and copy the name of the desired move. Back in the code navigate to where the old gif is located (it will follow the character’s name and a backslash) and paste in the name and file type of your new gif. Directly underneath this line there will be a space for you to write your notes.

And with that it’s done! Simply save the file, open it up in your web browser, and the move you’ve labbed will now be logged.

## Conclusion

I had considered (Especially since it wouldn’t be guaranteed it would get enough support to warrant putting that much work into it)
So I decided the next best thing to do would be to just give everyone the resources to do whatever they want with it.

I highly encourage you to play around with this and customize it to your liking. Cater it to your main, adapt it to a different fighting game, rewrite the format, or even put it online if you want! My only ask is that whatever you do you share it with the community.

