About
This is the Python code for object detection using python opencv. Your default camera will be used, 
if you want to use the other camera connected to your system you have to modify the one line in the code that is you have to replace the 
VideoCapture(0) 
to
VideoCapture(x)
where you can put x=1,2,3... stop when you get the required camera access.


You have to Adjust the Value of LH,LS,LV and UH,US,UV to get the particular set of color to track.

It uses bitwise operator to remove the unwanted color.
0.1=0 and 1.0=0 but 1.1=1 

credit : Anshul
