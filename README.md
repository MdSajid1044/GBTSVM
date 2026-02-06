# GBTSVM: Granular Ball Twin Support Vector Machine

Please cite the following paper if you are using this code:

A. Quadir, M. Sajid and M. Tanveer, "Granular Ball Twin Support Vector Machine," in IEEE Transactions on Neural Networks and Learning Systems, vol. 36, no. 7, pp. 12444-12453, July 2025, doi: 10.1109/TNNLS.2024.3476391.

BibTex
-------
```
@ARTICLE{10759815,
  author={Quadir, A. and Sajid, M. and Tanveer, M.},
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  title={Granular Ball Twin Support Vector Machine}, 
  year={2025},
  volume={36},
  number={7},
  pages={12444-12453},
  doi={10.1109/TNNLS.2024.3476391}}
```

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
The experiments are executed on a computing system running Python 3.11, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128 GB of Random Access Memory (RAM), and Windows 10.

We have put a demo of the “GBTSVM” and “LS-GBTSVM” models with the “chess_krvkp” dataset

The following are the best hyperparameters set with respect to the “chess_krvkp” dataset

Regularization Parameter c_1=0.00001, c_2= 0.00001 

Description of files:

main.py: This is the main file to run selected algorithms on datasets. In the path variable, specify the path to the folder containing the codes and datasets on which you wish to run the algorithm.

gen_ball.py: Generation of granular balls

GBTSVM.py: Solving the optimization problem

Some part of the code is taken from the "Granular Ball Support Vector Machine [1]" paper.
1. Xia, Shuyin, et al. "Gbsvm: Granular-ball support vector machine." arXiv preprint arXiv:2210.03120 (2022).

The codes are not optimized for efficiency. The codes have been cleaned for better readability and documented, and are not exactly the same as those used in our paper. For the detailed experimental setup, please follow the paper. We have re-run and checked the codes only in a few datasets, so if you find any bugs/issues, please write to A. Quadir (mscphd2207141002@iiti.ac.in) or M. Sajid (phd2101241003@iiti.ac.in, sajid.mathml@gmail.com).



           
