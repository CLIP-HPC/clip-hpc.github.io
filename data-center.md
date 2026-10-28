---
title: "Data Center"
description: "Compute nodes, storage, and network behind CBE, the CLIP Batch Environment."
url: "https://clip.science/data-center/"
---

# Data Center

Compute nodes, storage, and network behind CBE, the CLIP Batch Environment.

CBE, the CLIP Batch Environment, combines CPU, GPU, and high-memory compute
nodes with a parallel file system and a high-speed network. The platform runs
on OpenStack-managed infrastructure.

## Overall capacity

- **3,456** CPU cores in C3 nodes
- **112** GPUs: 64 NVIDIA B200 and 48 NVIDIA A100
- **8 TB** memory per M3 node, 32 TB across all M3 nodes
- **1 PB** BeeGFS parallel file system with **800 GB/s** throughput
- **400 Gbit/s** RoCEv2 network fabric

## Compute node classes

**CBE compute node classes**

| Class | Best suited for | Nodes | Hardware per node |
| --- | --- | --- | --- |
| C3 (CPU) | General-purpose batch and interactive workloads | 18 | 2× AMD EPYC 9655 (192 cores), 768 GB RAM |
| G5 (GPU) | Large model training, multi-GPU jobs, and GPU-accelerated simulation | 8 | 8× NVIDIA B200 |
| G4 (GPU) | Machine learning, deep learning, and GPU-accelerated analyses | 12 | 4× NVIDIA A100 |
| M3 (high memory) | Memory-intensive analyses that don't fit on standard nodes | 4 | 4× Intel Xeon 8460H, 8 TB RAM |

## Storage and network

BeeGFS is a parallel file system: it spreads data across many servers so that
many jobs can read and write at the same time. The CBE file system offers 1 PB
of capacity and up to 800 GB/s of throughput.

The nodes connect through a 400 Gbit/s Ethernet fabric that uses RoCEv2 (RDMA
over Converged Ethernet, version 2). Remote direct memory access (RDMA) lets
nodes exchange data directly between their memories, with low latency and
little load on the processors.

For details on the current configuration, contact the
[HPC Servicedesk](https://vbc.atlassian.net/servicedesk/customer/portal/5/group/6).

## Get help

Account holders can open a ticket in the
[HPC Servicedesk](https://vbc.atlassian.net/servicedesk/customer/portal/5/group/6).
Prospective users can email [contact@clip.science](mailto:contact@clip.science).
See [Support](/support/) for all options.
