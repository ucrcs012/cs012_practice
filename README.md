cs010_practice
==============

The CS010(v) practice repository is used to set up a students Cloud 9 public 
workspace to be used in collaboration with other students.

The practice workspace has been created to provide a place for students to
play with code and collaborate with other students on Labs, CodeLab, Zyante and
lecture concepts. Share your workspace with other students and start figuring
out C++ together.

Remember that assignments are to be done on your own and should not be shared
with other students. Practice programing concepts can be used here, but not the
assignment.

Once the workspace is created, you can utilize two terminal commands. The first
will pull all new files or modifications and incorporate them into your
Cloud 9 workspace. The second will reset all files you have modified to the 
versions that exist in the primary repository (overwriting without confirming).

* git pull
* git checkout -f


As the quarter progresses examples may be added for you to utilize or view. You
will utilize the above "git pull" whenever you wish to check and see if there
is anything new for you to "grab".



To compile a program we must be in the same directory as the C++ source file and
then you may execute the program.  By default the compiler g++ creates an 
exectuable called "a.out".

g++ hello_world.cpp


The g++ compiler creates a new file, the executable, called "a.out" by default.

run a.out
OR 
run a.out 10

The second run command executes the program for 10 seconds. This is useful when 
the program requires user input and takes longer than 5 seconds to execute.


To go back to the top level home directory we utilize an aliased command "home".
