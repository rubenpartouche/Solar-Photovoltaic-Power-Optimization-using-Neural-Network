# Solar-Photovoltaic-Power-Optimization-using-Neural-Network

The goal of this project is to construct and train a neural network predicting solar PV panel power output from any data set of operating conditions (outside air temperature, solar radiation intensity, load resistance). Then, we developed and evaluated a machine-learning based model to determine which panels configuration (series/parallel) of a solar PV system would maximize the power output for a given set of input operating conditions. 

## Part 1 

![image](https://user-images.githubusercontent.com/116780853/204201238-49c59c40-75d4-404c-a408-cc8da627f61a.png)

Part 1 of this project considers the performance of the solar panel design show above. The panel
contains 72 solar cells connected in series, each with an area of 173 cm2. Performance test data for this type of unit is provided as a dataset that includes the following performance parameters:

Specified operating parameters:
- Outside air temperature, Tair (°C)
- Incident direct normal solar radiation intensity, ID (W/m2)
- Load resistance, RL (Ohms)

Performance (output) parameters:
- Panel output voltage to load VL (V)
- Panel power output W! (W)

We have a dataset with input data parameters [Tair,ID,RL] provided for this project. 

## Part 2 

Part 2 of this project consider a solar PV system comprised of solar panels of the type decribed in Part 1. They will be installed in a close-spaced rectangular array, but will be wired with switches so it is possible to connected the four in parallel (mode 0), 2x2 in series/parallel (mode 1), or with the four in series (mode 2). As shown below, these changes combine the V-I characteristics of the individual modules to produce three very different overall system V-I characteristics.

![image](https://user-images.githubusercontent.com/116780853/204202370-01ea3d95-8762-44f3-91cc-03a4022f5ba0.png)
