## Run Examples on BlueHive cluster

This is an routine on how to setup and run codes in this reponsitory.

### Setup and Test

* Step 0: Go to Github: https://github.com/sischei/global_solution_methods_Rochester

        Download and unzip to your mian folder, the name would be global_solution_methods_Rochester-master

* Step 1: [setup] Go to /home/mfang2(Your NetID)/global_solution_methods_Rochester-master/Lecture_1/SparseGridCode

Install necessary packages (IPOPT is preinstalled by CIRC stuff for us, so I commented it out in install_SG.sh)   
    
$: cd global_solution_methods_Rochester-master/Lecture_1/SparseGridCode

$: sh install_SG.sh

* Step 2: in terminal, before you run any code 

$: module load ipopt/3.12.12/b2

* Step 3: [first time] go to current path to test if IPOPT works, run the test example, should be very quick

$: cd global_solution_methods_Rochester-master/Lecture_1/SparseGridCode

$: python hs071.py

### Running Examples

* Step 1: open terminal, before you run any code 

$: module load ipopt/3.12.12/b2

* Step 2: go to example folders to tun the code. (it takes time to solve, so just be patient)

$: cd global_solution_methods_Rochester-master/Lecture_1/SparseGridCode/growth_model/serial (or other example folders)

$: python main.py

*for all other questions of running issues on BlueHive, email me at min.fang@rochester.edu or CIRC@rochester.edu

Let's enjoy the lecture,
Ethan

