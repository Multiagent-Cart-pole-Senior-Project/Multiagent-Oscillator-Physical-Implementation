# Multiagent-Oscillator-Physical-Implementation
Python code to physically implement the synchronization of two oscillators to a leader using reinforcement learning. This is for the Synchronization of Cart Pole Systems using Reinforcement Learning senior project by Jakob Harig and Ryan Russell.

The oscillator is the preliminary model to test the multiagent synchronization using reinforcement learning for our project as the system is stable. This code is to physically implement the synchronization of two follower oscillators with one virtual leader following a sinusoidal pattern. This code will be run on an NVIDIA Jetson Nano, communicating through XBee modules, getting position and velocity data from an ultrasonic sensor, and driving all motors on the oscillator with the same PWM signal. 

### Multiagent_Oscillator_1.py and Multiagent_Oscillator_2.py:
  
  Description: This python code implements the synchronization of oscillators, to be run on an NVIDIA Jetson Nano, using an online reinforcement learning controller, utilizing a radial basis function. This then outputs the results of testing to a mat file to be plotted and evaluated using MATLAB.

  Terminal prompt to run on Cart 1:
  
    sudo python3 Multiagent_Oscillator_1.py
    
  Terminal prompt to run on Cart 2:
  
    sudo python3 Multiagent_Oscillator_2.py
  
  Output File on both Cart 1 and Cart 2:
  
    Oscillator_Results_{time}.mat

### Implementation

### Results

##### Plots

##### Video

### Conclusion
