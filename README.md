# Cache-Simulator

This is a last level cache simulator that simulates a cache given its associativity and the replacement policy followed. The accepted replacement policies are Random Replacement Policy, Least Recently Used(LRU) Policy and Tree-based Pseudo-LRU Policy. The problem statement can be found in _Problem-Statement.pdf_ along with more details on the implementation. Given a memory trace detailing access address and access type(r/w) as input, the code produces various cache events caused by the input which includes # of misses of each type(compulsary/conflict/capacity,read/write), # of accesses(read/write) and # of dirty blocks evicted. Read readme.txt before executing our code. The language used is C++.

## Testing

The memory trace in _input.txt_ with the sample terminal inputs as given in _readme.txt_ produces the sample output given in _readme.txt_.
