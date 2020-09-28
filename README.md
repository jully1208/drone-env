# drone-env

This README.md file was written from https://github.com/JacopoPan/gym-pybullet-drones/blob/master/README.md

Documentation for running gym-pybullet-drones

Need to install following to run the simulation 

If pip is not installed, run following command: 
$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

Install OpenAI Gym 

$ pip install gym 
$ python3 get-pip.py

To verify that you have installed pip, run:
$ pip3 --version 

Requirements 

You need to install CMake which can be done by following this link: https://cmake.org/download/
Select the correct file according your OS
To add CMake to terminal on a Mac, open the application and go to install for command line use under tools.
Then, click on Install Command Line Links 

Downloading major dependencies:
$ pip install pybullet
$ pip install stable-baselines3
$ pip install 'ray[rllib]'
$ brew install ffmpeg # for Mac, video recording
$ sudo apt install ffmpeg # for Linux, video recording

Installation 

Clone gym-py-bullet-drones git repo to your workspace 

$ git clone https://github.com/JacopoPan/gym-pybullet-drones.git
$ cd gym-pybullet-drones/
$ pip install -e .

Running 2 basic simple scripts - fly.py and learn.py
$ cd gym-pybullet-drones/examples/
$ python fly.py   
$ python learn.py 

