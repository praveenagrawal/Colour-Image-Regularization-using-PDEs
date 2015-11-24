# CS 663 Fundamentals of Digital Image Processing Course Project
Implementation of the following paper:
https://tschumperle.users.greyc.fr/publications/tschumperle_pami05.pdf

Code folder
===========
main.m
Has 4 sections:
Image Denoising/Restoration
Image Inpainting
Image Resizing
Flow Visualization

Select the appropriate section and change the following variables accordingly before execution:
1. Path to the input image in imread
2. stepsize (dt)
3. End time = number of iterations/step size (tend)
4. 'if loops' are present in the iterating loops for the sake of displaying intermediate results


Input folder
Has the test inputs taken from the original paper and slides referred to in the report (not all of the test inputs have been used by us)

Output folder
Has results for different application tested in images from 'Input Folder'
name: <operation being done>_<number of iterations>_<step size used>