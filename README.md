# CSAC

Constrained Self-Avoiding Chromatin

# installation

1- Code requires installation of cmake and boost and eigen3 libraries.

2- After libraries are installed, make sure to change the paths in CMakeLists.txt file.

3- Create a folder called build in the directory where you have the code
cd build
cmake ..
make
Above should compile the code. Hopefully no error.

# running

4- to test, I have a test configuration file in the folder. You can run it as
../build/bin/ensemble -conf ensemble.ini -prefix AA
../build/bin/ensemble = executable created after building the code
ensemble.ini = configuration file needed to point to the input files (see files for details of the inputs)
AA = prefix for the output chain files. This helps to iterate over when creating multiple chains. 

# Citation

When referencing this code, please cite:

Gürsoy, Gamze, Yun Xu, Amy L. Kenter, and Jie Liang. "Spatial confinement is a major determinant of the folding landscape of human chromosomes." Nucleic acids research 42, no. 13 (2014): 8223-8230.

# See also

mCSAC

https://github.com/uic-lianglab/mCSAC

nCSAC

https://github.com/uic-lianglab/nCSAC
