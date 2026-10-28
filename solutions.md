---
title: "Solutions"
description: "Batch, interactive, and grid computing services offered by CLIP."
url: "https://clip.science/solutions/"
---

# Solutions

Batch, interactive, and grid computing services offered by CLIP.

CLIP offers three services. Batch and interactive computing both run on CBE,
the CLIP Batch Environment; grid computing serves international particle
physics collaborations.

## Which option should I use?

- **Batch computing:** your work runs as scripts without supervision, repeats
  over many inputs, or runs for a long time.
- **Interactive computing:** you want to explore data, develop code, or use a
  graphical application in your browser while the session runs on cluster
  resources.
- **Grid computing:** you take part in the ALICE, Belle II, or CMS
  collaborations, which process data through the grid.

Comparing CLIP with your workstation or with MUSICA? See
[where CLIP fits](/where-clip-fits/).

## Batch computing

CBE gives you terminal access to a cluster with CPU nodes, GPU nodes with
NVIDIA B200 and A100 GPUs, and high-memory nodes; see
[Data Center](/data-center/) for details. SLURM, an open source job scheduler, places your jobs on compute nodes
as resources become available. CBE supports high-throughput computing (HTC): it
handles large volumes of computational tasks over extended periods, rather than
solving a single problem as fast as possible.

Key features:

- Secure Shell (SSH) access with short-lived certificates instead of passwords. Each
  certificate is valid for 16 hours.
- A shared scientific software stack from EESSI, the European Environment for
  Scientific Software Installations, which you load as environment modules.
- GPU jobs that request a full GPU or a smaller, isolated slice of one through
  Multi-Instance GPU (MIG).
- Job arrays for running the same analysis over many inputs.

Typical workloads include Nextflow pipelines, AlphaFold protein structure
prediction, R and Bioconductor genomics analyses, TensorFlow, and the Python
scientific stack.

## Interactive computing

OpenOnDemand is CBE's web portal for interactive work. From your browser, you
can open a shell, manage files, and start applications such as Jupyter
notebooks, RStudio, and remote desktops. Each session runs as a SLURM job on
cluster resources, so you choose the runtime, CPU, memory, and accelerators it
needs. OpenOnDemand replaces the separate JupyterHub, RStudio Server, and XPRA
services of the previous system.

[Open OpenOnDemand](https://ood.atlas.cbenext.vbc.ac.at/)


## Grid computing

CLIP operates T2_AT_VIENNA, Austria's only Tier 2 grid computing site,
processing jobs for international particle physics collaborations: ALICE,
Belle II, and CMS. If you work in one of these collaborations and have a
question about the site, email [contact@clip.science](mailto:contact@clip.science).

## Common tasks

The CBE documentation covers each task in detail:

- [Run your first job](https://docs.vbc.ac.at/research-computing/cbe/quick-start/)
- [Connect with SSH](https://docs.vbc.ac.at/research-computing/cbe/ssh-system-access/)
- [Submit and manage SLURM jobs](https://docs.vbc.ac.at/research-computing/cbe/slurm-jobs/)
- [Submit GPU jobs](https://docs.vbc.ac.at/research-computing/cbe/gpu-jobs/)
- [Find and load software with EESSI](https://docs.vbc.ac.at/research-computing/cbe/software-environment-eessi/)
- [Choose storage and transfer data](https://docs.vbc.ac.at/research-computing/cbe/storage-and-data/)
- [Use OpenOnDemand web applications](https://docs.vbc.ac.at/research-computing/cbe/openondemand-web-applications/)
- [Troubleshoot problems and get support](https://docs.vbc.ac.at/research-computing/cbe/troubleshooting-and-support/)

## Get help

Account holders can open a ticket in the
[HPC Servicedesk](https://vbc.atlassian.net/servicedesk/customer/portal/5/group/6).
Prospective users can email [contact@clip.science](mailto:contact@clip.science).
See [Support](/support/) for all options.
