---
layout: default
title: "MA222: Introduction to Partial Differential Equations"
course_description: "An introduction to the analysis and solution of Partial Differential Equations, which describe the relationships among the derivatives of an unknown function with respect to different independent variables, such as time and position."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Classification of Linear PDEs** <span id="2"></span> 
*There is an incredible amount of variety in the study of PDE problems,
in part because of the incredible amount of variety in the physical
systems that many of them model. Over the course of the last 300 years,
many different mathematicians and physicists have tackled the same
problems and come up with diverse approaches to solving them, each
adding new richness to the field. While this diversity makes for very
interesting problems, it can devolve into a theoretical Gordion knot
when considered without a strong and well-defined framework to anchor
the novice student. For that reason, we will wait to touch on the most
common solution methods until Units 3-5. In this unit, we will attempt
to impose some order on our approach so that as you learn different
solution methods, you will understand the broad classes of functions to
which they apply, as well as the complications that make one method
appropriate for one situation, but not for another.*  
  
 *The unit begins with a refresher on the concept of linear operators,
essential for the classification of linear PDEs. Equations are
classified as homogeneous or nonhomogeneous, and evolution or
nonevolution. The readings for the unit detail the different types of
boundary conditions and their physical significance. The different types
of linear PDEs are explained. Finally, the concepts of uniqueness and
well-posedness are elaborated, and uniqueness under suitable conditions
is established for some of the most important PDEs.*  
  
 *If your mathematical background does not include a course in real
analysis, you will likely find this unit more comprehensible if you
first skip ahead to Units 3 and 4 and study some of the more tangible
solution techniques. In so doing, do not worry about the technical
assumptions required to ensure that the techniques “work.” Rather,
assume what you need and focus on the techniques and what they produce.
Once you are comfortable with this, then go back to Unit 2 and work
through the mathematical underpinnings. As you do so, keep in mind what
you learned in Units 3 and 4 as a target to which the theory will
inevitably be applied. *

**Unit 2 Time Advisory**  
This unit should take you approximately 11 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.1: 2 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2: 9 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.1: 2.25 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.2: 0.25 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.3: 2 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.4: 2 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.5: 1.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2.6: 1 hour

  
 <span id="cke_bm_551E" style="display: none; "> </span>

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:   
-   define linear operators;
-   identify linear PDEs and classify them as elliptic, parabolic, or
    hyperbolic;
-   identify linear operations;
-   identify homogeneous PDEs;
-   relate solving homogeneous linear PDEs to finding kernels of linear
    operators;
-   identify evolution and nonevolution equations;
-   define initial-value problem;
-   define boundary-value problem and identify boundary conditions as
    periodic, Dirichlet, Neumann, or Robin (mixed);
-   explain the physical significance of boundary conditions;
-   show uniqueness of solutions to the Laplace and Poisson equations
    with various boundary conditions;
-   show uniqueness of solutions to the heat equation with various
    boundary conditions;
-   show uniqueness of solutions to the wave equation with various
    boundary conditions; and
-   define well-posedness.

**2.1 Linear Partial Differential Equations** <span id="2.1"></span> 
**2.1.1 Functions and Vectors** <span id="2.1.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “4A:
    Linear Partial Differential Equations: Functions and Vectors”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“4A: Linear
    Partial Differential Equations: Functions and
    Vectors”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 4A (pages
    57-59).   
        
     This reading explains how different sets of functions can be
    described as vector spaces, most importantly the C-infinity
    functions – those that are infinitely differentiable.  
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1.2 Linear Operators** <span id="2.1.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “4B:
    Linear Partial Differential Equations: Linear Operators”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“4B: Linear
    Partial Differential Equations: Linear
    Operators”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above. The book will open as a PDF.
    Read section 4B (pages 59-64).   
        
     Linear Algebra is a powerful tool used to investigate broad
    categories of equations and mathematical phenomena. Differentiation
    is a linear operation, and therefore many of the now familiar
    characters from PDE, such as the Laplacian, can be analyzed as
    linear operators.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Matthew Hancock’s “Problem Set 2” and
    MIT: Professor Steven Johnson’s “Problem Set 1”**
    Links: MIT: Professor Matthew Hancock’s [“Problem Set
    2](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet2.pdf)[”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet2.pdf)
    (PDF) and MIT: Professor Steven Johnson’s [“Problem Set
    1](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet1.pdf)[”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet1.pdf)
    (PDF)  
        
     Instructions: Click on the first link above, and complete problems
    2 and 3 of “Problem Set 2.” Then, click on the second link above,
    and complete problem 1 of “Problem Set 1.” To check your solutions,
    follow this
    [link](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet2sol.pdf)
    for the Hancock problems, and this
    [link](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_Steven-Johnson_ProblemSet1sol.pdf)
    for the Johnson problems.   
        
     You should dedicate approximately 1 hour to completing this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1.3 Homogeneous and Nonhomogeneous Linear PDEs** <span
id="2.1.3"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “4A:
    Linear Partial Differential Equations: Homogeneous vs.
    Nonhomogeneous”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“4A: Linear
    Partial Differential Equations: Homogeneous vs.
    Nonhomogeneous”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above. The book will open as a PDF.
    Read section 4C (pages 64-66).   
        
     This reading defines **homogeneous** and **non-homogeneous**
    equations and explains the **superposition principle**.  
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2 Classification of PDEs** <span id="2.2"></span> 
**2.2.1 Evolution and Nonevolution Equations** <span id="2.2.1"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “5A:
    Classification of PDEs and Problem Types: Evolution vs. Nonevolution
    Equations”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“5A:
    Classification of PDEs and Problem Types: Evolution vs. Nonevolution
    Equations”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 5A (pages 69
    and 70).  
        
     This reading defines **evolution equations** and the **order** of a
    PDE.   
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.  
      

-   **Assessment: Naval Postgraduate School: Professor Beny Neta’s
    Partial Differential Equations MA 3132: Solutions of Problems in
    Lecture Notes “Chapter 1.1: Introduction and Applications: Basic
    Concepts and Definitions”**
    Link: Naval Postgraduate School: Professor Beny Neta’s *Partial
    Differential Equations MA 3132: Solutions of Problems in Lecture
    Notes *[“Chapter 1.1: Introduction and Applications: Basic Concepts
    and Definitions”](http://faculty.nps.edu/bneta/lnotes.html) (PDF)  
        
     Instructions: Find the links under "MA3132 Lecture Notes and
    Solution Manual" and download the solution manual. Scroll down to
    page 1 of the document and attempt problems 1-5. When finished, go
    to page 2 to find the solutions. You will use this document again in
    the course, so you may wish to keep your copy available.  
        
     You should dedicate approximately 2 hours to completing this
    assessment.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.2 Initial-Value Problems** <span id="2.2.2"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “5B:
    Classification of PDEs and Problem Types: Initial Value Problems”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“5B:
    Classification of PDEs and Problem Types: Initial Value
    Problems”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 5B (pages 70
    and 71).  
        
     This reading defines **initial-value** or **Cauchy** problems.   
        
     Studying this reading should take approximately 15-20 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.3 Boundary Value Problems: Types of Boundary Conditions** <span
id="2.2.3"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “5C:
    Classification of PDEs and Problem Types: Boundary Value Problems”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“5C:
    Classification of PDEs and Problem Types: Boundary Value
    Problems”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 5C (pages
    71-84).  
        
     This reading defines **boundary-value problems**. While initial
    value problems apply only to evolution equations and may take place
    on an infinite domain, boundary-value problems are not restricted to
    evolution equations and allow more realistic modeling of physical
    phenomena. There are multiple types of **boundary conditions**, and
    this reading will explain their physical significance.  
        
     Studying this reading should take approximately 2 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.4 Uniqueness of Solutions** <span id="2.2.4"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “5D:
    Classification of PDEs and Problem Types: Uniqueness of Solutions”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“5D:
    Classification of PDEs and Problem Types: Uniqueness of
    Solutions”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 5D (pages
    84-95).  
        
     The ability to establish **uniqueness of solutions** is very
    important in analysis of PDEs. This reading describes the uniqueness
    of solutions to various PDEs with different regularity properties
    and boundary conditions.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Matthew Hancock’s “Problem Set 2” (PDF)
    and Penn State: Professor Kris Wysocki’s “Homework 4” (PDF)**
    Links: MIT: Professor Matthew Hancock’s [“Problem Set
    2](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/assignments/)[”](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/assignments/)
    (PDF) and Penn State: Professor Kris Wysocki’s [“Homework
    4](http://www.math.psu.edu/wysocki/M412/Math412.html)[”](http://www.math.psu.edu/wysocki/M412/Math412.html)
    (PDF)  
        
     Instructions: Click on the first link above to access the PDF, and
    complete problems 2 and 3 of “Problem Set 2.” Then, click on the
    second link above, select the hyperlink to “Homework 4” to download
    the PDF, and complete problem 5. To check your solutions for the
    Hancock problems, click on this
    [link](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/10/MIT_MatthewHancock_ProblemSet2sol.pdf).
    To check your solutions for the Wysocki problems, follow the top
    link again and click on the corresponding link for solutions.  
        
     In the second assessment, note that “energy methods” are used in
    the readings from Professor Pivato’s textbook to show uniqueness:
    namely, integrating the square of some quantity to show that it is
    zero.  
        
     You should dedicate approximately 1 hour to completing this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.5 Classification of Second Order Linear PDEs** <span
id="2.2.5"></span> 
-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    *Linear Partial Differential Equations and Fourier Theory*: “5E:
    Classification of PDEs and Problem Types: Classification of Second
    Order Linear PDEs”**
    Link: Cambridge University Press: Professor Marcus Pivato’s *Linear
    Partial Differential Equations and Fourier Theory*: [“5E:
    Classification of PDEs and Problem Types: Classification of Second
    Order Linear
    PDEs”](http://www.saylor.org/content/general/Cambridge_PDE.pdf)
    (PDF)  
        
     Instructions: Click on the link above and read section 5E (pages
    95-98).  
        
     Recall that in many cases, solving a (homogeneous) PDE can be
    formulated as finding the kernel (nullspace) of a linear operator on
    a function space. In this reading, three classes of linear PDEs are
    identified by analyzing these operators; the categories are
    **elliptic**, **parabolic**, and **hyperbolic** equations.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Naval Postgraduate School: Professor Beny Neta’s
    Partial Differential Equations MA 3132: Solutions of Problems in
    Lecture Notes: “Chapter 2.2: Classification and Characteristics:
    Classification of Linear Second Order PDEs”**
    Link: Naval Postgraduate School: Professor Beny Neta’s *Partial
    Differential Equations MA 3132: Solutions of Problems in Lecture
    Notes*: [“Chapter 2.2: Classification and Characteristics:
    Classification of Linear Second Order
    PDEs”](http://faculty.nps.edu/bneta/lnotes.html) (PDF)  
        
     Instructions: You should already have this text downloaded to you
    computer, but if not, click on the link above to download it. Go to
    page 14 and attempt problems 1 and 2. When finished, go to page 15
    to find the solutions.  
        
     You should dedicate approximately 1 hour to completing this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.6 Well-Posedness** <span id="2.2.6"></span> 
-   **Reading: Oakridge National Laboratory Physics Division’s “6
    Well-Posed PDE Problems”**
    Link: Oakridge National Laboratory Physics Division’s [“6 Well-Posed
    PDE
    Problems](http://www.phy.ornl.gov/csep/CSEP/PDE/NODE6.html)[”](http://www.phy.ornl.gov/csep/CSEP/PDE/NODE6.html)
    (HTML)  
        
     Instructions: Click on the link above, and read through the linked
    pages. Make sure to click on the “continued” link at the bottom of
    each webpage to read the entire 8-page tutorial.  
        
     These notes give an overview of the important concept of
    well-posedness, which links mathematical properties of solutions to
    PDEs to their usefulness in describing natural phenomena.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


