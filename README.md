# INTELFICEOPJU_THIRDYEAR

Model deployment 
https://yogeshraje-irisflowerprediction-app-sar065.streamlit.app/


Command -
Task - convert .ipynb file to .py file 
$ jupyter nbconvert demo_python1.ipynb --to script

Task- executing code on Intel Sklearnex without changing code 
$ python -m sklearnex demo_python.py

Task- -How to target specific GPUs

$qsub -l nodes=1:gpu:ppn=2 run.sh 


Task- -How to target specific FPGA

qsub -l nodes=1:fpga_runtime:arria10:ppn=2 -d . run.sh 

qsub -l nodes=1:fpga_runtime:arria10:ppn=2 -d . run.sh 

qsub -l nodes=1:fpga_runtime:stratix10:ppn=2 -d . run.sh

Task - How to target specific xeon processor
$ qsub -l nodes=1:xeon:ppn=2 run.sh


Patch sklearnex -Intel Extension for Sklearn
from sklearnex import patch_sklearn
patch_sklearn()

Unpatch sklearnex
from sklearnex import unpatch_sklearn
unpatch_sklearn()


#################################################################


Task1) Provide Feedback of 5 days workshop
1)open portal  lms.fice.in and LogIn with your credintials
2)From Menu click on Course and select your collage name O.P. Jindal University - OP Jindal University - Third Year - 2020-2024 batch
3)click on Feedback (Friday, 16 December 2022 ) to provide feedback about 5 days workshop.


+++++++++++++++++++++++++++++++


Task2) Attempt Quiz
1)open portal  lms.fice.in and LogIn with your credintials
2)From Menu click on Course and select your collage name O.P. Jindal University - OP Jindal University - Third Year - 2020-2024 batch
3)Click on Quiz link - Quiz (Phase - 3) 16th DEC 2022

###############################################################################################






