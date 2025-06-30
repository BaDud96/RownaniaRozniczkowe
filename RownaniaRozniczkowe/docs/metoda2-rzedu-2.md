Jeżeli równanie różniczkowe jest postaci:  
$$
y'' + p \cdot y' + q \cdot y = f(x)
$$
to postępujemy według schematu:  

- Znajdujemy rozwiązanie **ogólne równania liniowego jednorodnego II-go rzędu** [(opis)](metoda1-rzedu-2.md), czyli  
$$
y'' + p \cdot y' + q \cdot y = 0
$$  


- wyznaczamy rozwiązanie **szczególne \(y^*\) równania liniowego niejednorodnego II-go rzędu**
- rozwiązaniem **ogólnym równania liniowego niejednorodnego II-go rzędu** będzie suma rozwiązania ogólnego jednorodnego II-go rzędu i rozwiązania szczególnego niejednorodnego II-go rzędu, a więc 
$$
Y = y + y^*
$$  

Rozwiąznie szczególne równania liniowego niejednorodnego II-go rzędu- czyli \(y^*\) - wynaczamy **metodą przewidywania**. W naszym kursie zajmiemy się przypadkiem, kiedy \(f(x)\) z naszego równania do rozwiązania jest postaci:
$$ f(x) = e^{\beta x} \cdot P_n(x) $$
wobec czego, przewidywane \(y^*\) będzie wyglądało nastepująco:
$$ y^* = x^k e^{\beta x} W_n(x) $$
gdzie k - to krotność \(\beta\) w równaniu charakterystycznym.
Zobaczmy to na [przykładzie](przyklad-metoda2-rzedu-2.md)  