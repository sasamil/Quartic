# Direct solver of algebraic equations of 4th order
This is an extremely simple and efficient solver of algebraic equation of 4th order. I have read so many relating articles, I have tested other solutions... However, this solution contains <b>the algebraic improvement</b> which simplifies things, significantly. <img src="https://raw.githubusercontent.com/sasamil/WMS-TMS-Maker-Qt-GUI/master/icons/emoticons/idea2.gif" alt="eureka" height="18" width="30"> Consequently, the numerical computations are reduced and as far as I can see, it performs extraordinarily! The theory and mathematical background are explained in the file - theorymath_sr.docx. It's in Serbian now, but it will be translated to English (sooner or later).

The solution of a given quartic equation - <i>x^4 + a·x^3 + b·x^2 + c·x + d = 0</i> - can be found by the function: 

<i>solve_quartic(double a, double b, double c, double d)</i>

Quartic equation may have different types of roots. a) 4 real roots b) 2 real and 2 complex-conjugate roots c) 4 complex roots (two pairs of complex-conjugates). Our <i>solve_quartic()</i> returns the array of four complex numbers. If there are real roots, the immaginary parts of corresponding solutions (array members) will be simply - 0.

(Here, <i>main.cpp</i> file is given just for testing and experimenting) 
