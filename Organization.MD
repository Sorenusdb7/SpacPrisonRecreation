In any given Unreal Engine project, there will be a content folder that hold all of your assets and code for your Unreal Engine project. However, not all Unreal Engine projects’ content folders are organized the same way. This file explains how our content folder is organized so that you can find anything you need while working on the project.   
   
   
The content folder is the central storage space that holds everything. Most of these other things are divided into separate folders by asset type, however there are a few things within the content folder that are not in their own separate folders. The first of these objects is the Menu widget blueprint. As there were vary few blueprints used outside of each levels blueprints, we did not create a blueprint folder as it would have been relatively pointless. Next is the PoleMaterial material object used for the red metal poles in the Group Cell Room. Although we do have several materials we use, this has been separated from the rest of the materials as it was the only one we created, instead of being obtained from the Unreal Engine 4 marketplace. We will address the materials we obtained from the Unreal Engine 4 Marketplace at the end of this document. Finally, we have RobotoRegular and TestDiaFont. Both of these objects are used for the font that the subtitles for the dialogue system come from.   
   
The rest of the objects in the content folder are in their own separate folders.    
   
The Animations folder contains the animations used on the ghostly models. 
   
The Characters folder contains the ghostly models and the materials used for them.   
   
The Dialogue_Assets folder contains all of the assets used for the dialogue system. The dialogue voice and sound wave objects float freely within this folder, but the actual dialogue wave objects are separated further into their own folders based on the room the dialogue is for. As such, all dialogue waves for the Visitor Room are in Dialogue_Visitation, and all the dialogue waves for the Group Cell Room are in Dialogue_GroupCell.   
   
Our Maps folder holds our maps, or levels. Inside the maps folder are two more folders, Greyboxing and UsedMaps. Greyboxing contains our greyboxed maps, namely the Isolation Cell, the Rollcall Platform, and the backup of the Visitation Room. The UsedMaps folder holds all of the maps we used in our final built and packaged version of the project, including the Main Menu, the Group Cell Room, and the Visitation Room.   
   
The Meshes folder holds the static meshes for the project. This folder is divided into the VisitorRoomMeshes and GroupCellMeshes folders. VisitorRoomMeshes holds all the meshes used for the Visitor Room, as well as another folder that contains third party assets used for the table in the room. GroupCellMeshes holds all the meshes used for the Group Cell Room, as well as another folder that contains third party assets used for the beds in the room.   
