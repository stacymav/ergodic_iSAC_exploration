# ergodic_iSAC_quadrotor
C++ code implementing ergodic iSAC: an ergodic control algorithm that uses complex agent dynamics to explore a varying probability-of-detection distribution in real time. The current implementation uses 12-dimensional quadrotor dynamics to explore a Gaussian distribution  with the peak performing a circular motion. See videos of the results here: https://vimeo.com/stacymav

# Dependencies
The code requires the Boost and Eigen libraries.

# To compile and run
	--- Update Makefile.txt with local Boost and Eigen paths
	--- "make Quad_Euler.cpp"
	--- Run Quad_Euler.exe
	--- Plot resulting trajectories in Matlab, using ./data/plots_matlab.m

# Customization
All possible changes, e.g. agent dynamics, explored distribution, additional performance cost etc., can be made by updating the files included in the "user" folder.







