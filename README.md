# Batch Connect - Avogadro

A Batch Connect app designed for HPC Now! OnDemand that launches Avogadro in a node of the cluster.

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand Server node):

- [Avogadro]
- [Xfce Desktop] 4+

For VNC server support:

- [TurboVNC] 2.1+
- [websockify] 0.8.0+

**Optional** software:

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job

[Avogadro]: https://sourceforge.net/projects/avogadro/files/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[X server]: https://www.x.org/
[VirtualGL]: http://www.virtualgl.org/
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## Install

Use git to clone this app and checkout the desired branch/version you want to
use in the directory of applications in you Open OnDemand installation.

# OpenOndemand_Avogadro
