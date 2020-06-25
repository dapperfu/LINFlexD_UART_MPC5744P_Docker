

1. Bunch of code to [re]learn powerpc assembly.
2. LLVM e200z4 backend.
3. ????
4. Profit.

# Resources.

- [PPCEABI: PowerPC Embedded Application Binary Interface (EABI) - PPCEABI.pdf](https://www.nxp.com/docs/en/application-note/PPCEABI.pdf)
- [Variable-Length Encoding (VLE)Programming Environments Manual](https://www.nxp.com/docs/en/reference-manual/VLEPEM.pdf)
- [EREF: A Programmer’s Reference Manualfor Freescale Power Architecture Processors](https://www.nxp.com/files-static/32bit/doc/ref_manual/EREF_RM.pdf)
- [](https://www.nxp.com/files-static/training_pdf/FTF/2014/americas/WBNR_FTF2014_NET_F0143.pdf)

# Containerised CI/CD Skeleton Sample Project.

[GitHub Actions Build Status:](https://github.com/AutomotiveDevOps/LINFlexD_UART_MPC5744P_Docker/actions): ![Source Build](https://github.com/AutomotiveDevOps/LINFlexD_UART_MPC5744P_Docker/workflows/Source%20Build/badge.svg)

This repository is a single repo example combining:

- [powerpc-eabivle-gcc-dockerfiles](https://github.com/AutomotiveDevOps/powerpc-eabivle-gcc-dockerfiles)
- [nxp-devkit-mpc57xx-docker examples](https://github.com/AutomotiveDevOps/nxp-devkit-mpc57xx-docker/)
- [Github Actions](https://github.com/features/actions)

# Usage:

## Example Description

- Lets do some basic math.

# Why DevOps?

> - Smaller code changes are simpler (more atomic) and have fewer unintended consequences.
> - Fault isolation is simpler and quicker.
> - Mean time to resolution (MTTR) is shorter because of the smaller code changes and quicker fault isolation.
> - Testability improves due to smaller, specific changes. These smaller changes allow more accurate positive and negative tests.
> - Elapsed time to detect and correct production escapes is shorter with a faster rate of release.
> - The backlog of non-critical defects is lower because defects are often fixed before other feature pressures arise.
> - The product improves rapidly through fast feature introduction and fast turn-around on feature changes.
> - Upgrades introduce smaller units of change and are less disruptive.
> - CI-CD product feature velocity is high. The high velocity improves the time spent investigating and patching defects.
>>  [*Benefits of continuous integration-continuous deployment (CI-CD)*](https://help.mypurecloud.com/articles/benefits-continuous-integration-continuous-deployment-ci-cd/)
