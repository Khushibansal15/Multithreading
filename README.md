# Multithreading  Assignment

This assignment demonstrates matrix multiplication using multithreading in Python.We need to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using multithreading.

## Outputs
### Number of Cores:4
### Number of Threads vs. Total Time

| Num of Threads | Time Taken (seconds) |
|----------------|----------------------|
| 1              | 6.6031               |
| 2              | 5.4031               |
| 3              | 7.8317               |
| 4              | 6.4046               |
| 5              | 6.1392               |
| 6              | 6.4828               |
| 7              | 6.5887               |
| 8              | 7.5548               |
| 9              | 5.7658               |
| 10             | 5.7281               |
| 11             | 5.5632               |
| 12             | 5.3423               |
| 13             | 5.3381               |
| 14             | 5.4289               |
| 15             | 5.4883               |
| 16             | 5.1841               |


### Graph

![Number of Threads vs. Total Time]([![Plot](https://github.com/Khushibansal15/Multithreading/blob/main/Plot.PNG)
)

The graph illustrates how the total time taken for matrix multiplication decreases as the number of threads increases due to parallelism.

### CPU Usage

![CPU usgae](![Capture](https://github.com/Khushibansal15/Multithreading/assets/91721407/36138d18-1714-444a-aa6e-0b74a1f5e59b)
)

The CPU usage graph shows the utilization during the execution of the multithreading program, demonstrating the effectiveness of multithreading in leveraging CPU resources.
