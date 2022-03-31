 ![chardoc](https://user-images.githubusercontent.com/73298064/159528506-bf6e2181-e90d-427d-ac31-00c2144d7e54.PNG)<br/>
X-Bot Model can be found as a character in the Mixamo library.<br/>
![char1doc](https://user-images.githubusercontent.com/73298064/159529206-2984f8df-5103-4bbc-81d7-297aba2833c7.PNG)<br/>
Low-poly mesh human model can be found on turbosquid's website. You will have to purchase models from turbosquid. Once purchased, there will be directions on how to access the files for this character model.<br/>
## Accessing Mixamo:
![mix1](https://user-images.githubusercontent.com/73298064/159529396-c88706f3-3fd9-45d9-94c7-fd6b25e9632b.PNG)<br/>

Search “Mixamo” on your search bar and you will be sent to Mixamo’s homepage. If you have not created an adobe account, on the far right hand corner there is a sign up option for you to click on. If you have already made an adobe account, there is a login option that is adjacent to the sign up option.<br/>

![mix2](https://user-images.githubusercontent.com/73298064/159529834-5a1bc81c-5b4e-4a16-b410-5ab52036ef09.PNG)<br/>

Login Page<br/>

![mix3](https://user-images.githubusercontent.com/73298064/159529903-f9d1bc78-6a34-4cd6-aaca-13cf594e9e54.PNG)<br/>

Sign-up Page<br/>

## Downloading Mixamo Character Model and Animation:
![duc](https://user-images.githubusercontent.com/73298064/159530174-d32fbabe-5205-444c-909a-806fec7c5ef4.PNG)<br/>

After logging into your adobe account, there will be a library of characters for you to choose from on the character tab. These mixamo characters are already autorigged, so you don’t have to worry about auto-rigging them yourself.<br/>

![docu3](https://user-images.githubusercontent.com/73298064/159530364-a4e5f32e-6140-4659-ac8e-7a5030aa01ca.png)<br/>

Once you are content with the character model you have chosen, download the model as an **FBX file** with the pose being **T-Pose**.<br/>

![docu1](https://user-images.githubusercontent.com/73298064/159530904-a4afcc44-ea19-4e95-84c5-6992eb45e339.png)<br/>

On the animation tab, you can choose a variety of animations to put on your character model.<br/>

![docu2](https://user-images.githubusercontent.com/73298064/159531069-588a8d13-feab-48d8-b9fd-832be1dad288.png)<br/>

Once you are content with the character animation you have chosen, download the animation as a **FBX file, without skin, 30 second frame, and NO keyframe reduction**. This will provide the overall skeleton as well as the model.<br/>

## Importing Character Model and Animation in Unreal Engine:
###### FOR CHARACTER MODEL
![docu4](https://user-images.githubusercontent.com/73298064/159531417-c526e1e1-b88a-42eb-ba58-a2bc43981522.png)<br/>
Drag and drop the FBX file you downloaded for your character model, make sure the skeleton corresponds to the character model you are trying to import, leave the default import options the same, BUT uncheck the import animations option. 
###### FOR CHARACTER ANIMATION
![animd](https://user-images.githubusercontent.com/73298064/159531761-7d152ae6-983e-408d-8747-ff299f667b62.PNG)<br/>
Drag and drop the FBX file you downloaded for your character animation, make sure the skeleton corresponds to the character model you are trying to import, and leave the default import options the same
## Auto-rigging Imported Character Model on Mixamo
![docu5](https://user-images.githubusercontent.com/73298064/159531980-e758cb67-843e-4c22-b82c-361e81050223.png)<br/>

Go to the character tab of the mixamo website and click on “Upload Character”. There, drag and drop either the FBX or OBJ file of your character model. <br/>

![autorigd](https://user-images.githubusercontent.com/73298064/159532195-0c315c99-5182-4fea-9527-b21c5d4bb004.PNG)<br/>

After uploading the file of the character model, drag the points to their designated area like the figure shown above. Press next and Mixamo will start the autorigging process, this will take a few minutes.<br/>

![docu6](https://user-images.githubusercontent.com/73298064/159532284-f1734b1f-23b8-40d2-b1ff-591030cbbb35.png)<br/>

You can then go to the animations tab and try out animations on the auto-rigged character model you just uploaded.<br/>

## Apply Animation on Character Model on Unreal Engine:
![docu7](https://user-images.githubusercontent.com/73298064/159532461-05fc3abd-c47d-45b9-b48a-fc8dff655c13.png)<br/>

Select the desired character model and on the right hand side, there should be an animation tab. To expand the options for the animation tab, click on the small triangle icon that is adjacent to “Animation”. Change the Animation Mode to **“Use Animation Asset”**.<br/>

![docu8](https://user-images.githubusercontent.com/73298064/159532584-d8e791b6-2902-40cb-b182-ecf2fb6867b2.png)<br/>

Select the animation you would want the character to have in the “Anim to Play” section where there is a drop down menu to the right of the box shown in the figure above. <br/>














