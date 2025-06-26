Jeżeli równanie różniczkowe jest postaci:  
$$
y'' + p \cdot y' + q \cdot y = 0
$$  
to stosujemy podstawienie \(y = e^{\alpha x}\) i otrzymujemy:  
$$ \alpha^2 \cdot e^{\alpha x} + p \cdot \alpha \cdot e^{\alpha x} + q \cdot e^{\alpha x} = 0 $$  
dzielimy obustronnie przez \(e^{\alpha x}\) i otrzymujemy równanie:  
$$ \alpha^2 + p \cdot \alpha + q = 0 $$
zwane **równaniem charakterystycznym**.  
Następnie obliczamy \(\Delta = p^2 - 4q\)  
Jeżeli:  

- otrzymamy \(\Delta >0\), to \(\alpha_1 = \frac{-p-\sqrt{\Delta}}{2}\), \(\alpha_2 = \frac{-p+\sqrt{\Delta}}{2}\), a rozwiązaniem ogólnym równania II-go rzędu liniowego jednorodnego jest \(Y=C_1 \cdot e^{\alpha_1 x} + C_2 \cdot e^{\alpha_2 x}\)
- otrzymamy \(\Delta =0\), to \(\alpha_1 = \alpha_2= \frac{-p}{2}\), a rozwiązaniem ogólnym równania II-go rzędu liniowego jednorodnego jest \(Y=C_1 \cdot e^{\alpha x} + C_2 \cdot x\cdot e^{\alpha x}\)
- otrzymamy \(\Delta < 0\), to \(\alpha_1 = \frac{-p}{2}-\frac{\sqrt{-\Delta}}{2}i\), \(\alpha_2 = \frac{-p}{2}+\frac{\sqrt{-\Delta}}{2}i\), a rozwiązaniem ogólnym równania II-go rzędu liniowego jednorodnego jest \(Y=e^{\alpha x} \cdot (C_1 \cdot cos\beta x + C_2 \cdot sin\beta x)\), gdzie \(\alpha = \frac{-p}{2}\), a \(\beta = \frac{\sqrt-\Delta}{2}\)  
[Zobacz przykład](metoda1-rzedu-2)  
