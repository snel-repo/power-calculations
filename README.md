# power-calculations
This notebook reproduces the power calculations in Karpowicz et al., 2024 Figure 1b,c.

We calculate the power of the amplifier using the Noise Efficiency Factor (NEF) formula presented in Steyaert & Sansen 1987, with constants as described in the supplement of Nason et al., Nat BME 2020. 

We calculate the power of the analog-to-digital converter (ADC) by solving the Schreier Figure of Merit (FoMs) formula described in Schreier and Temes 2005, with constants from Nason et al., Nat BME 2020 and Murmann (https://github.com/bmurmann/ADC-survey).