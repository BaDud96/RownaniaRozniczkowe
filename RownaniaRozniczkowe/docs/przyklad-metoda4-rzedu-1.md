Rozwiążmy równanie:
$$
(3x^2 + 6xy^2)\,dx + (6x^2y + 4y^3)\,dy = 0
$$

Identyfikujemy funkcje
Mamy:
$$
P(x, y) = 3x^2 + 6xy^2 
$$
$$
Q(x, y) = 6x^2y + 4y^3 
$$

Obliczamy pochodne cząstkowe:
$$
\frac{dP}{dy} = 12xy
$$ 
$$
\frac{dQ}{dx} = 12xy
$$
$$
\frac{dP}{dy} = \frac{dQ}{dx}
$$
Zatem warunek zupełności jest spełniony. 

Znajdujemy funkcję pierwotną \(F(x, y)\):  
Całkujemy \(P(x, y)\) względem \(x\):
$$
(3x^2 + 6xy^2) \, dx = x^3 + 3x^2y^2 + h(y)
$$

Wyznaczenie \( h(y) \)
Obliczamy pochodną \(F(x, y)\) względem \(y\):
$$
\frac{dF}{dy} = 6x^2y + h'(y)
$$
Porównujemy z \(Q(x, y)\):  
$$
6x^2y + h'(y) = 6x^2y + 4y^3 
$$ 
$$
h'(y) = 4y^3
$$ 
$$
h(y) = y^4
$$

Zapisujemy rozwiązanie ogólne
$$
F(x, y) = x^3 + 3x^2y^2 + y^4 = C
$$

Ostateczne rozwiązanie równania:
$$
x^3 + 3x^2y^2 + y^4 = C
$$
$$
(3x^2 + 6xy^2)dx + (6x^2y + 4y^3)dy= 0 
$$