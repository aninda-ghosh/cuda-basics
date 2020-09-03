# cuda-basics

Learning the Parallelizationo of CUDA

## Basic RunDown Stats

Addition of a Million Numbers

| Blocks | Threads | Runtime     | Reduction in  Execution Time(%) | Error(%) |
|--------|---------|-------------|---------------------------------|----------|
| 1      | 1       | 126,540.590 | NA                              | 0        |
| 1      | 256     | 1468.649    | -98                             | 0.0001   |
| 4096   | 256     | 19.424      | -98                             | 0.0247   |