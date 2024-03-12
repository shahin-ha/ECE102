# ECE102

## Curve fitting
The current equation for the MOSFET in a sturation mode is: (The channel modulation effect could be ignored for the first order approximatoin)
$I_{ds}=\frac{1}{2}C_{ox}\mu_{n}\frac{W}{L}(V_{gs}-V_T)^2\:(1+\lambda Vds) ≃ \frac{1}{2}C_{ox}\mu_{n}\frac{W}{L}(V_{gs}-V_T)^2$ 

The equation could be written as:
$I_{ds}=K(V_{gs}-V_T)^2$ where $K=\frac{1}{2}C_{ox}\mu_{n}\frac{W}{L}$.
The sqr function in code is in this form and objetive is to find value of K and $V_T$ that fit the experimental data.
