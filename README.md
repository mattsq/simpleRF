## simpleRF
Marvin N. Wright, wright@imbs.uni-luebeck.de

### Description
Implements random forests (RF, Breiman 2001) with emphasis on simplicity. Uses reference classes and only plain R. Not optimized for computation speed. Allows rapid prototyping of RF-type algorithms.

For an runtime-optimized random forest implementation, see [ranger](github/imbs-hl/ranger).

### TODO
Features: 
* Variable importance
* Unordered factor splitting
* Use a standard `predict()` function
* ...

Technical stuff:
* Software tests
* Profile the code. Possible to make it faster without losing simplicity?

Be careful, this package is not extensively tested!