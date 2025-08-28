# Railway LiDAR Spatial Data Analytics

The histograms below summarize the elevation (Z-axis) distributions for two point-cloud datasets captured along a ~70 m railway segment. These visuals are used to infer a data-driven ground-level threshold for filtering and for improving the robustness of subsequent clustering.

## Dataset 1 — Z-axis Histogram
The distribution exhibits a dominant ground-return mode with a right-skewed tail corresponding to above-ground structures (e.g., rails, sleepers, and nearby objects). This supports selecting a threshold just above the ground mode for reliable ground filtering.
![Dataset 1: Z histogram with mode, mean, median](images/dataset1_z_histogram.jpg)

## Dataset 2 — Z-axis Histogram
A similar pattern is observed for Dataset 2, with a pronounced ground mode and a long upper tail. Consistency across datasets enables adopting a comparable ground-level cutoff for cross-dataset analysis.
![Dataset 2: Z histogram with mode, mean, median](images/dataset2_z_histogram.jpg)