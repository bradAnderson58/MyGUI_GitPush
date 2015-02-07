# MyGUI_GitPush
For use with HardPG: The Hardening
TODO:

Download this
Create a Path variable (mine is $(MYGUI_HOME))
C/C++ General include directories:
  $(MYGUI_HOME)\MyGUIEngine\include
  $(MYGUI_HOME)\Platforms\Ogre\OgrePlatform\include
  
Linker General additional library dir:
  $(MYGUI_HOME)\lib\Debug
  $(MYGUI_HOME)\lib\Release
  
Linker Input additional dependancies:
  MyGUIEngine_d.lib
  MyGUI.OgrePlatform_d.lib  (Debug)
  MyGUIEngine.lib
  MyGUI.OgrePlatform.lib   (Release)
  
If you are Brandon or Kevin, hopfully this should work.  If you are not, I have no idea.

