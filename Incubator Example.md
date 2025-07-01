---
layout: page
title: Incubator Example
---

The example is actively maintained in the its [own dedicated repository](https://github.com/INTO-CPS-Association/example_digital-twin_incubator).

And most of the individual examples used in the book have been implemented in the [practical course materials](https://github.com/clagms/IncubatorDTCourse).
The reader can either follow the jupyter notebooks in sequence, or consult the reference below for a mapping between the book examples and the course materials.

## Part I - Foundations

### 3.4 Models & Data - Incubator Temperature Virtual Model

The online [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/3-Physics-Modelling/2-ModellingIncubatorDynamics.ipynb) shows the creation of the model and its simulation.

## Part II - Models and Data

### 5.4.1 Ordinary Differential Equations

The online [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/3-Physics-Modelling/2-ModellingIncubatorDynamics.ipynb) shows the creation of the model and its simulation, from the [incubator dt practical course](https://github.com/clagms/IncubatorDTCourse).

### 5.5.2 Artificial Neural Networks - Incubator Neural Network

The online [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/3-Physics-Modelling/4-TrainingIncubatorNN.ipynb) contains a complete example from the [incubator dt practical course](https://github.com/clagms/IncubatorDTCourse).

### 5.6.1 Finite State Machines - Incubator Controller FSM

The incubator finite state machine can be found in this online [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/2-Controller-Modelling/1-State-Machines-FMI.ipynb) from the [incubator dt practical course](https://github.com/clagms/IncubatorDTCourse)

### 5.7.1 Co-Simulation

An example co-simulation is constructed in the last part of [this jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/3-Physics-Modelling/2-ModellingIncubatorDynamics.ipynb).

### 6.4.3 Calibration of Differential Equations

An example calibration is demonstrated in [this jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/4-Calibration/4-CalibratingIncubatorDynamics.ipynb).

### 7.6.1 Sensor Fusion - Kalman Filter

An example application of a Kalman filter in the incubator is demonstrated in [this jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/7-SoftwareSensing/2-Example_KF_Incubator.ipynb).

As a bonus, there is also a [simplified particle filter](https://github.com/clagms/IncubatorDTCourse/blob/main/7-SoftwareSensing/3-Example_PF_Incubator.ipynb).

### 7.5 Storing Data in Time-Series Databases

The setup of the timeseries database for the incubator is illustrated in [this jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/0-Pre-requisites/4-InfluxDB.ipynb).

## Part III - Services for Digital Shadows and Digital Twins

### 8.3 Visualisation Services in a Digital Twin

The setup of the timeseries database and dashboard for the incubator is illustrated in [this jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/0-Pre-requisites/4-InfluxDB.ipynb).

The 4D visualization of the incubator is constructed in this tutorial:
1. [GodotIntro](https://github.com/clagms/IncubatorDTCourse/blob/main/9-Visualisation/1-GodotIntro.html)
2. [IncubatorViz](https://github.com/clagms/IncubatorDTCourse/blob/main/9-Visualisation/2-IncubatorViz.html)
3. [IncubatorShadow](https://github.com/clagms/IncubatorDTCourse/blob/main/9-Visualisation/3-IncubatorShadow.html)

## 9.1 Incubator Monitoring

The last part of the following [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/7-SoftwareSensing/2-Example_KF_Incubator.ipynb) illustrates how a Kalman Filter is used to detect that the lid of the incubator has been openned.

### 9.2.3 Signal Temporal Logic

The following [jupyter notebook](https://github.com/clagms/IncubatorDTCourse/blob/main/8-Monitoring/3-STLMonitoringService.ipynb) illustrates how a temporal logic monitoring tool can be used in the incubator.

### 10.2.1 Design Space Exploration with Conflicting Objectives

The following [unit test](https://github.com/INTO-CPS-Association/example_digital-twin_incubator/blob/master/software/incubator/tests/controller_tunning_tests/test_controller_tunning.py) `test_controller_plot_pareto_front` illustrates the optimization with conflicting objectives and builds the pareto front.

### 10.2.2 Fault Injection

The FI plugin can be found [here](https://github.com/INTO-CPS-Association/fault-injection-maestro).

## Part IV - Realising Digital Shadows and Digital Twins

### 11.2 Digital Twin Frameworks

The DTaaS platform is being developed [here](https://github.com/into-cps-association/DTaaS) and multiple examples, including the [incubator example](https://github.com/INTO-CPS-Association/DTaaS-examples/blob/main/digital_twins/incubator/README.md), are provided [here](https://github.com/INTO-CPS-Association/DTaaS-examples).

