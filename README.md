HungarianAlgorithm
==================

Implementation of the Munkres' Assignment Algorithm (aka Hungarian Algorithm) in C++, based on <a href="http://csclab.murraystate.edu/bob.pilgrim/445/munkres.html">this</a> writeup.

I used the <a href="http://eigen.tuxfamily.org/index.php?title=Main_Page">Eigen linear algebra library</a>. I've included the header files in the folder EigenLibrary.
All that has to be done to use them is to compile with the include flag "-I EigenLibrary/".

1. Compile the program with

  <code>g++ -I EigenLibrary/ matching.cpp</code>
  
3. Run the program with

  <code>./a.out matrixfile</code>
