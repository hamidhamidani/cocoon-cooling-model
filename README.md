Author: Hamidani
Date: 06/05/2025

Model based on Hamidani & Ioka (2021, 2023a, 2023b, 2024a, 2025a, 2025b).

This code uses the parameters of:
- Jet: energy (E_eng), engine timescale (t_eng), opening angle (theta_0)
- Ambient medium: radius (R_a), mass (M_a), density profile (n = 2 by default)

It calculates:
1. Jet propgation through the ambient medium
2. The cooling emission from the cocoon 
It outputs flux for different observer times and frequency bands.

Notes:
1. Default values are for EP250108a (redshift, distance etc., please adjust).
2. Jet/CSM parameters are also set for EP250108a (please adjust).
3. To speed up the run, adjust `n1` and `n2` (time grid), and the `nu_values` array (frequencies).
4. The main paramters are: 
E_eng (jet total energy)
M_a (CSM mass)
R_a (CSM radius)
opacity (Thomson scattering opacity)
5. The other jet parameters can be adjusted manually

# MIT License
This code is free to use, modify, and distribute under the MIT License.
Please cite the following paper(s) if you use this code in your work:
Hamidani et al. 2025a, 2025b
