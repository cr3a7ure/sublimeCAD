sublimeCAD
-----------

Sublime Text 3 as OpenSCAD Editor

The build file will let you "build" the model and "run" or export it to stl.
The SideBar file will let you open openscad files with Openscad and stl with Netfabb (default), from the folder menu.
The only thing you will need to do while working with scad files is Alt-Tab..

This setup assumes you are using Linux.

Not tested but it should work for Sublime Text 2. For Windows users check the documentation on Sublime(http://docs.sublimetext.info/en/latest/reference/build_systems.html) and OpenSCAD(http://www.openscad.org/documentation.html)


Sublime plugins
----------------
Install them through Sublime automatically, those links are for reference.

1. Install the Package Installer
  https://sublime.wbond.net/installation
2. Install openscad plugin
  https://github.com/gorhgorh/Sublime-OpenScad
3. Install SideBarEnhancements
  https://github.com/titoBouzout/SideBarEnhancements

OpenSCAD
--------

1. Select on the menu Design -> Automatically reload and compile
2. Select on the menu View -> Hide Editor

Sublime
-------

1. move the <Openscad.sublime-build> inside ~/.config/sublime-text-3/Packages/User

  Being inside the downloaded folder:
  
      cp Openscad.sublime-build ~/.config/sublime-text-3/Packages/User/
      
2. Move the <Side Bar.sublime-menu> inside ~/.config/sublime-text-3/Packages/User/SideBarEnhancements/Open/ With/

  or cp or edit your own
  
      cp "Side Bar.sublime-menu" "~/.config/sublime-text-3/Packages/User/SideBarEnhancements/Open With/"
