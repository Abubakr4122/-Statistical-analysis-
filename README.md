# -Statistical-analysis-
18. Statistical analysis 
import numpy as np
arr = np.array([10, 20, 30, 40, 50])
mean_value = np.mean(arr)
median_value = np.median(arr)
std_dev = np.std(arr)
percentile_25 = np.percentile(arr, 25)
percentile_75 = np.percentile(arr, 75)
arr1 = np.array([1, 2, 3])
arr2 = np.array([4, 5, 6])
euclidean_distance = np.linalg.norm(arr1 - arr2)
data = np.array([[10, 200], [20, 300], [30, 400], [40, 500], [50, 600]])
correlation = np.corrcoef(data[:, 0], data[:, 1])[0, 1]
sampled_values = np.random.choice(arr, size=3, replace=False)
window_size = 2
moving_average = np.convolve(arr, np.ones(window_size)/window_size, mode='valid')
print("Original array:", arr)
print("Mean:", mean_value)
print("Median:", median_value)
print("Standard Deviation:", std_dev)
print("25th Percentile:", percentile_25)
print("75th Percentile:", percentile_75)
print("Euclidean Distance:", euclidean_distance)
print("Correlation between two columns:", correlation)
print("Random Sample:", sampled_values)
print("Moving Average:", moving_average)
Output:
Original array: [10 20 30 40 50]
Mean: 30.0
Median: 30.0
Standard Deviation: 14.142135623730951
25th Percentile: 20.0
75th Percentile: 40.0
Euclidean Distance: 5.196152422706632
Correlation between two columns: 1.0
Random Sample: [50 30 10]
Moving Average: [15. 25. 35. 45.]

