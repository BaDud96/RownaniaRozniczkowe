np.
$$ y' - tgx \cdot y = cosx $$
Rozwiązujemny równanie ogólne liniowe jednorodne  
$$ y' - tgx \cdot y = 0 $$
$$ y' = tgx\cdot y $$
$$ \frac{dy}{dx} = tgx\cdot y $$
$$ \frac{dy}{y} = tgx\cdot dx $$
$$ \int {\frac{dy}{y}} = \int {tgxdx} $$
$$ \int {\frac{dy}{y}} = ln|y| + c $$
$$ \int {tgxdx} = \int {\frac{sinx}{cosx}dx} = //t=cosx, dt=-sinxdx// = -\int {\frac{1}{t}dt} = -ln|t| + c = -ln|cosx| + c $$
$$ ln|y| = -ln|cosx| + c_1 $$
$$ ln|y| = -ln|cosx| + lne^{c_1} $$
$$ ln|y| = lne^{c_1} - ln|cosx| $$
$$ ln|y| = ln{\frac{e^{c_1}}{|cosx|}} $$
$$ e^{c_1} = C$$
$$ y = \frac {C}{cosx} $$
Rozwiązujemy równanie szczególne niejednorodne:  

$$ y^* = \frac{C(x)}{cosx} $$

$$ (y^*)' - tgx \cdot y^* = cosx $$ 

$$ C'(x) = (cosx)^2 $$

$$ C(x) = \int (cosx)^2 = \frac {1}{4} (sin2x+2x) $$

$$ y^* = \frac{\frac {1}{4} (sin2x+2x)}{cosx} $$

$$ Y = y + y^* = \frac {C}{cosx} + \frac{\frac {1}{4} (sin2x+2x)}{cosx} = \frac{\frac {1}{4} (sin2x+2x)+C}{cosx} $$