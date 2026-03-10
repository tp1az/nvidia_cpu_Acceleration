These are my implementations of the final exercises in the NViDIA Deep Learning Institutes Gpu Acceleration with the C++ Standard Library. 
The goal of this course is to improve fundamentals in writing parallizable code using the C++ STL algorithms. 
In DAXPY file I rewrote the Daxpy algorithm using std::transform std::for_each_n and std::fill_n
In the Select_Parallization I wrote a functionwhich selects some elements of an input vector v according to a general, user-provided criterion and copies the selected element consecutively into a new vector w.
In both of these cases I used c++ std::execution::par along with compiler flags to evaluate the differences in using a multicore cpu as well as gpu multithreading to accelerate algorithms.
Overall this project has been a great opportunity to learn about best practices in using STL Algorithms as well as writing code that can be executed on the cpu and gpu.
