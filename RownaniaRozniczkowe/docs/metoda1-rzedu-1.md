## Równanie różniczkowe pierwszego rzędu **o zmiennych rozdzielonych** to takie, które można zapisać w postaci:  
$$
y' = f(x) \cdot g(y)
$$
Można w nim oddzielić zmienne, pogrupować y na lewo, x na prawo, pamiętając, że y' = dy/dx : 
$$
\frac{dy}{dx} = f(x) \cdot g(y)
$$
teraz dzielimy przez **g(y)** i mnożymy przez **dx**, otrzymujemy :
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

## 🔸 Aby zastosować tę metodę:
- funkcje \(g(y)\) i \(f(x)\) muszą być ciągłe,
- \(g(y) \neq 0\) w dziedzinie rozwiązania,
- da się wyodrębnić \(dy\) i \(dx\) po przeciwnych stronach.

## 📘 Interpretacja geometryczna
Wartości \( \frac{dy}{dx} \) można traktować jako nachylenia stycznych do wykresu funkcji \(y(x)\). Rozdzielenie zmiennych pozwala „rozłożyć” to nachylenie na składniki zależne od \(x\) i \(y\), co umożliwia łatwiejszą analizę i rozwiązanie równania.