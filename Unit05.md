---
layout: default
title: "MA222: Introduction to Partial Differential Equations"
course_description: "An introduction to the analysis and solution of Partial Differential Equations, which describe the relationships among the derivatives of an unknown function with respect to different independent variables, such as time and position."
next: ../../../
previous: ../Unit04
---
**Unit 5: The Fourier Transform** <span id="5"></span> 
*The basic idea behind the Fourier transform is that the frequency
information hidden in a waveform or function because of its
time-dependence can be extracted by transforming that function into a
different space where the time-dimension is replaced with a frequency
dimension. In this space, relationships between derivatives of the
solution to a PDE are transformed into algebraic constraints that the
Fourier transform of the solution must satisfy. While Fourier series are
suited for boundary-value problems on bounded intervals, the Fourier
transform is used to solve boundary-value problems on infinite
domains.*  
  
 *In this unit, proceeding as before, the mathematical foundations for
the technique are laid down before the use of the technique is
demonstrated. Notice the similarity between the Fourier transform
solution to the Heat equation via convolution and the Green’s functions
derived earlier.*

**Unit 5 Time Advisory**  
This unit should take you approximately 20.25 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1: 8.5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1.1: 2 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1.2: 0.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1.3: 1 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1.4: 5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.2: 11.75 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.2.1: 1 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.2.2: 0.75 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.2.3: 10 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   define the Fourier transform;
-   derive basic properties of the Fourier transform of a function, such
    as its relationship to the Fourier transform of the derivative;
-   show that the inverse Fourier transform of a product is a
    convolution;
-   compute Fourier transforms of functions;
-   relate Fourier solutions to Green’s functions; and
-   use the Fourier transform to solve the heat and wave equations on
    unbounded domains.

**5.1 The Fourier Transform** <span id="5.1"></span> 
**5.1.1 One-Dimensional Fourier Transforms** <span id="5.1.1"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 8:
    Fourier Transforms: Introduction and the Fourier Transform”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*:
    *[*“*](http://www.math.umn.edu/~olver/pdn.html)*[Chapter 8: Fourier
    Transforms: Introduction and the Fourier
    Transform](http://www.math.umn.edu/~olver/pdn.html)[”](http://www.math.umn.edu/~olver/pdn.html)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to “Chapter 8,”
    and click on the link to download the PDF. Read the introduction and
    section 8.1 on pages 283-293.   
        
     The Fourier transform is an operator that maps functions into a
    space where their derivatives obey algebraic relationships. (It is
    similar to the Laplace transform that you learned about in MA221.)  
        
     Studying this reading should take approximately 2 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.1.2 Fourier Transforms of Derivatives and Integrals** <span
id="5.1.2"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 8:
    Fourier Transforms: 8.2: Derivatives and Integrals”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*:
    *[“](http://www.math.umn.edu/~olver/pdn.html)*[Chapter 8: Fourier
    Transforms: 8.2: Derivatives and
    Integrals](http://www.math.umn.edu/~olver/pdn.html)[”](http://www.math.umn.edu/~olver/pdn.html)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to Chapter 8,
    and click on the link to download the PDF. Read section 8.2 on pages
    293-295.   
        
     Be sure that you understand what the identities outlined here are
    saying and be able to apply them in appropriate situations.  
        
     Studying this reading should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.1.3 Green’s Functions and Convolution** <span id="5.1.3"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 8:
    Fourier Transforms: 8.3: Green’s Functions and Convolution”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*:
    *[“](http://www.math.umn.edu/~olver/pdn.html)*[Chapter 8: Fourier
    Transforms: 8.3: Green’s Functions and
    Convolution”](http://www.math.umn.edu/~olver/pdn.html) (PDF)  
        
     Instructions: Click on the link above, scroll down to Chapter 8,
    and click on the link to download the PDF. Read section 8.3 on pages
    295-300.   
        
     Convolution is a special operation because the Fourier transform of
    the convolution of two functions is the product of their Fourier
    transforms. Unsurprisingly, the Green’s function for the heat
    equation and similar convolution-based formulas can be derived using
    the Fourier transform.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.1.4 The Fourier Transform on Hilbert Space** <span
id="5.1.4"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 8:
    Fourier Transforms: 8.4: The Fourier Transform on Hilbert Space”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*:
    *[“](http://www.math.umn.edu/~olver/pdn.html)*[Chapter 8: Fourier
    Transforms: 8.4: The Fourier Transform on Hilbert
    Space](http://www.math.umn.edu/~olver/pdn.html)[”](http://www.math.umn.edu/~olver/pdn.html)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to Chapter 8,
    and click on the link to download the PDF. Read section 8.4 on pages
    300-304.   
        
     We have seen the Fourier transform as a mapping from the set of
    square-integrable functions on the real line to itself; this is a
    special example of a Hilbert space. Other spaces are possible, but
    that is outside the scope of this course.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Naval Postgraduate School: Professor Beny Neta’s
    Partial Differential Equations MA 3132: Solutions of Problems in
    Lecture Notes: “Chapter 9.2: Fourier Transform Solutions of PDEs:
    Fourier Transform Pair”**
    Link: Naval Postgraduate School: Professor Beny Neta’s *Partial
    Differential Equations MA 3132: Solutions of Problems in Lecture
    Notes*: [“Chapter 9.2: Fourier Transform Solutions of PDEs: Fourier
    Transform Pair”](http://faculty.nps.edu/bneta/lnotes.html) (PDF)  
        
     Instructions: Click on the link above. Under “MA3132 Lecture Notes
    and Solution Manual,” find the link “Solution Manual for MA3132 in
    pdf.” Click on the link to download the document; it contains
    problems and solutions.  
        
     In the PDF, scroll down to page 284 and attempt problems 1-5. When
    finished, go to page 285 to find the solutions.  
        
     You should dedicate approximately 4 hours to complete this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2 Fourier Transform Solutions to PDEs on Unbounded Domains** <span
id="5.2"></span> 
**5.2.1 The Heat Equation** <span id="5.2.1"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    *Introduction to Partial Differential Equations*: “Chapter 9: Linear
    and Nonlinear Evolution Equations: 9.1: The Fundamental Solution to
    the Heat Equation”**
    Link: University of Minnesota: Professor Peter Olver’s *Introduction
    to Partial Differential Equations*:
    *[“](http://www.math.umn.edu/~olver/pdn.html)*[Chapter 9: Linear and
    Nonlinear Evolution Equations: 9.1: The Fundamental Solution to the
    Heat
    Equation](http://www.math.umn.edu/~olver/pdn.html)[”](http://www.math.umn.edu/~olver/pdn.html)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to Chapter 9,
    and click on the link to download the PDF. Read section 9.1 on pages
    307-314 (stop at the section on Black-Scholes).   
        
     The Fourier transform is used here to derive the fundamental
    solution to the heat equation, which you have already seen in the
    section on Green’s functions. The author also tackles the heat
    equation with forcing.  
        
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2.2 The Wave Equation** <span id="5.2.2"></span> 
-   **Reading: University of British Columbia: Professor Joel Feldman’s
    “Using the Fourier Transform to Solve PDEs”**
    Link: University of British Columbia: Professor Joel Feldman’s
    [“Using the Fourier Transform to Solve
    PDEs](http://www.math.ubc.ca/~feldman/m267/)[”](http://www.math.ubc.ca/~feldman/m267/)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to the “Notes”
    section, and then click on the link titled “Using the Fourier
    Transform to Solve PDEs.” Read all of the lecture notes (4 pages).  
        
     These notes describe how to use the Fourier transform to solve the
    wave equation and the telegraph equation.  
        
     Studying this reading should take approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**5.2.3 Laplace’s Equation** <span id="5.2.3"></span> 
-   **Reading: MIT: Professor Matthew Hancock’s “Infinite Spatial
    Domains and the Fourier Transform: Fourier Transform Solution to
    Laplace’s Equation”**
    Link MIT: Professor Matthew Hancock’s [“Infinite Spatial Domains and
    the Fourier Transform: Fourier Transform Solution to Laplace’s
    Equation](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/lecture-notes/)[”](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/lecture-notes/)
    (PDF)  
        
     Instructions: Click on the link above. These are lecture notes from
    a PDE course at MIT. The beginning of the notes discusses some of
    the material covered in the previous sections. The material on
    Laplace’s equation begins on page 12. Read the entire set of lecture
    notes (13 pages).  
        
     Studying this reading should take approximately 4 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Naval Postgraduate School: Professor Beny Neta’s
    Partial Differential Equations MA 3132: Solutions of Problems in
    Lecture Notes: “Chapter 9.4: Fourier Transform Solutions of PDEs:
    Fourier Transforms of Derivatives”**
    Link: Naval Postgraduate School: Professor Beny Neta’s *Partial
    Differential Equations MA 3132: Solutions of Problems in Lecture
    Notes*: [“Chapter 9.4: Fourier Transform Solutions of PDEs: Fourier
    Transforms of
    Derivatives”](http://faculty.nps.edu/bneta/lnotes.html) (PDF)  
        
     Instructions: Click on the link above. Under “MA3132 Lecture Notes
    and Solution Manual,” find the link “Solution Manual for MA3132 in
    pdf.” Click on the link to download the document; it contains
    problems and solutions.  
        
     In the PDF, scroll down to page 290 and attempt problems 1-5. When
    finished, go to page 291 to find the solutions.  
        
     You should dedicate approximately 3 hours to complete this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Final Exam for Linear Partial Differential
    Equations (Fall 2006)**
    Link: MIT: [Final
    Exam](http://ocw.mit.edu/courses/mathematics/18-303-linear-partial-differential-equations-fall-2006/exams/)
    (PDF) for Linear Partial Differential Equations (Fall 2006)  
        
     Instructions: Click on the link above. In row 3 (Final Exam), go to
    the third (“tests”) column, and click on the “PDF” link. The final
    exam will download in PDF. Skip problem 4.  
        
     To check your solutions, follow the solutions link on the same
    page.  
        
     You should dedicate approximately 3 hours to complete this
    assessment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**Final Exam** <span id="6"></span> 
-   **Final Exam: The Saylor Founation’s “MA222 Final Exam”**
    Link: The Saylor Founation’s [“MA222 Final
    Exam”](http://school.saylor.org/mod/quiz/view.php?id=1074)  
      
     Instructions: You must be logged into your Saylor Foundation School
    account in order to access this exam. If you do not yet have an
    account, you will be able to create one, free of charge, after
    clicking the link.


