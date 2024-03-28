# Tekken Lab Assistant

## Gif Gathering

This guide will walk you through the process of collecting gifs for your Tekken lab assistant. Before diving into the HTML aspect, let's start by understanding how to gather the gifs.

### Prerequisites
You'll need a means of recording your screen. This could be software that came with your graphics card or any other screen recording tool.

### Recording Process
1. **Capture Replays**: Start by selecting a match to analyze from your replays. Choose matches where you faced tough opponents or encountered challenging situations.
   
2. **Identify Learning Moments**: Find moments in the match where you could have responded better or need to learn how to counter specific moves.

3. **Take Control and Record**: During replay, use the in-game feature to take control of your character. Try out different options to deal with the situations you've identified. Record your screen while responding to moves.

4. **Trim the Video**: After recording, trim each clip to contain only the necessary footage.

5. **Convert to Gifs**: Use a tool like Shutter Encoder to convert each clip into a gif. Set preferences for size and frame rate to create optimized gifs.

6. **Organize Gifs**: Place each gif into its corresponding character folder.

### Customizing HTML
Now, let's customize the HTML file to integrate these gifs into your lab assistant.

1. **Open the Index.html File**: Open the index.html file in a text editor like Notepad++ or VS Code.

2. **Navigate to Character Section**: Each section in the code corresponds to a character. Use Ctrl+F to search for your desired character section, e.g., "Lee."

3. **Copy and Paste Code Chunk**: Copy the code chunk for the character section and paste it above the line containing the word 'clear'. This creates a new spot to log a move.

4. **Update Gif and Notes**: In the folder for the chosen character, copy the name of the desired move. In the code, paste the name and file type of the new gif. Add notes below the gif if needed.

5. **Save and Test**: Save the HTML file. Open it in your web browser to see the move you've labbed now logged.

## Conclusion

Customize and adapt this Tekken lab assistant to your liking. Whether it's for your main character, another fighting game, or a different format, feel free to modify it. Share your customized versions with the community and contribute to improving the Tekken learning experience for everyone!
