## Astrophotography Post Processing with OpenCV
#### Dependencies
* Python (Python 3 recommended, not tested on Python 2)
* Matplotlib
* Numba
* Numpy
* OpenCV
* Scipy
* Scikit-image


## Install
```pip install astropenap```

## Current Functionalities
* 8-bit, 16-bit, 32-bit image conversion
* Background subtraction (gradient removal included)
* Chromatic adaptation (build-in D50 to/from D65 with XYZ scaling/Bradford/Von Kries method, custom white-point or method allowed)
* Color matrix conversion (similar to that of ```imagemagick```)
* Color space conversion (built-in sRGB to linear RGB D65, more in development)
* Deconvolution (NOT recommended due to lack of deringing algorithm)
* Gamma correction
* High dynamic range 2D deconvolution
* Histogram
* Local histogram equilization
* Logging
* Masks: star mask, global threshold mask, etc.
* RNC stretch (credit to Roger N. Clark for the functions)
* Simple star detection
* Star (PSF) fitting with 2D Gaussian (more PSF models in development)
* Star size reduction
* Starlet transformation

## Example
Example in ```OpenAP/tests```

```test_main.py``` outlines workflow associated with images with extended nebulosity.

```test_dso.py``` outlines workflow associated with images with little to none nebulosity.

## Credit
Thanks [@jinleic]( https://github.com/jinleic ) for inspiration and packaging.
