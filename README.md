# Description
DFT calculation of 1 atom developed in Fortran for Dr. Hélio Duarte's 2016 Density Functional Theory class at the Chemistry Department in UFMG.

# Instructions
To run the program, it is required to have a Fortran compiler installed in your computer. For this tutorial, it was used the GFortran compiler.

Open the terminal in the folder you downloaded the Atom package and type
```
$ gfortran *.f90 -o run
```
Now you can open and change the settings in the "input" file and run the calculation by typing on the command line
```
$ ./run
```
The results will be saved in the "results" folder under the name you picked in the "input" file (where is written "TITLE").
