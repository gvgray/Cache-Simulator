# Cache-Simulator w/ Python

These are the instructions given by the instructor:

The final programming assignment will be a cache simulator.

The program will have three configuration parameters and a trace file specifier which will consist of a set of memory reference addresses(32-bits in size).

cache_sim size of cache in bytes cache line size in bytes associativity file

cache size is <= 64k bytes (and a power of 2)

cache line size is <= 128 bytes (and a power of 2)

associativity is >= 1

file contains one integer value per line representing an reference address

Output consists of:

Total number of memory references: total

Cache Hits: total hits

Cache Misses: total misses

Followed by a printout of the final cache contents.  Print the tag of each line in each set.  Lines in a set should be printed in the LRU positional order (MRU at the top, down to LRU at the bottom).  Sets should be displayed from set 0 down to the final set.
