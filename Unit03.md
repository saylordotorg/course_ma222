**Unit 3: Fourier Series on Bounded Domains** <span id="3"></span> 
*As you may have learned in a physics (or music!) class, every sound is
made up of sound waves with different frequencies. Thus, for instance, a
C-major chord based at middle C is made of up waves at 261.6 Hz(C),
329.6 Hz (E), and 392.0 Hz (G). The combination (or superposition) of
these three individual sound waves produces a new and distinct sound. In
fact, any signal or waveform (subject to some reasonable conditions) can
be written as the combination of some fundamental waves, whether it is a
water wave, a light or electromagnetic wave, or a sound wave.
Mathematically, a waveform is just a function, and, conversely, every
function can be viewed as a waveform. Most (again, subject to some
reasonable conditions) can be written as a combination of some
fundamental wave-like functions, namely sines and cosines. This was the
observation of Fourier, a great scientist of the nineteenth century. It
took years for other mathematicians to accept his work and come up with
a theoretical framework for his results. The study of such ideas is
today called Harmonic Analysis, and it has gone far beyond Fourier’s
original ideas to touch almost every part of modern science and
technology, from medical imaging to wireless communication.*  
  
 *In this unit, you will learn to apply Fourier’s original
insight *– *that most useful functions can be written as linear
combinations of sine and cosine waves. To do this rigorously, some
mathematical underpinnings must be established, such as the definition
and elaboration of the square-integrable functions, the differences
between different modes of convergence, and the orthogonality of the
basis of trigonometric functions, some of which you will recall from
MA241. After this has been accomplished, you will learn how to calculate
Fourier series for suitable functions.*

**Unit 3 Time Advisory**  
This unit should take you approximately 14.5 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1: 4.75 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; "><span
id="cke_bm_563S" style="display: none; "> </span>☐    </span>Subunit
3.1.1: 0.75 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1.2: 0.25 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1.3: 0.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1.4: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1.5: 0.25 hours<span id="cke_bm_563E"
style="display: none; "> </span>

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2: 9.75 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2.1: 4 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2.2: 1 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2.3: 0.25 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2.4: 4.5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   define, characterize, and use inner products;
-   define the space of L<sup>2</sup> functions and state its key
    properties;
-   show that a function belongs to the space of
    L<sup>2 </sup>functions;
-   define orthogonality and show the orthogonality of certain
    trigonometric functions;
-   define the Haar Basis;
-   distinguish between pointwise, uniform, and L<sup>2</sup>
    convergence;
-   show convergence of sequences;
-   use the Weierstrass M-test to show that Fourier series converge;
-   define orthogonal and orthonormal basis;
-   define Fourier series on [0,π] and [0,L] and identify sufficient
    conditions for their convergence and uniqueness;
-   define the Gibbs Phenomenon; and
-   compute Fourier coefficients and construct Fourier series.

**3.1 Necessary Functional Analysis** <span id="3.1"></span> 
**3.1.1 Inner Products** <span id="3.1.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “6A:
    Some Functional Analysis: Inner Products”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“6A: Some
    Functional Analysis: Inner
    Products”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 6A (pages
    103-105).  
        
     Solving linear PDEs using algebraic methods requires an
    understanding of inner product spaces.  
        
     Studying this reading should take approximately 20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Steven Johnson’s “Problem Set 2”**
    Link: MIT: Professor Steven Johnson’s [“Problem Set
    2](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet2.pdf)[”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet2.pdf)
    (PDF)  
        
     Instructions: Click on the link above to access the PDF file, and
    complete problem 2 from “Problem Set 2.” To check your solutions,
    follow this
    [link](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet2sol.pdf).  
        
     You should dedicate approximately 30 minutes to completing this
    assessment.  
        
     Terms of Use: The materials above are released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike 3.0 United States (CC
    BY-NC-SA
    3.0)](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     

**3.1.2 L2 Space** <span id="3.1.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “6B:
    Some Functional Analysis: L2 Space”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“6B: Some
    Functional Analysis: L2
    Space”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 6B (pages
    105-108).  
        
     In order to apply ideas from linear algebra to PDEs, one requires a
    normed linear space with a well-defined norm. Using the inner
    product ideas from the previous section, the author defines the
    vector space L<sup>2</sup> of square-integrable functions.  
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.3 Orthogonality** <span id="3.1.3"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “6D:
    Some Functional Analysis: Orthogonality”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“6D: Some
    Functional Analysis:
    Orthogonality”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 6D (pages
    112-116).  
        
     In this section, the author shows the **orthogonality of
    trigonometric functions**, which will be a crucial fact for the
    development of Fourier series in upcoming units.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.4 Convergence Concepts** <span id="3.1.4"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “6E:
    Some Functional Analysis: Convergence Concepts”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“6E: Some
    Functional Analysis: Convergence
    Concepts”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section
    6E (pages 116-131).  
        
     In many cases, solutions to PDEs can be constructed using sequences
    or series of functions. However, as you know from calculus, the
    construction of a sequence or series does not guarantee that it has
    a well-defined limit. For this reason, the author defines several
    modes of convergence, which will be used to establish the validity
    of these types of solutions. The diagrams used to illustrate these
    concepts are excellent.  
        
     Studying this reading should take approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.5 Orthogonal and Orthonormal Bases** <span id="3.1.5"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “6F:
    Some Functional Analysis: Orthogonal and Orthonormal Bases”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“6F: Some
    Functional Analysis: Orthogonal and Orthonormal
    Bases](http://www.saylor.org/content/general/Cambridge_PDE.pdf)[”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section
    6F (pages 131-133).  
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2 Fourier Series** <span id="3.2"></span> 
**3.2.1 Eigensolutions to Linear Evolution Equations** <span
id="3.2.1"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 3:
    Fourier Series: 3.1: Eigensolutions to Linear Evolution Equations”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*: [“Chapter 3: Fourier Series:
    3.1: Eigensolutions to Linear Evolution
    Equations](http://www.math.umn.edu/~olver/pdn.html)[”](http://www.math.umn.edu/~olver/pdn.html)
    (PDF)  
        
     Instructions: Click on the link above. Scroll down to the Chapter
    3, and click on the link to download the PDF. Read pages 55-63.  
        
     In this reading, the author motivates the construction of Fourier
    series by tying them to **eigenvalue problems** for linear evolution
    equations. We will return to these ideas when we discuss the
    technique of separation of variables.  
        
     Studying this reading should take approximately 4 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.2 Fourier Series on [0, ?]** <span id="3.2.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “7A:
    Fourier Sine Series and Cosine Series: Fourier (Co)sine Series on
    [0, ?]”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“7A: Fourier
    Sine Series and Cosine Series: Fourier (Co)sine Series on [0,
    π]”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
      
     Instructions: Click on the link above and read section 7A (pages
    137-144).  
        
     All of the facts that were established in section 3.1 about inner
    products, orthogonality, the L<sup>2</sup> functions, and
    orthonormal bases are brought into play in this section. Fourier
    series are one of your most powerful tools for solving PDEs. They
    are also extremely important for signal and image processing, so
    investment in understanding this concept is well-worth your time.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.3 Fourier Series on [0,L]** <span id="3.2.3"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “7B:
    Fourier Sine Series and Cosine Series: Fourier (Co)sine Series on
    [0, L]”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“7B: Fourier
    Sine Series and Cosine Series: Fourier (Co)sine Series on [0,
    L]](http://www.saylor.org/content/general/Cambridge_PDE.pdf)[”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 7B (pages
    144-146).  
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4 Computing Fourier Coefficients** <span id="3.2.4"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “7C:
    Fourier Sine Series and Cosine Series: Computing Fourier (Co)sine
    Coefficients”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“7C: Fourier
    Sine Series and Cosine Series: Fourier (Co)sine
    Coefficients](http://www.saylor.org/content/general/Cambridge_PDE.pdf)[”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 7C (pages
    147-158).  
        
     This section reviews some important methods of computing Fourier
    coefficients for various functions, including polynomials, step
    functions, and piecewise linear functions.  
        
     Studying this reading should take approximately 1 hour and 30
    minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Matthew Hancock’s “Problem Set 1” and
    Trinity College, Dublin: Professor Sarah McMurry’s “Problem Sheet
    2”**
    Link: MIT: Professor Matthew Hancock’s [“Problem Set
    1](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet1.pdf)[”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet1.pdf)
    (PDF) and Trinity College, Dublin: Professor Sarah McMurry’s
    [“Problem Sheet
    2](http://www.maths.tcd.ie/~saram/2S2/index.html)[”](http://www.maths.tcd.ie/~saram/2S2/index.html)
    (PDF)  
      
     Instructions: Click on the first link above to access the PDF, and
    complete problem 1 from “Problem Set 1.” Then, click on the second
    link above, scroll down to the section “Problem Sheets,” and select
    the link to “Problem Sheet 4.” Complete all of the problems on
    “Problem Sheet 4.” To check your solutions for the Hancock
    assessments click on this
    [link](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/assignments/probheisolns.pdf).
    To check your solutions for the McMurry assessments follow the
    second link again and click on the corresponding link (“Answers to
    Sheet 4”) for solutions.  
        
     You should dedicate approximately 3 hours to completing this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


