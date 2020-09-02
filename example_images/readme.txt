The images presented here were created by Kevin Wang. 
When using sndrizpipe you will need to put the faux flt files into a folder labeled 'bright.flt'.
You will need to use the following commands:
 *sndrizpipe bright --dosetup --dorefim --dodriz1
 *sndrizpipe bright --doreg --dodriz2 --dodiff --imsize 300 --tempepoch 11
You might get an error about 'orig_wcskey' being missing. If you get this error rerun the last command and the error should go away.

In the same directory where you keep the bright.flt folder, you will need to include the epochs file. Sndrizpipe uses this for certain formatting things.
