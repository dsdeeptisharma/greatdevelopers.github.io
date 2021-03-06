---
layout: post
title:  "Saturday Seminars"
date:   2016-04-13 10:30:00 +0530
author: "Pritika Malhotra"
categories: presentation
---
﻿Date-26.03.2016

Entry Task - Deepak Pruthi
Installation of SageMath and using it to solve Equations:
SageMath - Rushingly Illustrated about the installation and some basic usage of:
* tutorial() - Open all offline tutorial of Sage
* solve() - for solving equations
* desolve() - used for solving differential equation
* Simple Harmonic Motion


Sage is an open-source alternative to Maple, Mathematica, Magma and MATLAB.


He didn’t prepare well enough. Sir told him to solve the same equation on a paper first and then to illustrate in SageMath. But he wasn’t able to do that. So wasn’t considered ready to be included in GD and was given another chance.


Installation:
Q: What is meaning of upstream-binary in installation command?
Sagemath-upstream-binary is the name of the package to be installed.


What is a PPA?
Ans: A Personal Package Archive (PPA) is a special software repository for uploading source packages to be built and published as an APT repository by Launchpad.[1] While the term is used exclusively within Ubuntu, Launchpad host Canonical envisions adoption beyond the Ubuntu community. 
Read more: Personal Package Archive


Declaring two variables: x,y = var(‘x,y’)  → (1)
What will be the type of Variables?
The language that Sage uses is almost the same as the Python programming language. Python variables do not need explicit declaration to reserve memory space. The declaration happens automatically when you assign a value to a variable. The equal sign (=) is used to assign values to variables.


Use of LHS in (1)?
According to the discussion the (1) shows the dependency of variables i.e. output of a single equation involving two variables depends upon the other variable.


A Talk about experience out of GD…..
By Manpreet:
Marks that she used to secure in her class decreased after coming to GD. She seems disinterested in attending classes.
She became worried after losing GD membership. It’s the place she could always turn and learn from others as well and solve her problem.


By Monisha:
She didn’t feel like opening emails after getting out and felt low for the entire week. She came to sir to know the reason for discontinuing the membership. But he was busy and for a few days couldn’t get a chance to talk to him. She felt free and didn’t do any work.


By Kamalpreet:
According to her one gets more time to spend with his/her family. You feel free most of the time and get to know about your potential. “This experience is also important”, she added. She also explained her experience about M.Tech. and as a TA. First she thought of teaching as nothing meaningful, but later on she got interested in it and finally she is enjoying it as she tries to share her knowledge with students.


By Amritpal:
He replied to a thread in GD and got an instant reply. He got excited at first but later he realised that it was the opposite. The email read, “you don’t have permission to post to the group”. He too was missing GD mails.There was a sense of freedom but he didn’t stop working during this period.


There was another presentation by Tamandeep. He was there to show us the improvements that he had made in his project. He had adopted modular approach and made functions to achieve the task as suggested by Sir.


Questions:
* What’s the new name of mathpiper? Or is it the new one?
MathPiper is a new mathematics-oriented programming language which is simple enough to be learned as a first programming language and yet powerful enough to be useful in any science, mathematics, or engineering related career.  MathPiper is also a Computer Algebra System (CAS) which is similar in function to the CAS which is included in the TI 89 and TI 92 calculators.
MathRider contains a computer algebra system called MathPiper.
Read more: http://comments.gmane.org/gmane.comp.mathematics.sage.education/759


* Is there any free FOSS alternative for DAE solver like sage.
Yes, there are DAE solvers in sage.
* desolve - Compute the “general solution” to a 1st or 2nd order ODE via Maxima.
* desolve_laplace - Solve an ODE using Laplace transforms via Maxima. Initial conditions are optional.
* desolve_rk4 - Solve numerically IVP for one first order equation, return list of points or plot.
* desolve_system_rk4 - Solve numerically IVP for system of first order equations, return list of points.
* desolve_odeint - Solve numerically a system of first-order ordinary differential equations using odeint from scipy.integrate module.
* desolve_system - Solve any size system of 1st order odes using Maxima. Initial conditions are optional.
* eulers_method - Approximate solution to a 1st order DE, presented as a table.
* eulers_method_2x2 - Approximate solution to a 1st order system of DEs, presented as a table.
* eulers_method_2x2_plot - Plot the sequence of points obtained from Euler’s method.


ode_solver() is another class.


* Alternative JavaScript frameworks that can help in CAD drawing.
http://www.learningjquery.com/2015/05/7-awesome-javascript-libraries-for-drawing


* And what types of solvers are available in MATLAB and the equations that they can solve?
Ode23: Uses simultaneously second and third order Runge Kutta formulas to make estimates of the error,and calculate the time step size. Since the second and third order RK require less steps, ode23 is ”less expensive” in terms of computation demands than ode45, but is also lower order. Use for nonstiff ODEs.
Ode45; Uses simultaneously fourth and fifth order RK formulas to make error estimates and adjust the time step accordingly. MATLAB recommends that ode45 is used as a first solver for a problem. For nonstiff ODEs.
ode113:Uses variable-order Adams-Bashforth-Moulton solver. For problems with stringent error tolerances or for solving computationally intensive problems. For nonstiff ODEs.
Ode15s: If using ode45 turns out to be a slow process, then the DEs you are solving are stiff. Use ode15s or one of the solvers (ode23s, ode23t, ode23tb).


* How much is octave behind in solving differential equations?
For non-stiff ODEs, Matlab has three solvers:
Ode113, ode23 and ode45 implement an Adams-Bashforth-Moulton PECE solver and explicit Runge-Kutta 
formulas of orders 2 and 4, respectively.
For stiff ODEs, Matlab has four ODE solvers:ode15s,ode23s,ode23t, and ode23tb implement
the numerical differentiation formulas, a Rosenbrock formula, a trapezoidal rule using a “free”
interpolant, and an implicit Runge-Kutta formula, respectively.
According to their documentations, Octave solve non-stiff ODEs using the Adams methods and stiff equations using the backward differentiation formulas. These are implemented in lsode in Octave. Matlab and Octave have state-of-the-art variable-order, variable-time step methods for both non-stiff and stiff ODEs available, with Matlab’s implementation being the richest and its stiff solvers being possibly more efficient
http://userpages.umbc.edu/~gobbert/papers/SharmaGobbertTR2010.pdf




* Medium order differential equation? And other orders?
http://in.mathworks.com/help/matlab/ref/ode45.html


* Does solving of differential equation means we need to specify what Solver is to be used?
http://in.mathworks.com/help/matlab/math/choose-an-ode-solver.html
 
* If these solvers are specified by the users or they are automatically chosen?
In all of the examples examined, it’s the user who decides the ode solver to be used. 


Sir suggested that if user specifies the solver then it can be another project to make it automatic.
