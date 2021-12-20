[![Codacy Badge](https://api.codacy.com/project/badge/Grade/129d02949d13460c910acda8d5408cc8)](https://app.codacy.com/app/Bo-Yuan-Huang/IMDb?utm_source=github.com&utm_medium=referral&utm_content=PrincetonUniversity/IMDb&utm_campaign=Badge_Grade_Dashboard)
[![Build Status](https://travis-ci.org/PrincetonUniversity/IMDb.svg?branch=master)](https://travis-ci.org/PrincetonUniversity/IMDb)

This is the ILA model database, archiving the ILA models and the verification scripts.

[IMDb_Archive](https://github.com/PrincetonUniversity/IMDb-Archive)

## Content

### Accelerators

-   [AES](https://github.com/yuex1994/ILA_AES): ILA model of the AES (Advanced Encryption Standard) accelerator.
-   [SHA](https://github.com/yuex1994/ILA_SHA): ILA model of the SHA (Secure Hash Algorithm) accelerator.
-   [FLEXNLP](https://github.com/PrincetonUniversity/flexnlp-ila): ILA model of the FlexASR accelerator (all rights reserved - Harvard University).
-   [HLS-CNN](https://github.com/PrincetonUniversity/hlscnn-ila): This is the ILA model of HLSCNN accelerator (all right reserved - Harvard University)
-   [VTA](https://github.com/LeeOHzzZ/vta-ila): ILA model of the Versatile Tensor Accelerator (VTA)
-   [GB](https://github.com/yuzeng2333/ILA_GB):
-   [RBM](https://github.com/yuzeng2333/ILA_RBM):
-   [NVDLA](https://github.com/yuzeng2333/ILA_NVDLA):

### Communication

-   [LMAC](https://github.com/LeeOHzzZ/lmac-ila): LeWiz Communications Ethernet MAC.
-   [AXI](https://github.com/PrincetonUniversity/ILA_AXI_Protocol): OH! Implementation, it also includes the protocol verification
-   [Off-chip](https://github.com/HuaixiLu/ILA_Offchip_Protocol): BaseJump Implementation

### Cores

-   [RISC-V]
-   [Pico](https://github.com/yuzeng2333/ILA_Pico)
-   [Piccolo](https://github.com/yuzeng2333/ILA_Piccolo)
-   [Rocket](https://github.com/PrincetonUniversity/ILA_Rocket): Rocket Processor
-   [PTX](https://github.com/yuex1994/ILA_PTX): ILA model of the Nvidia GPU PTX ISA.
-   [Nibber](https://github.com/HuaixiLu/ILA_Nibbler): ILA verification of a SIMD Processor
-   [8051](https://github.com/yuex1994/ILA_8051): ILA model of the Intel 8051 micro-processor

### Others

-   [FIFO-BMC](examples/FIFO-BMC) demonstrates the bounded model checking (BMC) capability of ILAng using a FIFO example.
-   [Cache Coherence](https://github.com/HuaixiLu/ILA_CCP): OpenPiton Implementation, we also verifies cache coherence protocol under this repo.
-   [Memory Controller]

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
