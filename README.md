# Guillaume J.

Computational chemist transitioning into HPC support engineering.

Physical Chemistry - Astrochemistry - Computational Science.
Molecular dynamics, quantum chemistry, spectroscopy.
13 years university teaching experience.
Real HPC user: Gaussian, NWChem, Molpro, Slurm, Linux.

---

## Where I'm coming from

I'm a computational chemist moving into HPC support. For ~7 years I was the
researcher on the cluster : running Gaussian / NWChem / Molpro on CECI
infrastructure, and debugging SCF convergence failures, memory overflows and
MPI issues under deadline. For 13 years I've taught at university, which is
mostly the work of making hard technical things clear to people who don't yet
get them.

That's the angle I bring to support: I've been the user in the queue, and I can
explain.

---

## Technical background

**Scientific computing**
- Quantum chemistry: Gaussian, NWChem, Molpro
- Scientific Python: numpy, scipy, pandas, matplotlib
- Fortran (legacy code in research labs)

**HPC & Linux**
- Slurm: job submission, sacct
- Lmod: module system, modulefile creation (Lua)
- Apptainer: container build and usage for HPC
- Bash scripting: set -euo pipefail, trap, logging
- Linux: Ubuntu, process management, filesystem, SSH

**Tools**
- Git, GitHub
- Python automation: argparse, jinja2, paramiko, psutil, rich
- MPI: mpi4py, parallel scaling methodology

---

## HPC Portfolio

| Repo | Description |
|------|-------------|
| [hpc-job-templates](https://github.com/GuillaumeJmt/hpc-job-templates) | Annotated Slurm scripts for Gaussian, MPI, arrays |
| [lmod-demo-environment](https://github.com/GuillaumeJmt/lmod-demo-environment) | Lmod modulefile demo for NWChem 7.3.0 (personal install) |
| [slurm-efficiency-analyzer](https://github.com/GuillaumeJmt/slurm-efficiency-analyzer) | Python tool to detect CPU and memory waste in Slurm jobs |
| [mpi-scaling-benchmark](https://github.com/GuillaumeJmt/mpi-scaling-benchmark) | MPI strong scaling benchmark with mpi4py |
| [bash-hpc-toolkit](https://github.com/GuillaumeJmt/bash-hpc-toolkit) | Defensive bash scripts for HPC support |
| [jobscript-generator](https://github.com/GuillaumeJmt/jobscript-generator) | CLI tool to generate Slurm jobscripts from templates |
| [apptainer-scientific-container](https://github.com/GuillaumeJmt/apptainer-scientific-container) | Apptainer container for scientific Python |
| [hpc-monitoring-dashboard](https://github.com/GuillaumeJmt/hpc-monitoring-dashboard) | Real-time terminal dashboard for HPC node monitoring |
| [gpu-hpc-toolkit](https://github.com/GuillaumeJmt/gpu-hpc-toolkit) | GPU support notes and cluster-convention jobscripts (learning, no GPU hardware) |
| [slurm-admin-cheatsheet](https://github.com/GuillaumeJmt/slurm-admin-cheatsheet) | Slurm administration command reference |
| [hpc-lab-journal](https://github.com/GuillaumeJmt/hpc-lab-journal) | Technical diary of real HPC problems and solutions |

---

## Reproducible results

- NWChem 7.3.0 - H2O HF/STO-3G: -74.962946671090 Ha (deterministic result for this exact input; reproduced to all digits on every correct run, not a literature value)
- Apptainer container: numpy 2.4.6, scipy 1.17.1, pandas 3.0.3

---

## Environment

All projects developed on Apple M1 (ARM64) with Lima VM Ubuntu 24.04.
Realistic HPC environment without a physical cluster.

---

## Contact

Open to HPC support, research computing, and scientific IT positions.
Brussels, Belgium.
