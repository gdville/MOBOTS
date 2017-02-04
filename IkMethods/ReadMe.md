These files were the work of [Samuel R. Buss](http://euclid.ucsd.edu/~sbuss/ResearchWeb/ikmethods/index.html), providing variety of inverse kinematics approaches, especially relevant to inverse kinematics of multibodies with multiple end effectors. Included is an extension of damped least squares called selectively damped least squares (SDLS) which adjusts the damping factor separately for each singular vector of the Jacobian singular value decomposition based on the difficulty of reaching the target positions. SDLS has advantages in converging in fewer iterations and in not requiring ad hoc damping constants. Theory is presented in this [paper](http://euclid.ucsd.edu/~sbuss/ResearchWeb/ikmethods/SdlsPaper.pdf).

You will need to have OpenGL, GLUT and GLUI header files and libraries to compile and run these. 

 * Software accompanying the book
 *		3D Computer Graphics: A Mathematical Introduction with OpenGL,
 *		by S. Buss, Cambridge University Press, 2003.
 *
 * Software is "as-is" and carries no warranty.  It may be used without
 *   restriction, but if you modify it, please change the filenames to
 *   prevent confusion between different versions.  Please acknowledge
 *   all use of the software in any publications or products based on it.
