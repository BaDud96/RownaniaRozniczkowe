Równanie różniczkowe pierwszego rzędu **o zmiennych rozdzielonych** to takie, które można zapisać w postaci:  
$$
y' = f(x) \cdot g(y)
$$
Można w nim oddzielić zmienne, pogrupować y na lewo, x na prawo, pamiętając, że y' = dy/dx : 
$$
\frac{dy}{dx} = f(x) \cdot g(y)
$$
teraz dzielimy przez g(y) i mnożymy przez dx, otrzymujemy :
$$
\frac{dy}{g(y)} = f(x)dx
$$
całkujemy obustronnie
$$
\int \frac{dy}{g(y)} \ = \int f(x)\,dx
$$
Obliczamy całki i tak przekształcamy równanie, żeby uzyskać postać y = H(x) + C.  
Rozwiązaniem będzie **rodzina funkcji y = H(x) + C**, różniąca się stałą C, czyli tzw. **rozwiązanie ogólne**.  
Jeżeli w zadaniu będzie podany **warunek poczatkowy Cauchy'ego y(x0) = y**, to podstawiając go do równania ogólnego otrzymamy **rozwiązanie szczególne**.  
