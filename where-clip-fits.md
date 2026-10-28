---
title: "Where CLIP fits"
description: "Choose between your workstation, CLIP and CBE, and MUSICA for your research computing."
url: "https://clip.science/where-clip-fits/"
---

# Where CLIP fits

Choose between your workstation, CLIP and CBE, and MUSICA for your research computing.

Start on your workstation to develop and test. Move to CLIP when you need shared
computing capacity, scheduled jobs, or supported scientific applications. If
your project needs national-scale resources, we can point you toward MUSICA
onboarding and the access process of Austrian Scientific Computing (ASC).

These options are not size thresholds. Many projects use more than one: you
might develop on your workstation, run production analyses on CLIP, and request
a MUSICA allocation for a later, larger phase.

## Your workstation

Use your own computer to develop, explore, and run small tests. Typical work
includes:

- Writing and debugging analysis scripts on a small subset of your data.
- Exploring results in a notebook or an R session.
- Preparing figures, reports, and manuscripts.
- Checking a pipeline configuration before you run it on the full dataset.
- Developing and testing GPU code on a local GPU, if your workstation has one,
  before you run it at scale on CLIP.

## CLIP and CBE

Use CLIP when your work needs shared computing capacity, scheduled CPU or GPU
jobs, or supported interactive applications. CBE, the CLIP Batch Environment,
is the cluster you work on. Typical work includes:

- Running a workflow, such as a Nextflow pipeline, across all samples of a
  sequencing project.
- Repeating the same analysis over many inputs or parameter combinations as a
  job array.
- Training or applying machine-learning models, or predicting protein
  structures, on GPUs.
- Running analyses that need more memory or run longer than your workstation
  allows.
- Working in Jupyter, RStudio, or a remote desktop in your browser, with the
  session running on cluster resources.

See [Solutions](/solutions/) for the batch, interactive, and grid
services, and [Access](/access/) to check eligibility and
request an account.

## MUSICA

MUSICA is a national, multi-site high-performance computing system operated by
Austrian Scientific Computing (ASC), not by CLIP. Consider it when your
project's needs call for an ASC allocation, for example:

- Large simulations or analyses that need many nodes working together.
- A long-running project whose computing needs you can plan ahead and want to
  secure as a dedicated project allocation.
- Collaborations with partners at other Austrian institutions that already
  work on ASC systems.

Access is project-based, and ASC grants the resources. The
[VBC guide to getting started with MUSICA](https://docs.vbc.ac.at/research-computing/musica/)
explains local onboarding, including the shared allocation for ÖAW institutes.
The [ASC MUSICA documentation](https://docs.asc.ac.at/musica/index.html) is
authoritative for accounts, projects, access, jobs, and storage, and ASC
provides MUSICA support. If you do not know who manages your institute's MUSICA
allocation, ask through the
[HPC Servicedesk](https://vbc.atlassian.net/servicedesk/customer/portal/5/group/6).

## Not sure? Ask us

Email [contact@clip.science](mailto:contact@clip.science) with your
affiliation, your group or lab, and a short description of your work. We help
you choose the right option.
