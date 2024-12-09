# BH4TDV-PyConfigurator

This is a Python script to read/write configuration on BH4TDV devices, which include:
X1C3 (tested)
X1C5 (untested)
AVRT5 (untested)
HG-UV98 (tested)

I don't consider myself a programmer at all, but I cobbled this together to command line configure these.
I manually sniffed out the serial datastream to determine where all the bytes go. 
I didn't find all of them, but enough to make most of the functions work. 

functionality includes:
*read/write the device
*read/write a file
*view settings
*edit settings
