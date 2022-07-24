# Non-uniform-fft
This is trying to solve the problem of large samples in Wiener filtering

I tried nufft in Matlab, but got inconsistent results due to there is no inverse nufft, i.e., nuifft.

I tried fftw, seems fftw is default algorithm in python and Matlab. The first time to run the fft is very slow. Then it will be faster after first running.
