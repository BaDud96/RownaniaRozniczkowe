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