
Loads 3d object and make them rotate as trackball would, using Kivy framework.

This fork is the python 3 version (tested in Kivy-1.8.0-py3.3-win32).


Changes:
* (2015-04-08) changed windmill obj to be two parts (and added blender version in etc)
* (2015-04-08) fixed windmill obj to use correct texture path
* Changed vertex_format tuples from string,int,string to bytestring,int,string
* Ran 2to3.py

Known Issues:
* This version of objloader.py is different (has less code, not sure what yet) than version included in kivy-rotation