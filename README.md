# radiogalsim
Simulate the microJansky radio sky to create image pairs for learning-based deconvolution  

The following will simulate 800 training image pairs and 100 validation image pairs, using a PSF/kernel that corresponds to a DSA-2000-like instrument. 

$ python make_img_pairs.py -k example-rci-psf.fits -o output_directory 

