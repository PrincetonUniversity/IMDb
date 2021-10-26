[![Codacy Badge](https://api.codacy.com/project/badge/Grade/129d02949d13460c910acda8d5408cc8)](https://app.codacy.com/app/Bo-Yuan-Huang/IMDb?utm_source=github.com&utm_medium=referral&utm_content=PrincetonUniversity/IMDb&utm_campaign=Badge_Grade_Dashboard)
[![Build Status](https://travis-ci.org/PrincetonUniversity/IMDb.svg?branch=master)](https://travis-ci.org/PrincetonUniversity/IMDb)

This is the ILA model database, archiving the ILA models and the verification scripts.

[IMDb_Archive](https://github.com/PrincetonUniversity/IMDb-Archive)

## Content

### Accelerators

-   [AES] is a documented tutorial for ILA-based behavioral equivalence checking.
-   [FLEXNLP]
-   [HLS-CNN]
-   [VTA]

### Communication

-   [LMAC]: LeWiz Communications Ethernet MAC.
-   [AXI]: OH! Implementation, it also includes the protocol verification
-   [Off-chip]: BaseJump Implementation

### Cores

-   [RISC-V](cores/RISC-V)
-   [PTX](cores/PTX)

### Others

-   [FIFO-BMC](examples/FIFO-BMC) demonstrates the bounded model checking (BMC) capability of ILAng using a FIFO example.
-   [L2 Cache]: OpenPiton Implementation, we also verifies cache coherence protocol under this repo.

## Contribute

1.  Please ensure all commited files follow the [MIT License](LICENSE) requirements.
2.  Please properly categorize the design and provide scripts for setting up/reproducing the case study in `scripts/ci`.
3.  Please test and make sure your model works (at least) under the below environment:

Environment:
-   Ubuntu 18.04 LTS (Bionic)
-   gcc 7.4.0 
-   Python 2.7
-   boost 1.65.1
-   z3 4.4.1
-   bison 3.0.4
-   flex 2.6.0
-   [ILAng](https://github.com/Bo-Yuan-Huang/ILAng) (0.9.1 or above)

A docker image with the above configuration can be pulled by:

``` bash
docker pull byhuang/ilang:IMDb-ci
```
