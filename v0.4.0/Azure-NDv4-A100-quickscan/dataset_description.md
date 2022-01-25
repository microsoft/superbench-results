# Azure NDv4 Quick-scan Golden dataset on SuperBench v0.4

The dataset is generated from 1,939 NDv4 nodes' SuperBench v0.4 raw results.

The results are the averaged data among the same type of metrics. For example, we aggregate IB loopback bandwidth from 8 NICs together and do the average, aggregate kernel launch time from 8 GPUs together and do the average, etc.

Included benchmarks: 

- kernel-launch
- gemm-flops
- nccl-bw
- ib-loopback
- mem-bw

Missed benchmarks：
- gpt_models
- gpu-copy-bw
- cpu-memory-bw-latency
