# Sorting Algorithm Performance Evaluation

## Overview

This project evaluates and compares the performance of various sorting algorithms under different input conditions using simulation and modeling techniques in Python. The study focuses on both comparison-based and non-comparison-based sorting algorithms, analyzing their efficiency in terms of runtime and memory usage across different input sizes and data distributions.

## Objectives

1. Implement and evaluate the performance of five sorting algorithms:
   - Bubble Sort
   - Insertion Sort
   - Merge Sort
   - Quick Sort
   - Counting Sort

2. Analyze algorithm performance across different input sizes and data distributions.
3. Provide insights into the strengths and weaknesses of each algorithm for various scenarios.
4. Offer guidance on algorithm selection based on specific data characteristics and requirements.

## Methodology

### Simulation Framework

- **Programming Language**: Python 3.7+
- **Libraries**: numpy, pandas, matplotlib, seaborn
- **Performance Metrics**: Runtime (seconds), Memory Usage (MB)

### Experimental Design

- **Input Sizes**: 100, 250, 500, 1,000, 5,000, 10,000, 20,000 elements
- **Data Distributions**: Random, Nearly Sorted, Reverse Sorted
- **Trials**: 5 per configuration

## Key Findings

1. **Runtime Efficiency**:
   - Counting Sort demonstrated the best runtime performance for datasets with a controlled value range.
   - Merge Sort and Quick Sort showed robust performance across varying input sizes and distributions.
   - Insertion Sort and Bubble Sort were inefficient for large datasets but performed well with nearly sorted data.

2. **Memory Utilization**:
   - Merge Sort required more memory compared to other algorithms due to its merging process.
   - Counting Sort's memory usage scaled with the value range, potentially becoming memory-intensive for large ranges.
   - Quick Sort, Insertion Sort, and Bubble Sort exhibited minimal additional memory usage.

3. **Impact of Data Distribution**:
   - Insertion Sort excelled with nearly sorted data, achieving near-linear runtime.
   - Quick Sort's performance varied based on data distribution, potentially degrading with reverse-sorted data.
   - Merge Sort maintained consistent efficiency across all data distributions.

## Conclusion

The choice of sorting algorithm significantly impacts performance and resource utilization. This study provides empirical evidence to guide algorithm selection based on specific data characteristics and application requirements. For large datasets with a limited value range, Counting Sort offers unparalleled efficiency. For general-purpose sorting with consistent performance, Merge Sort is highly reliable. Quick Sort provides a good balance of efficiency and memory usage but may require optimizations for certain data distributions.

## Future Work

- Extend the analysis to include parallel sorting algorithms.
- Investigate the impact of cache performance on sorting efficiency.
- Explore hybrid sorting algorithms that adapt to data characteristics.

## Contributors

| Heyeman Abdisa |
| Hikma Anwar |
| Hunde Desalegn |
| Ifa Tolla |
| Iman Ahmed |
| Senait Mengesha |
