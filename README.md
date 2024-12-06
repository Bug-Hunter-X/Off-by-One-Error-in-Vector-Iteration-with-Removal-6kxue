# Off-by-One Error in Rust Vector Iteration
This example demonstrates a common off-by-one error that can occur when removing elements from a vector while iterating over it using an index. The bug occurs when removing an element which causes the other elements to shift their index, but the index variable in the loop is not adjusted accordingly. This will cause the program to skip elements or potentially panic due to an out-of-bounds index.

The solution provided addresses this issue using iterators for a safer and more idiomatic Rust approach.