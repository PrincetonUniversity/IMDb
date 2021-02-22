# IMDb_Accls

This is the ILA model database of accelarators, archiving the accelarator ILA models and the verification scripts.

There's a separate branch for each design. To access it, e.g. AES, simply type
```bash
git checkout AES
```

## Designs
-   [AES](https://github.com/PrincetonUniversity/IMDb_Accls/tree/AES)
-   [SHA](https://github.com/PrincetonUniversity/IMDb_Accls/tree/SHA)
-   [RBM](https://github.com/PrincetonUniversity/IMDb_Accls/tree/RBM)
-   [GB](https://github.com/PrincetonUniversity/IMDb_Accls/tree/GB)
-   [FLEXNLP](https://github.com/PrincetonUniversity/IMDb_Accls/tree/FLEXNLP)
-   [HLS_CNN](https://github.com/PrincetonUniversity/IMDb_Accls/tree/HLS_CNN)
-   [VTA](https://github.com/PrincetonUniversity/IMDb_Accls/tree/VTA)
-   [NVDLA](https://github.com/PrincetonUniversity/IMDb_Accls/tree/VTA)


## Contribute

1.  Please add a new branch for the new case study and provide some description for the design.
2.  Please ensure all commited files follow the [MIT License](LICENSE) requirements.
3.  Please properly categorize the design and provide scripts for setting up/reproducing the case study in `scripts/ci`.
4.  Please test and make sure your model works (at least) under the below environment:

Environment:
-   Ubuntu 18.04 LTS (Bionic)
-   gcc 7.4.0 
-   Python 2.7
-   boost 1.65.1
-   z3 4.4.1
-   bison 3.0.4
-   flex 2.6.0
-   [ILAng](https://github.com/Bo-Yuan-Huang/ILAng) (0.9.1 or above)