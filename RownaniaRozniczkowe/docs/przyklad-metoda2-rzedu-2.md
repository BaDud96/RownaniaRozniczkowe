np.
$$ y'' -4y = e^2x $$
Szukamy rozwiązania ogólnego równania liniowego jednorodnego:
$$ y'' -4y = 0 $$
Podstawiamy \( y = e^{\alpha x} \), wtedy:
$$
\alpha^2 - 4 = 0
$$
Zatem:
$$
\alpha^2 = 4
$$
$$
\alpha_1 = 2, \quad \alpha_2 = -2
$$
Rozwiązaniem równania ogólnego jednorodnego będzie:
$$ y = C_1e^{2x} + C_2 e^{-2x} $$
Krotność \(\beta\) wynosi 1 więc przewidywane rozwiązanie równania szczególnego niejednorodnego będzie postaci:

$$
y^* = a \cdot x \cdot e^{2x}
$$

Obliczamy pierwszą pochodną \( y^* \):  

$$
(y^*)' = a \cdot e^{2x} + 2a \cdot x \cdot e^{2x}
$$  
Obliczamy drugą pochodną \( y^* \):  

$$
(y^*)'' = 2a\cdot e^{2x}(2x+2)
$$

Podstawiamy \((y^*)''\) oraz \(y^*\) do naszego równania \( y'' -4y = e^2x \) i wyliczamy z niego wspólczynnik a.  
Otrzymujemy \(a=\frac{1}{4}\), więc \(y^*\) jest postaci:

$$ y^* = \frac{1}{4}xe^{2x} $$  

Ostatecznym rozwiązaniem ogólnym równania liniowego niejednorodnego II-go rzędu jest:
$$ Y = y + y^* = C_1e^{2x} + C_2e^{-2x} + \frac{1}{4}xe^{2x} $$