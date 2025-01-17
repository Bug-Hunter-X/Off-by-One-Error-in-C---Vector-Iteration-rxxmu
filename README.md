# Off-by-One Error in C++ Vector Iteration

This example demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of the vector, leading to undefined behavior.

The solution involves changing the loop condition to `i < vec.size()` to correctly iterate within the bounds of the vector.