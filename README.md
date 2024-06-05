# QEDynamics (4 component version)

## About
QEDynamics(4 component version) is a Fortran 90 program 
which simulates time evolution of atomic or molecular systems
based on the Rigged QED theory.  
This website introduces the one based on the method which uses 4-component electronic field.

## Documentation
https://mfukudaqed.github.io/Tachibana_Lab_HP/qed/four_component/QEDynamics_e/QEDynamics.html

## Usage
1. Modify the 2nd line of the sample params.ini to `samples/DiracData/STO-3G`

2. Then, 
```
$ ./sim params.ini
```

3. You should get `out.dat` file under QEDynamics4comp.
You may plot the 4th row (charge density at (x,y,z)=(-1,0,0), 
difference from the initial value) against 2nd row (time).

