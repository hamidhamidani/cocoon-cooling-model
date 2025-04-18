Author: Hamidani
Date: 18/04/2025

Model based on Hamidani & Ioka (2021, 2023a, 2023b, 2024a, 2025a, 2025b).

This code uses the parameters of:
- Jet: energy (E_eng), engine timescale (t_eng), opening angle (theta_0)
- Ambient medium: radius (R_a), mass (M_a), density profile (n = 2 by default)

It calculates:
1. Jet propgation through the ambient medium
2. The cooling emission from the cocoon 
It outputs flux for different observer times and frequency bands.

Notes:
1. Default values are for EP250108a.
2. Jet/CSM parameters are based on GRB060218 due to its similarity to EP250108a.
3. To speed up the run, adjust `n1` and `n2` (time grid), and the `nu_values` array (frequencies).
4. The main paramters are: 
E_eng (jet total energy)
M_a (CSM mass)
R_a (CSM radius)
opacity (thomson scattering opacity)
