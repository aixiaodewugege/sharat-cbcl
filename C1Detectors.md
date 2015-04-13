# Introduction #

This code implments a scanning based object detector similar to the scheme adopted in [Bileschi's thesis](http://cbcl.mit.edu/projects/cbcl/publications/theses/thesis-bileschi.pdf). This behaves similarly to histogram of gradient detectors. The detection proceeds at multiple scale. The demo code included contains pre-built car and pedestrian detectors.

# Installation #
To use this code
```
svn checkout http://cbcl-model-matlab.googlecode.com/svn/trunk/
svn checkout http://sharat-cbcl.googlecode.com/svn/trunk/sharat-cbcl/c1-detectors
```

## Running the code ##
```
cd /path/to/c1-detectors
matlab
(In matlab)
addpath(genpath('/path/to/cbcl-model-matlab'))
demo
```