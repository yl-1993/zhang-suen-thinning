Zhang-Suen Thinning
===================

This is the implementation of the Zhang-Suen thinning algorithm using OpenCV. The algorithm is explained in "A fast parallel algorithm for thinning digital patterns" by T.Y. Zhang and C.Y. Suen. See the tutorial in [opencv-code.com](http://opencv-code.com/quick-tips/implementation-of-thinning-algorithm-in-opencv/).

To use the thinning function, simply copy the `thinning()` and `thinningIteration()` function to your code. See the `main()` block for an example on how to use the function.

Both `thinning.cpp` and `thinning.py` are similar, except that the former written in C++ and the latter in Python.

So as to be friendly with both py2 and py3, the C expression used in `thinning.py` has been rewritten in Python and `weave.inline` has been replaced with `numba`.

Contact
-------
Feel free to ask question and report bugs to nash [at] opencv-code [dot] com.

Credit
------
Many thanks for DG (dangets [at] gmail [dot] com) for the pointer access code for improving the speed.
