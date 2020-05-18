# Guassian Graphical Model
GMM original code : equSA

Need gcc to compile the main code: equSA.c

step 1: module load gcc

step2 : gcc equSA.c -lm -o equSA

step3: ./equSA

Some key parameters in equSA.c

DataNum=500, DataP=200, MaxNei=21;

ALPHA1=0.2, ALPHA2=0.05;

MAX_NUM=2000000, GRID=2, mingrid=2;



Also available on R CRAN : https://github.com/BochaoJ/equSA and https://cran.r-project.org/web/packages/equSA/index.html
