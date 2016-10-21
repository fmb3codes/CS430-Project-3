/////////////////////////////////////////////////////////////  
///////////////////CS430 Project 3////////////////////////  
/////////////////////Frankie Berry/////////////////////////  
///////////////////October 20, 2016//////////////////////
////////////////////////////////////////////////////////////

 This application is intended to take in a desired width and height as well as a .json scene input file and .ppm output filename and properly write it out to the designated .ppm file; in contrast with the previous project, this application handles a new light object and the corresponding shading.

 There are no special notes regarding the usage of the program; the program can be built from the makefile and commands should be sent
according to the usage pattern given in the project criteria. The program assumes that a properly formatted json input file
should be passed to the command line and that it should also exist, but there is error checking in the case that it doesn't. Also, if
the output file specified does not exist, then one will be created. 

  Due to the fact that this project is intended to handle illumination, the application does not support the old json file format. In addition to this, the file also assumes that there is at least one light in the json file in order to illuminate the objects, otherwise the resultant output ppm file will be colored fully black (background color). 

  Also included two example .json files for reference which have been checked against to validate the correct .ppm file output with proper diversity of object color/orientation in conjunction with the two different possible light types.
