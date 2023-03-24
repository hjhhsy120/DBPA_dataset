# Dataset

## Folders
+ 32_128: 32 cores and 128 GB memory
+ 32_256: 32 cores and 256 GB memory
+ 64_128: 64 cores and 128 GB memory
+ 64_256: 64 cores and 256 GB memory

## Files

### Single Anomalies
+ fault1_data.pickle: Concurrent Inserts
+ fault2_data.pickle: Missing Indexes
+ fault3_data.pickle: Heavy Workloads
+ fault4_data.pickle: Vacuum
+ fault5_data.pickle: Concurrent Commits
+ lockwait_data.pickle: Lock Waits
+ multiindex_data.pickle: Too Many Indexes
+ setknob_data.pickle: Small Shared Buffer
+ stress_data.pickle: I/O Saturation
+ normal_data.pickle: Normal

### Compound Anomalies
+ fault2+fault5_data.pickle: Missing Indexes + Concurrent Commits
+ fault2+lockwait_data.pickle: Missing Indexes + Lock Waits
+ fault2+multiindex_data.pickle: Missing Indexes + Too Many Indexes
+ fault3+IO_data.pickle: Heavy Workloads + I/O Saturation
+ fault4+multiindex_data.pickle: Vacuum + Too Many Indexes
+ multiindex+fault3_data.pickle: Too Many Indexes + Heavy Workloads
+ multiindex+IO_data.pickle: Too Many Indexes + I/O Saturation
+ multiindex+lockwait_data.pickle: Too Many Indexes + Lock Waits
+ setknob+fault1_data.pickle: Small Shared Buffer + Concurrent Inserts

## Information

Citation:

```
Shiyue Huang, Ziwei Wang, Xinyi Zhang, Yaofeng Tu, zhongliang Li, and Bin Cui:
"DBPA: A Benchmark for Transactional Database Performance Anomalies"
SIGMOD 2023
```

Main repository:

https://github.com/hjhhsy120/DBPA
