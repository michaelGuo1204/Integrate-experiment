- Linear functions, which means the rate is constant, don't fit very well. Exponetial functions which imply the rate is proportional to substrate concentration, fit a bit better.

- If the rate complies with MM equation
  $$
  \dfrac{\mathrm{d}c}{\mathrm{d}t}=v_m\cdot c/(c+k_s)
  $$
  we integrated it and failed to drive a meaningful result, because either $R^2$ is low or $K_s$ is negative or unrationally large.

- We also assume that when enzyme concentration is large, only part of the enzyme molecules bind to the substrate. The "effective" enzyme concentration is proportional to the substrate concentration. This can also be verified by modifying the derivation of MM equation. Thus
  $$
  \dfrac{\mathrm{d}c}{\mathrm{d}t}=k_{cat}\cdot c^2/(c+k_s)
  $$
  However, this also failed because $K_s$ is negative or too large, which leads that lower substrate concentration makes higher rate.

- The last three fits are just based on similar curve shape. We cannot explain them.



       p1 =   2.456e-06  (2.295e-06, 2.617e-06)
       p2 =   -0.001864  (-0.001921, -0.001807)
       p3 =      0.9788  (0.9745, 0.9831)
    
       p1 =   1.204e-06  (1.088e-06, 1.319e-06)
       p2 =  -0.0009488  (-0.0009913, -0.0009063)
       p3 =      0.9163  (0.9129, 0.9196)
    
       p1 =       9e-07  (8.382e-07, 9.617e-07)
       p2 =   -0.001099  (-0.001131, -0.001066)
       p3 =      0.9537  (0.9501, 0.9574)

$$
\begin{gather*}
	EnzymeActivity(\text{单位体积活力},\mathrm{U\cdot mL^{-1}})=\dfrac{OD_{420}(120\mathrm{s})-OD_{420}(60\mathrm{s})}{0.5\mathrm{mL}}\times 10^{3}\\
	SpecificActivity(\text{比活力},\mathrm{U\cdot g^{-1} })=\dfrac{EnzymeActivity}{Enzyme Concentration(\mathrm{g\cdot mL^{-1}})}
\end{gather*}
$$




