# Non-uniform-fft
This is trying to solve the problem of large samples in Wiener filtering

I tried nufft in Matlab, but got inconsistent results due to there is no inverse nufft, i.e., nuifft.

I tried fftw, seems fftw is default algorithm in python and Matlab. The first time to run the fft is very slow. Then it will be faster after first running. ![image](https://user-images.githubusercontent.com/4518648/180654577-d9f6ea19-f669-46f8-a2d6-9ff64ef21330.png)
