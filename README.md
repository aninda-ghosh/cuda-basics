# cuda-basics

Learning the Parallelizationo of CUDA

## Basic RunDown Stats

Addition of a Million Numbers

---------------------------------------------------------------------------------------------------------------------

Blocks      Threads         Runtime                 Improvement         Error Injected          Error %
1           1               126,540.590 us          NA                  0                       0
1           256             1468.649 us             -98%                1                       0.0001%
4096        256             19.424 us               -98%                247                     0.0247% ?? Ugh Why

---------------------------------------------------------------------------------------------------------------------
