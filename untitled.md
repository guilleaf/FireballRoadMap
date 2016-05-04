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

  * Fireball will be developed on Github, with documentation on Github Pages. 
  * This roadmap is written on Authorea that is also integrated with Github so we have a coherent set of tools for direct the project as effectively as possible.
  * For software development we will work using a Continous Integration model, test driven development and fork-modify-test-merge where I (Guillermo) will be the official merger and gatekeeper for the project. The reason for that is not control but freedom, you can fork Fireball work by your own, break things, do a mess if you want. When you are erady to merge, your should test your branch, assure that all tests succeed, adding new tests for your own development and asking permission for merge. I will check that the merge will not create ruptures with the code and will have a stable and robust code as a result.
  * We need test-coverage, right now we start with 0%, achive 10% will be relatively easy, 20% we can get in the first month, 30% is a poor but decent level by the end of the summer 2016. The size of the code and the fragmentation of the drivers will make challenging achieve 50% but that should be our goal by the end of the year.
  * We need a platform for testing, I (Guillermo) am using Travis-CI for PyChemia,
  