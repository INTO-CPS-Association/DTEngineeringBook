---
layout: page
---

The following is a virtual model for calculating the average temperature evolution (ignoring objects within the box). 
The model takes the form of differential equations that describe how temperature evolves in the system[^Feng2021]:

$$ C_{h} \frac{dT_{h}}{dt} =  H_h \cdot P_h - G_{hb} \cdot (T_{h} - T_{b}) $$

$$ C_{b} \frac{dT_{b}}{dt} =  G_{hb} \cdot (T_{h} - T_{b}) - G_{br} \cdot (T_{b} - T_{r}) $$

where $T_{h}$ is the temperature of the heater (measured in $^{\circ}C$), $T_{b}$ is the temperature of the air inside the box ($^{\circ}C$), $T_{r}$ is the room temperature ($^{\circ}C$); $C_{h}$ is the heat capacity of the heater ($\text{J}/(\text{Kg}\cdot^{\circ}C)$) while $C_{b}$ is the heat capacity of the box including contained air ($\text{J}/(\text{Kg}\cdot^{\circ}C)$). The electric power supplied to the heatbed is given by voltage times current $V_h \cdot I_h$ ($\text{W}$), while $H_h$ is a Boolean variable utilised to switch electric power on and off. Finally, $G_{br}$ is a coefficient that models heat transfer between the box and the room ($\text{W}/^{\circ}C$) while $G_{hb}$ is a coefficient that models heat transfer between the heater and the box ($\text{W}/^{\circ}C$).

## Code

The unit test demonstrating the use of the model can be found in [test_four_parameter_model.py](https://github.com/INTO-CPS-Association/example_digital-twin_incubator/blob/master/software/incubator/tests/modelling_tests/test_four_parameter_model.py) with name `test_run_experiment_four_parameter_model_20201221`


## References

[^Feng2021]: Feng, Hao, Cláudio Gomes, Casper Thule, Kenneth Lausdahl, Michael Sandberg, and Peter Gorm Larsen. ‘The Incubator Case Study for Digital Twin Engineering’. arXiv:2102.10390 [Cs, Eess], 20 February 2021. http://arxiv.org/abs/2102.10390.