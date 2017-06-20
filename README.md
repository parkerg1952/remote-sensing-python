# NEON Lesson Building Repository - Remote Sensing Python
This is a development repository for the
<a href="http://www.neondataskills.org" target="_blank">NEON Data Skills portal</a>. 
Here the NEON Data Skills team develops and builds new content. Content is 
transferred to the NEONScience/NEON-Data-Skills repository to be published. 

This directory will contain all the code related to the Remote Sensing Python
lessons originally created for Data Institute 2017. 


## Other associated directories

*`images/Remote-Sensing-Python/...`: each series/lesson will have a subdirectory with the same naming/file
path as in the `_posts` directory. This allows for organized and automated 
creation of files and embedding the images in the files.  
* `code/Remote-Sensing-Python/...`: this directory (same file paths inside) will contain any code that 
should be downloadable with the lesson via the "Download code" button at the 
bottom of each tutorial page. 

## Originally from a file called README that was added into this file

The Day 1 Lesson (Jupyter Notebooks) were designed in the following order:

1. intro_neon_aop_hyperspectral_python.ipynb
2. hdf5_hyperspectral_functions.ipynb
3. plot_spectral_signatures.ipynb
4. calculate_ndvi_extract_spectra_with_masks.ipynb

Data, once uploaded should be stored under the Remote-Sensing-Python folder, or the paths to access data will need to be modified in the notebook scripts.
I am still updating and adding functions to the neon_aop.py module that is loaded at the start of lessons 2-4, but all functions required to run the notebooks should already be uploaded.
