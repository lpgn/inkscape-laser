# Inkscape-laser
creates a laser gcode for inkscape <br />
Download Zip <br />
Place both laser files into inkscape -> share -> extensions


# Horizontal Lines Only
1. Import image (BMP)
2. Path -> Trace Bitmap
3. Delete imported image
4. Set fill color to none
5. Set stroke to flat color and width to 0.05
6. Create box just below image at width wider than the total width of the image
7. Set the height of the box to 0.1mm
8. Edit -> Clone -> Create Tiled Clones...
9. Shift Tab -> Shift Y Per Row: to 100% and Rows to 200? (this number will change to accommodate the height of the object)
10. Delete both the original box you created and the box overlayed on it. (They cause problems?)
11. Select all cloned boxes -> Path -> Combine
12. Place cloned boxes over image then select everything
13. Path -> Intersection
14. Extensions -> Generate G-code -> Horizontal Laser Tool -> Remember to select: Laser Horizontal lines only

#The Video
https://youtu.be/8bl8vIKZ9y8
#Demo Video of Laser Exposing
https://youtu.be/Ul8YaZ_39vI
#Some Completed Boards 
(these were taken while still fine tuning my settings)
https://goo.gl/photos/wEs65TT6wfioqrSTA

I have been running the MakeBlock laser at L8 and the laser speed at 800. 
I use MG Chemicals Positive Developer at a mixture of at least 20 parts water to 1 part chemical.
