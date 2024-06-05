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

## LISENCE, Terms of use
1. No Redistribution :  
    You are not allowed to redistribute QEDynamics (4 component version) in any form.

1. No Commercial Use :   
    You may not use QEDynamics (4 component version)) for any commercial purposes without prior written consent from us.

1. No Warranty :  
    The program represents experimental code and there is no warranty of correctness of results.

1. Citation :  
    Any use of QEDynamics (module for Dirac) that results in published material should cite the following: 
    ''QEDynamics (module for Dirac) (2023), written by M. Senami, K. Ichikawa, A. Tachibana  
    with contributions from M. Fukuda and K. Soga,  
    (https://github.com/mfukudaQED/QEDynamics4comp)''

1. Contact:  
    Masahiro Fukuda masahiro.fukuda__at__issp.u-tokyol.ac.jp
