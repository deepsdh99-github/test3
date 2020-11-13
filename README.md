# ------------------ Project Overview ------------------

## Abstract

This project is regarding test recommendation for LALPATH client. There are 3 main tasks mentioned below:

1. Must visit client, as per PJP
2. Test recommendation, for each client
3. Credit limit, calculation for each client

# ------------------ Create Environment ------------------

## Download Anaconda

1. $ cd ~
2. $ mkdir tmp
3. $ cd tmp
4. $ curl -O https://repo.continuum.io/archive/Anaconda3-2020.07-Linux-x86_64.sh

## Run the bash script to install Anaconda3

Now we can run the script:

1. $ bash Anaconda3-2020.07-Linux-x86_64.sh

Accept the Licence Agreement and allow Anaconda to be added to your PATH. By adding Anaconda to your PATH, the Anaconda distribution of Python will be called when you type $ python in a terminal.

## Activate the installation

1. $ source ~/.bashrc

## Setting Up Anaconda Environments

1. $ conda create -n py36 python=3.6
2. $ conda activate py36
3. $ pip install -r requirements.txt

# ------------------ Steps to run through ------------------

## Run MONTHLY once (2nd date of every month, after getting last month full data)

1. $ cd API_new/
2. $ conda activate py36
3. python ./recommendation.py

## Run DAILY once

1. $ cd API_new/
2. $ conda activate py36
3. python ./run.py