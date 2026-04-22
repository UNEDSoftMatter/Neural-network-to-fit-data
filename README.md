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

The file neural_network_program will be created, which is the executable.

If you want to clean everthing before compiling again, just do

make clean


# Running the program

You need to have the following files in the same directory (with the exact names shown below):

- **neural_network_program**: the executable.
- **input**: a file containing the program inputs.
- **data.dat**: the data to be fitted by the neural network.

To run the program, execute:

./neural_network_program


# Input variables 

N       -> Number of particles in each direction ( in a rectangular grid)
