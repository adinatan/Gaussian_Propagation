# Gaussian_Propagation

propagates a Gaussian beam through a series of lenses. (All units are metric)

Input:
    lambda         beam's wavelength
    beam_waist     waist of the beam at the waist positions (wp)
    wp             waist position
    fpos           lenses positions vector [pos1, pos2, pos3 ...]
    f              lenses focal-lengths vector [f1, f2, f3 ...]
    show_flag      prints text on figure with waist positions and sizes
 
Example:
           Gaussian_Propagation(8e-7,0.00075,-0.1,[0 0.1],[-0.5 0.2])
           
           
![Fig1](https://github.com/adinatan/Gaussian_Propagation/fig1.png)
