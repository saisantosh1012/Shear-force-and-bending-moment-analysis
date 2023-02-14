# Shear-force-and-bending-moment-analysis
// Bascially the program is designed for the analysing the point load applied on the beams.
The program results in giving output as bending moment and shear force diagram.

**EXAMPLE PROBLEM**<br>
**INPUT
Length of the beam = 500
length unit = m
Distance of Point load from left end = 200**

**Output**
 
As per the static equilibrium, net moment sum at either end is zero

Reaction R1 = 900.0 kn,

Also Net sum of vertical forces is zero, 

hence R1+R2 = 600.0 kn.


Shear Force at x (x<200.0), Vx = R1 =900.0 kn
             at x (x>200.0), SF = R1 - P = 900.0 - 1500.0 = --600.0 kn

Bending Moment at x (x<200.0), Mx = R1*x = 900.0*x
               at x (x>=200.0), Mx = R1*x - P*(x-200.0) 
                                = 900.0x - 1500.0(x-200.0) = -600.0x + 300000.0

Maximum Shear Force Vmax = 900.0 kn
maximum BM, Mmax = 179879.88 knm
maximum BM at x = 200.2 m

**OUTPUT FIGURE**
<img width="553" alt="image" src="https://user-images.githubusercontent.com/103347778/218680885-49ab843e-2f37-48ff-8f86-1c8166941a49.png">

