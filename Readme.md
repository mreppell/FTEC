#FTEC

A coalescent simulator capable of modeling faster than exponential population growth

For help running the simulator please read the user guide

For more information about the model please see:

Reppell M., Boehnke M., Zöllner S. (2012). FTEC: a coalescent simulator for modeling faster than exponential growth. *Bioinformatics.* 28: 1282–1283.

Reppell M, Boehnke M, Zöllner S. (2013). The impact of accelerating faster than exponential population growth on genetic variation. *Genetics.* 196(3):819-28.

##Installation and Compilation

FTEC requires header files from both the Boost and TCLAP libraries to compile and run. There are 3 available source code downloads, differing in which of these library files they contain, so that a user can select the most appropriate download for their system. If a user's system already includes a library and they download a version of FTEC that includes the library's header files the program should compile without problem, so if there is any uncertainty download the larger source file.

###Linux
1. Place downloaded source file in directory where you would like to install FTEC
2. tar -zxf File.tar.gz
3. Inside the new /FTEC directory run command `make`
4. The executable FTEC should now reside in the direcotry and can be run using `FTEC -parameters`

###Windows with MinGW
1. [Instructions for installing MinGW and MSYS](http://genome.sph.umich.edu/wiki/Installing_MinGW_%26_MSYS_on_Windows)
2. Download source file and place it in the folder /msys/1.0/home/user/ where user is your user account name
3. Open the MSYS command line
4. tar -zxf File_Name.tar.gz
5. Inside the new /FTEC directory run command `make`
6. The executable FTEC should now reside in the direcotry and can be run using `FTEC -parameters`

###Additional Info
More information on [Boost](http://www.boost.org/) and the [Boost Random Number Library](http://www.boost.org/doc/libs/1_48_0/doc/html/boost_random.html)
More information on the [TCLAP Library](http://tclap.sourceforge.net/)
