# Introduction to Image Understanding Homework 1: Power Law Transformation

## Overview

1. Upload a personal image in a hosting place that can be accessed using an URL. Alternatively, you can pick an image from an URL already available (but not the ones used in the lecture). Please select an image with some brightness problems, either too dark or too bright. Because you will try to fix that problem.
2. Display the image making sure that the image has the color channels in the right order.
3. Convert your image into grayscale (you can use any library for this).
4. Implement power law transformation ($s = c$ $r^{\gamma}$) to fix the brightness. You can use $c=1$. Do not forget to normalize your input intensities into [0,1] range. Do not use a built-in function from any library. If your image suffers from low intensities (too dark), $\gamma$ values smaller than 1 should help. If your image suffers from high intensities (too bright), $\gamma$ values greater than 1 should help. Explicitly write which $\gamma$ value you chose.
5. Plot two images (before and after power law transformation) side by side.
