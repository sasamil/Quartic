Direct solver of algebric equation of 4th order.

This is an extremely simple and efficient solver of algebric equation of 4th order. I have read so many relating articles, I have tested other solutions... However, this solution contains an algebric improvent which simplifies things, significantly. Consequently, it reduces numerical computations and as far as I can see, it performs extraordinarily. (This solution/algorithm may be the fastest one <imgsrc="www.animated-gifs.eu/category_emoticons/smilies-transportation/0030.gif" alt="fast, faster..." height="25" width="25">- I wouldn't be surprised, at all<!--imgsrc="http://forum.srpskinacionalisti.com/images/smilies/eusa_think.gif" alt="maybe the best" height="16" width="17"-->) The theory and mathematical background is explained in the file - theorymath_sr.docx. It's in Serbian now, but it will be translated to English (sooner or later).

The solution of a given quartic equation - <i>x^4 + a·x^3 + b·x^2 + c·x + d = 0</i> - can be found by the function: 

<i>solve_quartic(double a, double b, double c, double d)</i>

Quartic equation may have different types of roots. a) 4 real roots b) 2 real and 2 complex-conjugate roots c) 4 complex roots (two pairs of complex-conjugates). Our solve_quartic() returns the array of four complex numbers. If there are real roots, the immaginary parts of corresponding array members (solutions) will just be 0.

<i>main.cpp</i> file is given here just for testing and experimenting.
