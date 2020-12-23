# Planck-Function
The program investigates Planck's Function

Anthony Dawson 2020 Planck Function.ipynb
___
The following code:

Firstly prints the value of $U(f,T)$ for a user inputted frequency

Secondly gives a plot of Rayleigh-Jeans law over a range of frequncies to show that this leads to the Ultraviolet catastrophe. Using the formula $$U(f, T) = \frac{8 \pi f^{2}}{c^3}{kT}$$

Thirdly the program gives a plot of Planck's function for Temperatures of 2000K, 3000K, 4000K, 5000K, 6000K alongside Rayleigh-Jeans plot

Fourthly the program finds the peak of the Planck function for each temperature and its corresponding frequency. Using this the function then calculates the wavelength at this peak and uses it to estimate the constant in Wien's displacement law

Finally the programme performs integrals of the Planck function for temperatures of 2000K, 4000K, and 6000K using trapezoidal and Simpson methods. The programme then evaluates if these are proportional to $T^4$ from Stefan Boltzmanns law $ I = \sigma T^4$
___

Boltzmann constant k = 1.38e-23 JK^-1

speed of light c = 3.0e8 ms^-1

Planck's constant = 6.63e-34 m^2 kg/s

___

1. Calculate the value of U(v,T)
2. Plot Rayleigh Jeans Law
3. Plot Planck's function 
4. Plot for 5 different temperatures with Rayleigh Jeans on same plot
5. Find the peak of the Planck function for each temperature
6. Find frequncy at each peak
7. Use $c=f\lambda$ to find wavelength at peak
8. Calculate constant
9. Compute areas under curves using trapezoid rule
10. Compute areas under curves using Simpson's rule
11. Check proportionality with $T^4$
