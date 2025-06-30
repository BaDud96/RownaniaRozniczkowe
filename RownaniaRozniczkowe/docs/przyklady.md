Rozwiążmy przykład:
$$
y' = x \cdot tgy
$$
$$
\frac{dy}{dx} = x \cdot tgy\ 
$$
$$
\frac{1}{tgy}dy = xdx\  
$$
$$
\int \frac{1}{tgy}dy = \int xdx \
$$
teraz rozwiązujemy całkę po lewej stronie  
$$
\int \frac{1}{tgy}dy = \int \frac{cosy}{siny}dy \
$$
aby rozwiązać tą całkę stosujemy podstawienie t = siny, dt = cosy dy, otrzymujemy:  
$$
\int \frac{1}{tgy}dy = \int \frac{cosy}{siny}dy = \int \frac{1}{t}dt = ln|t| + c = ln|siny| + c \
$$
teraz rozwiązujemy całkę po prawej stronie  
$$
\int xdx = \frac{1}{2}x^2 + c\  
$$
zgodnie z opisaną metodą stosowaną do [równań I-go rzędu o zmiennych rozdzielonych](metoda1-rzedu-1.md)  
$$
ln|siny| = \frac{1}{2}x^2 + c\  
$$
$$
ln|siny| = \ln\left(e^{\frac{1}{2}x^2}\right) + lne^c = \ln\left(e^{\frac{1}{2}x^2}\right) \cdot e^c \
$$
ale \(e^c\) to jakaś liczba, stała więc zatąpimy to jedną stałą C 
opuszczając logarytm naturalny otrzymujemy:  
$$
siny = C \cdot e^{\frac{1}{2}x^2}\
$$
rozwiązaniem jest uzyskanie funkcji y(x), więc ostatecznie mamy:  
$$
 y = arcsin(C \cdot e^{\frac{1}{2}x^2})\
$$

🔙 [Powrót do opisu](metoda1-rzedu-1.md)  

np. $$ y'' + 4y' + 4y = 0 $$
po podstawieniu \(y=e^{\alpha x}\) i podzieleniu przez \(e^{\alpha x}\), otrzymujemy:  
$$ {\alpha}^2 + 4\alpha + 4 = 0 $$
$$ \Delta = 16 - 16 = 0 $$
więc będzie jeden podwójny pierwiastek \(\alpha\)  
$$ \alpha = -4 / 2 = -2 $$
więc zgodnie z teorią opisaną [tutaj](metoda1-rzedu-2.md)  
rozwiązanie będzie postaci:
$$ Y=C_1 \cdot e^{\alpha x} + C_2 \cdot x\cdot e^{\alpha x} $$
więc ostatecznie dla naszego przykładu mamy:  
$$ Y=C_1 \cdot e^{-2x} + C_2 \cdot x\cdot e^{-2x} $$  
$$
y' + x \cdot y = 0
$$
$$
\frac{dy}{dx} = -x \cdot y\
$$ 
$$
\frac{dy}{y} = -x \cdot dx\
$$
$$
\int \frac{dy}{y} = \int -x \cdot dx\
$$
$$
 ln|y| = -\frac{1}{2}x^2 + c\
 $$
$$
ln|y| = \ln\left(e^{-\frac{1}{2}x^2}\right) + lne^c\
$$
$$
ln|y| = \ln\left(e^{-\frac{1}{2}x^2} \cdot e^c\right)\
$$  
ale \(e^c\) to stała, którą oznaczymy C,    
więc po opuszczeniu logarytmu naturalnego otrzymujemy:  
$$
y = C \cdot e^{-\frac{1}{2}x^2}\
$$
Jest to rozwiązanie ogólne jednorodne.  

🔙 [Powrót do opisu](metoda2-rzedu-1.md)  
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
\int (3x^2 + 6xy^2) \, dx = x^3 + 3x^2y^2 + h(y)
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
\int h'(y) = y^4
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
