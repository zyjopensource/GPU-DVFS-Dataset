# GPU-DVFS-Dataset

This repository provides the dataset used in our research on improving GPU energy efficiency through application-transparent frequency scaling. The dataset includes comprehensive experimental results collected from NVIDIA GPUs across a wide range of operating frequencies.

## About the Dataset

This dataset contains measurements from **33 diverse workloads** executed on the **NVIDIA V100 GPU (TDP 300W)**. Each workload was tested under **various GPU core frequencies ranging from 757 MHz to 1530 MHz**. All experiments are repeated at least 5 times and the results report the average values.

### Included Metrics

- **Performance**  
  Normalized to the performance at the maximum frequency (1530 MHz).

- **Power**  
  Average GPU power consumption during the workload's execution. For multi-GPU runs, the value is averaged over all GPUs used.

- **Energy Efficiency**  
  Defined as `performance / power`. Values are also normalized.

## Data Format

Data is stored in CSV format and is easily parseable for analysis and visualization.

## Reference

This dataset is released in conjunction with our paper:

**Improving GPU Energy Efficiency through an Application-transparent Frequency Scaling Policy with Performance Assurance**

For a full description of the methodology, experiment setup, and insights, please refer to the paper.

## Citation

If you use this dataset in your research, please cite our paper.

---

Thank you for your interest in our work!
