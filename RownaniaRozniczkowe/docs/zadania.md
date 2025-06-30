#Ćwiczenia do samodzielnego rozwiązania

Poniżej znajdziesz zestaw 14 zadań – po dwa dla każdej omawianej metody, dodatkowo dwa dla zupełnych z czynnikiem całkującym. Podpowiedzi są ukryte i można je rozwinąć klikając w tytuł.

---

## 🔹 Zmiennych rozdzielonych

**Zadanie 1**  
\(
\frac{dy}{dx} = \frac{xy}{1 + y^2}
\)  

??? info "Pokaż rozwiązanie"
    Rozdzielamy:
    \(
    \frac{1 + y^2}{y} dy = x dx
    \)  
    \(
    \int \left(1 + \frac{1}{y^2}\right) dy = \int x dx \Rightarrow y - \frac{1}{y} = \frac{x^2}{2} + C
    \)

**Zadanie 2**  
\(
\frac{dy}{dx} = \frac{e^x}{y}
\)  

??? info "Pokaż rozwiązanie"
    Rozdzielamy:
    \(
    y dy = e^x dx
    \Rightarrow \int y dy = \int e^x dx \Rightarrow \frac{y^2}{2} = e^x + C
    \)  

---

## 🔹 Liniowe jednorodne

**Zadanie 3**  
\(
\frac{dy}{dx} + 2y = 0
\)  

??? info "Pokaż rozwiązanie"
    Czynnik całkujący: \( \mu(x) = e^{2x} \)  
    \(
    \frac{d}{dx}(y e^{2x}) = 0 \Rightarrow y e^{2x} = C \Rightarrow y = C e^{-2x}
    \)

**Zadanie 4**  
\(
\frac{dy}{dx} + \frac{1}{x}y = 0
\)  

??? info "Pokaż rozwiązanie"
    \(\mu(x) = e^{\int \frac{1}{x} dx} = x\)    
    \(
    \frac{d}{dx}(x y) = 0 \Rightarrow xy = C \Rightarrow y = \frac{C}{x}
    \)  

---

## 🔹 Liniowe niejednorodne

**Zadanie 5**  
\(
\frac{dy}{dx} + y = \cos x
\)  

??? info "Pokaż rozwiązanie"
    \( \mu(x) = e^x \)  
    \(
    \frac{d}{dx}(y e^x) = e^x \cos x \Rightarrow y = e^{-x} \int e^x \cos x dx
    \)  
    Całkowanie przez części:
    \(
    y = \frac{e^{-x}}{2}(e^x \sin x + \cos x) + C e^{-x}
    \)  

**Zadanie 6**  
\(
\frac{dy}{dx} + y = x^2
\)  

??? info "Pokaż rozwiązanie"
    \( \mu(x) = e^x \)  
    \(
    \frac{d}{dx}(y e^x) = x^2 e^x \Rightarrow y = e^{-x} \int x^2 e^x dx
    \)  
    (Całkowanie przez części — pomijamy)

---

## 🔹 Zupełne i z czynnikiem całkującym

**Zadanie 7**  
\(
(2xy + y^2)dx + (x^2 + 2xy)dy = 0
\)  

??? info "Pokaż rozwiązanie"
    Warunek zupełności spełniony ✅  
    \(
    \frac{dM}{dy} = 2x + 2y = \frac{dN}{dx}
    \)  
    \(
    F(x, y) = x^2y + xy^2 = C
    \)  

**Zadanie 8**  
\(
(3x + 4y)dx + (4x + 6y)dy = 0
\)  

??? info "Pokaż rozwiązanie"
    Sprawdzamy zupełność:
    \(
    \frac{dM}{dy} = 4 \text{ oraz } \frac{dN}{dx} = 4 \Rightarrow \text{zupełne ✅}
    \)    
    \(
    F(x, y) = 3x^2/2 + 4xy + 3y^2 = C
    \)  

**Zadanie 9**  
\(
(y + 2x)dx + x dy = 0
\)  

??? info "Pokaż rozwiązanie"
    Niezupełne. Mnożymy przez \(\mu = \frac{1}{x}\):  
    \(
    \left(\frac{y}{x} + 2\right) dx + dy = 0
    \)  
    Teraz zupełne: \(F(x, y) = y + 2x + \ln|x| = C\)  

**Zadanie 10**  
\(
(y - x)dx + (x - 2y)dy = 0
\)  

??? info "Pokaż rozwiązanie"
    Niezupełne. Znajdujemy czynnik \(\mu = \frac{1}{y^2}\) (przykładowy) lub transformujemy do rozdzielnych. Rozwiązanie po przekształceniu:
    \(
    \frac{dy}{dx} = \frac{y - x}{x - 2y} \Rightarrow \text{zmienne rozdzielone}
    \)  

---

## 🔹 II rzędu liniowe jednorodne

**Zadanie 11**  
\(
y'' - 3y' + 2y = 0
\)  

??? info "Pokaż rozwiązanie"
    Równanie charakterystyczne:
    \(
    r^2 - 3r + 2 = 0 \Rightarrow r = 1, 2 \Rightarrow y = C_1 e^x + C_2 e^{2x}
    \)  

**Zadanie 12**  
\(
y'' + y = 0
\)  

??? info "Pokaż rozwiązanie"
    Równanie charakterystyczne:
    \(
    r^2 + 1 = 0 \Rightarrow r = \pm i \Rightarrow y = C_1 \cos x + C_2 \sin x
    \)  

---

## 🔹 II rzędu liniowe niejednorodne

**Zadanie 13**  
\(
y'' - y = e^x
\)

??? info "Pokaż rozwiązanie"
    Rozwiązanie ogólne to suma rozwiązania jednorodnego i szczególnego:
    \(
    y_h = C_1 e^x + C_2 e^{-x}
    \)
    Zgadujemy postać szczególnego: \(y_p = Ax e^x\)
    \(
    y_p' = Ae^x + Axe^x, \quad y_p'' = 2Ae^x + Axe^x
    \)
    Podstawiamy:
    \(
    y'' - y = (2Ae^x + Axe^x) - Axe^x = 2Ae^x = e^x \Rightarrow A = \frac{1}{2}
    \)
    \(
    y = C_1 e^x + C_2 e^{-x} + \frac{1}{2}x e^x
    \)

**Zadanie 14**  
\(
y'' + 4y = \cos 2x
\)

??? info "Pokaż rozwiązanie"
    Rozwiązanie jednorodne:
    \(
    r^2 + 4 = 0 \Rightarrow r = \pm 2i \Rightarrow y_h = C_1 \cos 2x + C_2 \sin 2x
    \)
    Prawej stronie odpowiada szczególne: \(y_p = Ax \cos 2x + Bx \sin 2x\)
    (z powodu rezonansu)
    Po podstawieniu i porównaniu współczynników:
    \(
    y_p = -\frac{1}{8}x \sin 2x
    \)
    \(
    y = C_1 \cos 2x + C_2 \sin 2x - \frac{1}{8}x \sin 2x
    \)
