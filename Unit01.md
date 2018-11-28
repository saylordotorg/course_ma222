**Unit 1: Introduction to Partial Differential Equations** <span
id="1"></span> 
*This unit will review the background mathematics that you will need to
use in this course. You should be familiar with the majority of the
concepts presented here, but some material may be new to you. This unit
will also introduce the notation and terminology that we will use in the
remainder of the course.*  
  
 *In addition, several of the most important PDEs *– *the heat equation,
the wave equation, and Schrodinger’s equation *– *will be derived from
physical principles. While some of this material is optional, knowledge
of it will help you develop intuition about solutions to these equations
and understand why the theory developed as it did.*

**Unit 1 Time Advisory**  
This unit should take you approximately 8.25 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.1: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.2: 5.25 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit 1.2.1: 1.5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit 1.2.2: 2 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit 1.2.3: 1.75 hours

<span id="cke_bm_612E" style="display: none;"> </span><span
id="cke_bm_611E" style="display: none;"> </span>

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   recall notation for partial derivatives;
-   recall how to manipulate complex numbers;
-   recall how to use Cartesian, polar, and spherical coordinates;
-   recall important concepts from Vector Calculus;
-   state the heat, wave, Laplace, and Poisson equations and explain
    their physical origins;
-   define harmonic functions;
-   state and justify the maximum principle for harmonic functions; and
-   state the mean value property for harmonic functions.

**1.1 Preliminaries** <span id="1.1"></span> 
**1.1.1 Sets, Functions, and Derivatives** <span id="1.1.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “Chapter
    Zero: Appendices”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“Chapter Zero:
    Appendices”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above. This reading covers subunits
    1.1.1 through 1.1.5.  
        
     Read sections 0A through 0E in the Appendices section (pages 545
    through 565). Section 0A will explain vocabulary such as **path,
    mass density,** and **time-varying scalar field.** Section 0B
    explains the author’s notation for derivatives. Section 0C reviews
    complex numbers. Section 0D reviews several coordinate systems,
    including polar and spherical. Section 0E reviews some important
    concepts from vector calculus, including the gradient, the
    divergence, the Divergence theorem, and Green’s formulas.  
        
     Reading these sections should take approximately 3 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.1.2 Notation for Derivatives** <span id="1.1.2"></span> 
*Note: This topic is covered by the reading assigned below subunit
1.1. *

**1.1.3 Complex Numbers** <span id="1.1.3"></span> 
*Note: This topic is covered by the reading assigned below subunit
1.1. *

**1.1.4 Coordinate Systems** <span id="1.1.4"></span> 
*Note: This topic is covered by the reading assigned below subunit
1.1. *

**1.1.5 Vector Calculus** <span id="1.1.5"></span> 
*Note: This topic is covered by the reading assigned below subunit
1.1. *

**1.2 Overview and Motivation** <span id="1.2"></span> 
*If your background or interest in mathematical physics is small, feel
free to skim through much of the material on physical motivation for the
development of these PDEs, which is given in the readings for subunits
1.2.2–1.2.3. However, this material is worthwhile, and you should be
sure to take the time to understand the mathematical properties of the
solutions to the PDEs, which some of these readings begin to discuss.
The material on the properties of harmonic functions, for instance, is
particularly important.*

**1.2.1 Overview of PDEs** <span id="1.2.1"></span> 
-   **Web Media: YouTube: commutant’s “PDE Part 1: Introduction”**
    Link: YouTube: commutant’s [“PDE Part 1:
    Introduction](http://www.youtube.com/watch?v=LYsIBqjQTdI)[”](http://www.youtube.com/watch?v=LYsIBqjQTdI)
    (YouTube)  
        
     Instructions: Click on the link above, and watch the video. The
    author briefly explains what PDEs are and what it means to solve
    them and then works through an example.  
        
     Watching this lecture and pausing to take notes should take
    approximately 25 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: MIT: Gigliola Staffilani’s *Introduction to Partial
    Differential Equations*: “Lecture 1: “Introduction and Basic Facts
    about PDEs”**
    Link: MIT: Gigliola Staffilani’s *Introduction to Partial
    Differential Equations*: [“Lecture 1: Introduction and Basic Facts
    about
    PDEs”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/05/Lecture-1-Introduction-and-Basic-Facts-about-PDEs.pdf) (PDF)  
        
     Instructions: Click on the link above. The lecture notes will open
    in PDF form (6 pages).   
        
     These notes give an overview of much of the course content and
    define **linearity** and **homogeneity**.  
        
     Studying these notes should take approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Web Media: YouTube: commutant’s “PDE Part 2: Three Fundamental
    Examples”**
    Link: YouTube: commutant’s [“PDE Part 2: Three Fundamental
    Examples](http://www.youtube.com/watch?v=DDPO-19FyJM&feature=related)[”](http://www.youtube.com/watch?v=DDPO-19FyJM&feature=related)
    (YouTube)  
        
     Instructions: Watch this brief video that briefly explores three
    fundamental PDEs. The physical motivation behind these PDEs will be
    explained in the next three sections.  
        
     Watching this lecture and pausing to take notes should take
    approximately 20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.2 Heat and Diffusion** <span id="1.2.2"></span> 
**1.2.2.1 Fourier’s Law and the Heat Equation** <span
id="1.2.2.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “1A:
    Heat and Diffusion: Fourier’s Law” and “1B: Heat and Diffusion: The
    Heat Equation”**
    Links: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“1A: Heat and
    Diffusion: Fourier’s
    Law](http://www.saylor.org/content/general/Cambridge_PDE.pdf)” (PDF)
    and [“1B: Heat and Diffusion: The Heat
    Equation”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)   
        
     Instructions: Click on the links above and read sections 1A and 1B
    (pages 3-9).  
        
     The heat equation describes the erosion or diffusion of a system,
    and this reading explains its derivation. The reading also gives
    several solutions to the heat equation.  
        
     Studying this reading should take approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.2.2 Laplace’s Equation** <span id="1.2.2.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “1C:
    Heat and Diffusion: Laplace’s Equation”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“1C: Heat and
    Diffusion: Laplace’s
    Equation”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 1C (pages
    9-12).  
        
     This reading explains Laplace’s equation and defines **harmonic
    functions**.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.2.3 The Poisson Equation** <span id="1.2.2.3"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “1D:
    Heat and Diffusion: The Poisson Equation”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“1D: Heat and
    Diffusion: The Poisson
    Equation”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 1D (pages
    12-16).  
        
     The Poisson equation describes the steady state of the
    generation-diffusion equation.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.2.4 Properties of Harmonic Functions** <span id="1.2.2.4"></span> 
-   **Reading: Mathnotes.me: “Laplace Equation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.2.3 Waves and Signals** <span id="1.2.3"></span> 
**1.2.3.1 The Laplacian and Spherical Means** <span
id="1.2.3.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “2A:
    Waves and Signals: The Laplacian and Spherical Means”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“2A: Waves and
    Signals: The Laplacian and Spherical
    Means”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 2A (pages
    23-27).   
        
     This reading further justifies the spherical means used in the
    exploration of the properties of harmonic functions.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.3.2 The Wave Equation** <span id="1.2.3.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “2B:
    Waves and Signals: The Wave Equation”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“2B: Waves and
    Signals: The Wave
    Equation”](http://www.saylor.org/content/general/Cambridge_PDE.pdf) (PDF)  
        
     Instructions: Click on the link above and read section 2B (pages
    27-34).   
        
     This reading derives the wave equation. Again, feel free to skip
    this material if you find it overwhelming or uninteresting.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Web Media: YouTube: commutant’s “PDE Part 7: Wave Equation:
    Intuition”**
    Link: YouTube: commutant’s [“PDE Part 7: Wave Equation:
    Intuition](http://www.youtube.com/watch?v=ck-r_qmNNG0&feature=related)[”](http://www.youtube.com/watch?v=ck-r_qmNNG0&feature=related)
    (YouTube)  
        
     Instructions: Watch this video that explains the physical origins
    of the wave equation and what exactly the terms mean. In addition,
    the author analyzes the dimensions of variables.  
        
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


