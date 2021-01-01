# VRMenuTestProject  
Design and implement a VR menu without UMG or UI or similar. Only 3D interactable "menu" objects.  
  
The basis for this was: https://youtu.be/vEZWC2xZQMU  
  
  
However, this did not suit my needs as I need 3-4 menu options, not just one. So, I figured:  
  
BP_ButtonXXXXX - Should contain material, highlighted material, and laser point interactions for triggers.  
MotionControllerPawn - Should contain most of the logic and interaction code.  
MotionControllerMap (Level BP) - Controls the high level interactions.  
