# Opis zmiennych rozdzielonych

Równania różniczkowe o **zmiennych rozdzielonych** to jedna z najprostszych klas równań różniczkowych I rzędu. Ich cechą charakterystyczną jest możliwość przekształcenia równania do postaci, w której zmienne niezależna \(x\) i zależna \(y\) są rozdzielone po przeciwnych stronach równania.

## 🔹 Postać ogólna

Równanie ma postać:
$$
\ \ y'= f(x)\cdot g(y)  \  
$$
Można je zapisać także jako:
$$
\ \frac{dy}{dx} = f(x) \cdot g(y) \
$$
Mnożymy obustronnie razy **dx** i dzielimy przez **g(y)**, otrzymujemy:
$$
 \ \frac{dy}{g(y)}= f(x)\cdot dx \
$$

i całkujemy obustronnie:
$$
\ \int \frac{dy}{g(y)} = \int f(x)\cdot dx \
$$
Rozwiązaniem będzie rodzina funkcji:
$$
\ G(y) = H(x)+C \
$$

## 🔸 Aby zastosować tę metodę:
- funkcje \(g(y)\) i \(f(x)\) muszą być ciągłe,
- \(g(y) \neq 0\) w dziedzinie rozwiązania,
- da się wyodrębnić \(dy\) i \(dx\) po przeciwnych stronach.

## 📘 Interpretacja geometryczna
Wartości \( \frac{dy}{dx} \) można traktować jako nachylenia stycznych do wykresu funkcji \(y(x)\). Rozdzielenie zmiennych pozwala „rozłożyć” to nachylenie na składniki zależne od \(x\) i \(y\), co umożliwia łatwiejszą analizę i rozwiązanie równania.

## 📌 Podsumowanie
Metoda rozdzielania zmiennych to jedno z najbardziej podstawowych, ale i potężnych narzędzi w rozwiązywaniu równań różniczkowych. Jest często punktem wyjścia w analizie bardziej złożonych zjawisk.
