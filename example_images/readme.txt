The images presented here were created by Kevin Wang. 
When using sndrizpipe you will need to put the faux flt files into a folder labeled 'bright.flt'.
You will need to use the following commands:
 *sndrizpipe bright --dosetup --dorefim --dodriz1
 *in the jupyter notebook about making example files you will need to run the third cell in order to fix one of the resulting files for the drizzle process
 *for some reason drizzlepac sometimes drops certain factors that are important to have
 *sndrizpipe bright --doreg --dodriz2 --dodiff --imsize 300 --tempepoch 11

In the same directory where you keep the bright.flt folder, you will need to include the epochs file. Sndrizpipe uses this for certain formatting things.

The parameters imsize 300 and tempepoch 11 are unique to these images as they control the size of the ouput images and demonstrate how to do subtractions between various epochs.

If you get an error about orig_wcs missing you are using too old of a drizzlepac version and need to update.
