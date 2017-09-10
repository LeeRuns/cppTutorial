# cppTutorial
A repository of different cpp tutorials that I have performed 2 learn the language
# Design 4 Use  
Place to store cpp code examples.  First focusing on all of the different snippets and modules that are usefull
when making engineering applications.  This is training which I elected to engage upon to further my career.
The page is designed to provide myself with a place to keep all of this so that it is readily accessible over the years.
In applying these code snippets, the design is to make platform independent code.  The resulting executables will be 
platform specific.


## Section 1: Compilers, Make Files, and Multiple OSs
Understanding how compilers work across multiple OSs and how to write cpp code for cross platform compatibility is critical for the success of any industrial scale cpp based project.  This section addresses the basics that a user must understand to be able to successfully implement a program across a single, or multiple operating systems and machines.  

## When writing in VS2017,VS2015,VS2013:
_need to complete analysis of Compilers and some basic training before I can determine how to set windows to compile code for installation on other windows machines and on linux machines?

1) Install mingw
2) Setup mingw in VS version being run

## When writing in Eclipse Neon 
1) Install gcc compiler
2) Setup GCC compiler for your eclipse project
3) Setup GIT to sync the project

#### _Ubuntu Linux Machines_

#### _Scientific Linux Machines_

#### _Linux Machines_

# FAQ

q-What is a compiler?
q-what is a make file?
q-How is compiling a cpp program different from compiling a fortran program?
q-Do i need to determine the final user before i can write cpp code?
q-What is a VS CPP make file project
q-
q-if i build a win32 application will the executable run on any windows machine?
q-if i build a win32 application will i be able to compile it with gcc?

q-how do i know what compilers are installed on my machine?
q-how do i install mingw?
q-can i run the same compilers on both scientific linux (red hat based) and ubuntu (debian based)?
q-if i setup a cpp program in and compile it with mingw or cygwin, then want to share it with my co-workers, will they need to compile it or will they be able to run the executable?
q- How do i get a list of all of the compilers that can be installed on a linux machine?    

a- To list all available compilers that can be installed, enter:    
    
    _debian/ubuntu_     
                (simple dump of all compilers)            **$ apt-cache search Compiler**    
                (color the java compilers)                **$ apt-cache search Compiler | grep -i --color java**    
                (color the fortran compilers)             **$ apt-cache search Compiler | grep -i --color fortran**    
    
    _Scientific Linux_    
                (general command for rhls)                **$ yum search all compiler**    
                (**preferred cmd**)                       **$ yum groupinfo "Development tools"**    
                
                
q-what are the command to check the compilers installed on a linux machine    
a- depends on the linux distrobution...

    _ubuntu_     
                ()                                        **$ dpkg --list | grep compiler**        
    _Scientific Linux (multiple commands)_    
                ()                                        **$ yum list installed | grep -i --color compiler**    
                ()                                        **$ yum list installed | grep -i --color gcc**    
                ()                                        **$ yum list installed | grep -i --color java**    
                ()                                        **$ yum list installed gcc**
                ()                                        **$ yum list installed 'gcc*'**    
