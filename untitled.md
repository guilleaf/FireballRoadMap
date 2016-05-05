This is a roadmap for the future of Fireball.
My vision is to raise Fireball as a friendly, widely use software for High Throughput Materials analysis.
The code must to be fast, robust, well written, accurate and sufficiently well tested.
We must have a clear idea of the power of the code but also its limitations, we need scientific proofs
of their accuracy to reproduce the geometry, dynamics, energetics and their derivatives.
We will create a code with a brand recognition, papers showing that recognition. 
This is an ambitious plan to put Fireball as fast and reliable atomistic simulation package on the Tight-Binding 
level of Theory. The next topics are my current list of tasks that we should address in the forthcoming months.

I will divide the topics by areas of expertise rather than urgency or priority. Feel free to open discussion about
some other tasks that I missed or tasks that should not be on this list.


Software Development
====================

  1. Fireball will be developed on Github, with documentation on Github Pages. Learn about Git, one nice document was written on Authrea: [A quick introduction to version control with Git and GitHub](https://www.authorea.com/users/5990/articles/17489)

  1. This roadmap is written on Authorea that is also integrated with Github so we have a coherent set of tools for direct the project as effectively as possible.

  1. For software development we will work using a Continous Integration model, test driven development and fork-modify-test-merge where I (Guillermo) will be the official merger and gatekeeper for the project. The reason for that is not control but freedom, you can fork Fireball, work by your own, break things, do a mess if you want. When you are erady to merge, your should test your branch, assure that all tests succeed, adding new tests for your own development and asking permission for merge. I will check that the merge will not create ruptures with the code and will have a stable and robust code as a result.

  1. We need test-coverage, right now we start with 0%, achive 10% will be relatively easy, 20% we can get in the first month, 30% is a poor but decent level by the end of the summer 2016. The size of the code and the fragmentation of the drivers will make challenging achieve 50% but that should be our goal by the end of the year.

  1. We need a platform for testing, I (Guillermo) am using Travis-CI for PyChemia. The nature of Fireball, being a Fortran code we should consider something like [Buildbot](http://buildbot.org)

  1. Fireball should run and pass test with Intel and gfortran compilers. That is not the case right now and that is one important task. I propose as minimum Intel 2011 and Gfortran 4.6
  
  1. Using Fortran 2003 should be safe (see: [GCC Fortran 2003 status](http://gcc.gnu.org/wiki/Fortran2003Status)) the situation with Fortran 2008 is less mature ([GCC Fortran 2003 status](https://gcc.gnu.org/wiki/Fortran2008Status))
  

Applications
============

   1. We need to identify a niche market for Fireball and explote it. Right now I am considering 


Branding
========

   1. Science is a human product and some of the rules of society also apply to us. We need brand recognition. A consistent image. One task is to have and use a consistent Logo for the code. The basic rules are: Small number of colors, I (Guillermo) create the logo for PyChemia using [Inkscape](https://inkscape.org/en/), in fact I have a set of of similar but not identical set of logos for the code. I use them all the time that PyChemia is presented. Having a logo for Fireball help us to have a familiar image for our code. The image should be a vectorial image in SVG format. Simple, elegant and with transparent background. The logo could include have hidden symbolism, many brand logos do. That increases the power of it.  