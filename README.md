CPU Simulator program and output file
------------------------

This directory contains simulator.cpp and should produce simulator.out after invocation of "make"

To run the test file's , please use the command below

    ./simulator.out <code.o> <memory.dat>


To test my program with different cache_blocks and different block_sizes, please open
"simulator.cpp" and the number of cache blocks is defined as #define CACHE_BLOCKS and the 
block size is defined as #define BLOCK_SIZE . You can change the CACHE_BLOCKS and BLOCK_SIZE 
on line 40 and 43 to any value for testing and recompile the source code with an invocation of 
"make".


Results for the cache hit and miss performance of different cache blocks and block sizes are outlined in "results.md"

