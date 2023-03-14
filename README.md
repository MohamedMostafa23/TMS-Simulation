# TMS-Simulation

## Simulating a figure 8 Magstim coil for TMS using the eddy current solver

### The magnetic flux density B due to the coils in a vertical cross section
![image](https://user-images.githubusercontent.com/61363974/224866045-68b63d2d-09b7-4093-ad65-1fb8fd4c0dcb.png)


### Arrow Plot of B
![image](https://user-images.githubusercontent.com/61363974/224866094-a3d6e16f-55c5-44ab-aa3d-f082299d2934.png)


### The induced current J in a horizontal cross section of the head showing all layers of the head model
![image](https://user-images.githubusercontent.com/61363974/224866345-69848332-79a6-4cc3-9468-26ca70b01d33.png)


### Arrow Plot of J
![image](https://user-images.githubusercontent.com/61363974/224866415-94aab608-2b82-4b45-a117-eebb26293168.png)


## Removing CSF layer from the brain 

### Magnetic Plot of J
![image](https://user-images.githubusercontent.com/61363974/224866524-ce3a29e1-a696-4b32-9883-135bf831ae49.png)


### Arrow Plot of J
![image](https://user-images.githubusercontent.com/61363974/224866538-6e320b8f-3c1a-47ce-8668-7cc26214b752.png)


## Laws used to simulate the above problem:
Laws that guide this simulation are mainly Maxwell’s equations. First time varying electric current through the coils generate a time varying magnetic field that rotates around the coil guided by ampere’s circuital law. Then this time varying magnetic field induce a curling electric field inside the head guided by faraday’s law.
