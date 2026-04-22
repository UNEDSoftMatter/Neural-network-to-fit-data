# Neural-network-to-fit-data
Neural network programmed with C++/CUDA to find a function fitting a set of data points.
Developed by Adolfo Vázquez-Quesada. 

mail: a.vazquez-quesada@fisfun.uned.es

--------------------------------------------------

- Host variables and functions are declared in class_system.h.
  Each function is defined in its own file, specifically in system_* files.

- Device variables and functions are declared in kernel_functions.h.
  Each function is defined in its own file, specifically in kernel_* files.

- In config.h we can define if the real variables are float or double.

- main.cu is the main file of the code.

# Compilation 
The compilation is done with the makefile file. 
To compile, just write the following command in the command line:

make

If you want to clean everthing before compiling again, just do

make clean

# Input variables 
