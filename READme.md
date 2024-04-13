# Matrix Multiplication with Multithreading

This repository contains a Python script that demonstrates matrix multiplication with multithreading using Google Colab. The script multiplies 100 random matrices of size 1000x1000 with a constant matrix of the same size and measures the execution time with different numbers of threads. Additionally, it monitors CPU usage during the execution.

## Methodology

The script utilizes the `concurrent.futures` module in Python to implement multithreading for matrix multiplication. It generates 100 random matrices and a constant matrix of size 1000x1000. Then, it performs matrix multiplication in parallel using the specified number of threads. CPU usage is monitored using the `psutil` library.

## Result Table

The following table shows the execution time and CPU usage for matrix multiplication with varying numbers of threads:

| Threads | Time taken (s) | CPU Usage (%) |
| ------- | -------------- | ------------- |
| 1       |      8.25      |     5.05%     |
| 2       |      7.27      |     22.0%     |
| 3       |      6.13      |      4.0%     |
| 4       |      7.54      |      4.0%     |
| 5       |      8.95      |      3.5%     |
| 6       |      6.83      |     55.1%     |
| 7       |      6.13      |      4.5%     |
| 8       |      7.77      |      4.5%     |

## Result Graph

The graph below illustrates the relationship between the number of threads and execution time:

![image](https://github.com/sgracevera/MultiThreading/assets/130788675/aafb7593-0815-4de4-9a2e-f1401e00e5ec)


## Usage

To run the script:
1. Open the provided notebook in Google Colab.
2. Execute the code cells in the notebook.
3. View the results in the output.

## Dependencies

- Python 3.x
- NumPy
- concurrent.futures
- matplotlib
- psutil

## License

This project is licensed under the [MIT License](LICENSE).


