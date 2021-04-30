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

           lambda     = 8e-7 ;      % [m]
           beam_waist = 0.00075 ;    % [m] 
           wp         = -0.1 ;      % [m] 
           fpos       = [0 0.1]     % [m] 
           f          = [-0.5 0.2]; % [m]
           
           Gaussian_Propagation(lambda,beam_waist,wp,fpos,f,show_flag)
          
           
           
![Fig1](https://github.com/adinatan/Gaussian_Propagation/blob/master/gp.png)
