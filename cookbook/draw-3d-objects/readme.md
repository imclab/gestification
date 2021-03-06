Draw 3D Objects
===============

Live demo R2:  http://jaanga.github.io/gestification/cookbook/draw-3d-objects/r2/draw-3d-objects.html   
- Added save file. The app now can write out an HTML file that rebuilds whatever you created. Leap motion device not required. Can be shared with anybody.  

See also this conversation with @dstir on the Leap Motion Forum:  
https://forums.leapmotion.com/forum/general-discussion/apps-and-project-discussion/53293-simple-3d-sketch-app


Live demo R1: http://jaanga.github.io/gestification/cookbook/draw-3d-objects/r1/draw-3d-objects.html  

It's something like 3D printing in thin air.

This is a vector paint app. You will see that the objects created have shadows and that using your mouse you can zoom, and and rotate all around the objects.

The app draws objects when you point with just one finger. The app stops drawing whenever you open your hand or make a fist.

You can choose to create tetrahedrons, cubes or spheres. You can select one of three sizes. Colors are randomly selected each time a fresh line is started.

###Road Map###
It's likely that this app will have many 'cousins' - apps that concentrate on particular aspects of drawing in 3D. 
Ultimately a much bigger app will combine these coding examples into a much more complex feature example app.

###Issues###
The determination of whether a finger is being pointed or not is still at quite an early stage. 
The app frequently considers that you have two fingers displayed when you actually have only one displayed. 

###Copyright and License
Copyright &copy; 2013 Jaanga authors

MIT License

###Change Log

2013-09-22 ~ Theo
* R2 added. Supports file save.

2013-08-19 ~ Theo
* Folder and file added