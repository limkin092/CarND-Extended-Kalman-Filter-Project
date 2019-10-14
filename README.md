# Extended-Kalman-Filter
Udacity CarND Term 2, Project 1 - Extended Kalman Filters

## Project Basics
In this project, I used C++ to write a program taking in radar and lidar data to track position using Extended Kalman Filters.

The code will make a prediction based on the sensor measurement and then update the expected position. See files in the 'src' folder for the primary C++ files making up this project.

## Build instructions
Assuming you have 'cmake' and 'make' already:
1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./ExtendedKF`

## Results
In two different simulated runs, my Extended Kalman Filter produces the below results. The x-position is shown as 'px', y-position as 'py', velocity in the x-direction is 'vx', while velocity in the y-direction is 'vy'. Residual error is calculated by mean squared error (MSE).

*Test*

| Input |   MSE   |
| ----- | ------- |
|  px   | 0.0972256 |
|  py   | 0.0853761 |
|  vx   | 0.450855 |
|  vy   | 0.439588 |
