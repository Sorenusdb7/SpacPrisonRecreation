The level select menu present is implemented using Widgets. To modify this menu, open the application and then double click the Menu Widget Blueprint in the Content folder.
![cap1](https://user-images.githubusercontent.com/57114167/162527713-77d91137-8eb9-4e5f-a089-ebde6e496368.PNG)
This opens an asset editor. To adjust the position of buttons, click and drag to move them around the dotted box that represents the screen. Additional buttons can be added to the menu from the drop down on the left side of the asset editor.
![cap2](https://user-images.githubusercontent.com/57114167/162527732-1728225c-f57b-4b22-8840-84fe162037b7.PNG)
To change the behavior of buttons, click the Graph button on the top right of the asset editor. On the Graph screen, you can right click and search for functions to add. Every button needs an On Clicked event, and we can connect this to an Open Level event to create a button that changes the level for us.
![cap3](https://user-images.githubusercontent.com/57114167/162527745-7bf29021-faf2-4393-9ccf-0d8c5dd289a9.PNG)
