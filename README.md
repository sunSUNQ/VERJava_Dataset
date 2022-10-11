# Introduction

This is the replication package for the paper titled "VERJava: Multi-level Vulnerable Version Identification for Java OSS" (ICSME 2022). 

# Folders

- **commit files**: all commits we collected
- **patch functions**: we split commit to patch functions，all patch functions we used in VERJava are in this folder
- **true results**: the true results of each target software
- **Statistics of annotation situations**: to investigate the actual proportion of each annotation situation for each target, we perform a statistic analysis on a sub-dataset.

# Other Statistics

In our 167 CVE datasets, we did some statistics and found some interesting findings.

- **CVE_addordelete_function_statistics.xlsx**: The patch has statistics for operations that add or remove functions.
- **NVD_version_error_statistics.xlsx**: NVD annotated inaccurate statistics of vulnerable versions.
- **Percentage_distribution_of_function_number.xls**: CVE patches involve counts of patch function statistics.
- **Precision_on_threshold.xlsx**: Detailed experimental results for different thresholds.
- **Sibling_interface_class_statistics.xlsx**: CVE statistics of sibling classes and interface classes.
- **VERJava_results.xlsx**: Our human annotation results and VERJava tool experimental results with false negative and false positive statistics.
- **V-SZZ_results.xlsx**: V-SZZ and △V-SZZ experimental results and statistics of false negatives and false positives.
