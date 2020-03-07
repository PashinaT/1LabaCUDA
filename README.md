# 1LabaCUDA

 Multiplication of the matrices with float elemnts.
 Matrixs size is  NxN.
 Visual Studio 2015 and Cuda Toolkit 8 were used for this work.
 
 This code works with Cuda project from Visual Studio.

## System configuration

| Name | Values |
|-------|---------|
| CPU | AMD Ryzen 5 2600 Six-Core Processor 3.4 GHz (Turbo Boost 3.9 GHz) |
| RAM | 16 GB DDR4 |
| GPU | GIGABYTE GeForce GTX 550 Ti [GV-N550D5-1GI] |
| OS | Windows 10 64-bit |

## Results

The average time in milliseconds for 5 measurements

| Size | CPU | GPU |
|-------------|---------------------|-------------------|
| 128 х 128 | 7 ms | 0.3 ms |
| 256 х 256 | 54.2 ms | 4.8 ms |
| 512 х 512 | 433.2 ms | 22.7 ms |
| 1024 х 1024 | 4889.6 ms | 173.7 ms |
| 2048 х 2048 | 29396 ms | 2375.6 ms |
