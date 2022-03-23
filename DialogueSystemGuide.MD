How to implement the Dialogue System:   
   
Unreal Engine 4 has a built in dialogue system. This system creates Dialogue waves and plays them using Unreal blueprints. These dialogue waves have subtitles attached to them that play when the dialogue wave plays.   
   
We use .wav files that are designated periods of pure silence in order do use this system to get subtitles that last for specified amounts of time without actually emitting an audible sound. We chose not to record the lines for the story because we weren’t confident we could get voice actors that would be able to do the lines justice (I.E. give quality voice acting that did not take away from the game by sucking the user out of the experience).   
   
Here is a step-by-step guide of how to implement the Dialogue System for future areas:   
1-Write the story for the area   
2-Split the story into lines   
3-Measure how many seconds the user should have to read each line to create a list of lengths of silence you need.   
4-Record the .wav audio clips of silence using a recording software such as Audacity.   
5-Import the .wav clips into the UE4 project and label them by length of time of the audio clip.   
6-Create a dialogue voice by right clicking in the content browser and going to sounds> dialogue> dialogue voice.   
7-Create a dialogue wave by right clicking in the content browser and going to sounds> dialogue> dialogue wave. Add the dialogue voice as the speaker, and under that, go to the sound wave and set it to the correct .wav of silence. Then type in the line in the spoken text. Save it, and exit the wave.   
8-Repeat step 7 until you have all of your lines. Keep track of lines by giving all of the ones in the same scene the same start followed by the number that line is in order. For example, DVS1-DVS44 for the visitation room.   
9-Go to the blueprint for the level by going into the map. Then go to blueprints>Open Level Blueprint.   
10-Create the necessary variables by creating 1 dialogue context variable and setting it’s speaker to be the same as that of the dialogue voice you created in step 6. Then create one sound wave variable for each .wav you use for the area and setting their default values to each of the different .wavs you are using for the area.   
11-Use the following pattern of blueprints-First use “Play Dialogue 2D” and set the dialogue equal to the dialogue wave for that line. Set the context to be the dialogue context variable you created. After the “Play Dialogue 2D”, use “Delay”. Then separately, grab the variable for the corresponding silence .wav used in the dialogue wav for that line, and use the “Get” for that variable. Drag from that “Get Duration” and then plug that in to the duration for the “Delay”.   
12-Repeat step 11 for each line. Start this sequence by having the first line come from the BeginPlay event.
