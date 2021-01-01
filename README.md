# VRMenuTestProject  
  
Goal: Design and implement a menu for my newest virtual reality video game without using Unreal Motion Graphics, User Interfaces, primary use of Widgets, or similar. Only 3D interactable "menu" objects allowed. Widgets allowed as child components.  
   
Built off of: https://youtu.be/vEZWC2xZQMU  
  
However, this video does not suit my needs as I need 3-4 menu options, not just one. So, I figured:  
- BP_ButtonXXXXX - Should contain material, highlighted material, and laser point interactions for triggers. These should be responsible for cosmetics/aesthetics.   
- MotionControllerPawn - Should contain most of the logic and interaction code. This should be responsaible for controlling what happens when each actor is clicked upon.   
- MotionControllerMap (Level BP) - Controls the high level interactions. This should be responsible for the spawning and destroying of "pause menu actors".  
  
Dev Notes:    
For VR Funhouse: Christmas Edition:  
- Need to modify SteamVR controller bindings to reflect the changes in menu and controls.  
- Need to delete the "quit game" controller shortcut.    
