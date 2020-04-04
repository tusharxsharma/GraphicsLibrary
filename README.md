# GraphicsLibrary 🖥️
The graphics. h header file provides access to a simple graphics library that makes it possible to draw lines, rectangles, ovals, arcs, polygons, images, and strings on a graphical window
## Download these header files
You need these few files to run the graphics.h header file
Download the files from here https://github.com/tusharxsharma/GraphicsLibrary
## 3. Include libbgi.a
Copy and paste libbgi.a file in the lib folder of MinGW

Path: C:\MinGW\lib
## 4. Add Link Libraries in Include Folder
   * In the MinGW folder , go to Include

   * Paste these 2 files : graphics , winbigim to the folder.
 

   * Restart CommandPrompt with these options 
      gcc (yourcodename.c) -o (yourcodename) -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
 
 
