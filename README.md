Direct solver of algebric equation of 4th order.

This is an extremely simple and efficient solver of algebric equation of 4th order. I have read so many relating articles, I have tested other solutions... However, this solution contains an algebric improvent which simplifies things, significantly. Consequently, it reduces numerical computations and as far as I can see, it performs nice. (This solution/algorithm might be the fastest one - I wouldn't be surprised) The theory and mathematical background is explained in theorymath_sr.docx. It's in Serbian now, but it is going to be translated to English, soon.

Quartic equation  x^4 + a·x^3 + b·x^2 + c·x + d = 0  can be solved by the function: 

solve_quartic(double a, double b, double c, double d)

Quartic equation may have different types of roots. a) 4 real roots b) 2 real and 2 complex-conjugate roots c) 4 complex roots (two pairs of complex-conjugates). Our solve_quartic() returns the array of four complex numbers. If there are real roots, the immaginary parts of corresponding array members (solutions) will just be 0.

main.cpp file is given here just for testing and experimenting.
