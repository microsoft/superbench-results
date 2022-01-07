# Azure NDmv4 Golden dataset on Superbench v0.3

The dataset is generated from 729 ndmv4 nodes' Superbench v0.3 raw results.

The results are the averaged data among the same type of metrics. For example, we aggregate IB loopback bandwidth from 8 NICs together and do the average, aggregate kernel launch time from 8 GPUs together and do the average, aggregate disk IO latency from 8 disks together and do the average, etc.

Included benchamrks: 

-   kernel-launch
-   gemm-flops
-   nccl-bw
-   ib-loopback
-   mem-bw
-   cublas_function
-   cudnn_function
-   matmul
-   sharding-matmul 
-   computation-communication-overlap
-   bert_models
-   lstm_models
-   gpt_models
-   resnet_models
-   densenet_models
-   vgg_models

Missed benchamrks: 

-  disk-benchmark
-  gpu-copy-bw
