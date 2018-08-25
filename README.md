# DRL_Udacity_Navigation_Project
The environment is a 3D space where an AI navigates and attempts to collect yellow bananas and avoid blue bananas.

The state space is of length 37 and the action space is of length 4. The state space details the visual aspect of the 3D space in 1D-tensor format and the actions are move forward, move backward, turn left, and turn right respectively.

An agent with the average score of 13 over the 100 latest epsiodes has been considered to solve the environment!

To run the project in windows, pytorch and unityagents packages must be installed. Pytorch's instructions for downloading are here: https://pytorch.org/ and unityagents instructions for downloading are here: pip install unityagents. You will also need to unzip the folder for the banana.exe as the folder is named at the moment.

The project will be ready to run after all dependencies are met! Training an AI can and probably will use a lot of processing power, so do not be surprised if your computer suddenly is performing more than usual.

This project was heavily based on the source code from the Udacity program. I have made updates to how the agent is updated and the architecture of the neural networks.
