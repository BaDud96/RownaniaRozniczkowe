## Równanie różniczkowe I-go rzędu **zupełne**
to równanie postaci:  
$$
P(x,y) + Q(x,y)\frac{dy}{dx} = 0,
$$
w którym funkcje P(x,y) i Q(x,y) są ciągłe w pewnym obszarze D i takie, że:
$$
P(x,y)dx + Q(x,y)dy
$$
jest różniczką zupełną pewnej funkcji dwóch zmiennych F(x,y) określonej w obszarze D, w każdym punkcie tego obszaru zachodzą związki:
$$
\frac{dF}{dx} = P(x,y), \frac{dF}{dy} = Q(x,y)
$$
Warunkiem koniecznym i wystarczającym na to, aby wyrażenie było różniczką zupełną w tym obszarze, jest spełnienie równości:
$$
\frac{dQ}{dx} = \frac{dP}{dy},
$$
Jeśli ten warunek jest spełniony w pewnym obszarze \( D \subset \mathbb{R}^2 \), to istnieje funkcja \( F(x, y) \), której różniczka daje wyjściowe równanie.  
  
  Jeśli zachodzi: 
$$\frac{dQ}{dx} \neq \frac{dP}{dy},
$$
to warunek nie jest spełniony i wyrażenie nie jest różniczką zupełną. Może istnieć jednak taka funkcja \( \mu(x, y) \) w rozpatrywanym obszarze, że jeśli pomnożymy przez nią obie strony równania, to otrzymane w ten sposób równanie:
$$
\mu(x,y) P(x,y) + \mu(x,y) Q(x,y)\frac{dy}{dx} = 0
$$
jest już równaniem zupełnym.
---
## 🛠️ Rozwiązywanie
Sprawdzamy warunek zupełności: 
$$
\frac{dQ}{dx} = \frac{dP}{dy}
$$
### ✅ Jeśli warunek jest spełniony:
  1. Znajdujemy funkcję pierwotną \( F(x, y) \), taką że:
  $$ \frac{dF}{dx} = P(x, y)$$ 
  2. Całkujemy względem \(x\)
  3. Dodajemy funkcję \( h(y) \) jako „stałą całkowania”
  4. Różniczkujemy wynik względem \( y \), aby określić \( h(y) \) na podstawie \( Q(x, y) \)
  
### ❗ Gdy warunek zupełności nie jest spełniony:
1. Próbujemy przekształcić równanie do postaci zupełnej przez **mnożenie przez czynnik całkujący** \( \mu(x, y) \)  
2. Czynnik \(\mu\) powinien zależeć tylko od \(x\) lub tylko od \(y\), aby uprościć poszukiwania  
3. Po przemnożeniu sprawdzamy, czy nowe funkcje \( \mu P \) i \( \mu Q \) spełniają warunek zupełności:
$$
  \frac{d(\mu Q)}{dx} = \frac{d(\mu P)}{dy}
$$
4. Jeśli tak, możemy rozwiązać tak jak równanie zupełne

### Ostateczne rozwiązanie ma postać:
$$
F(x, y) = C
$$

---
Przejdź do praktyki: [zobacz przykład](przyklad-metoda4-rzedu-1.md)