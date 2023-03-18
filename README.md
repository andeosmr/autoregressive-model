## A demonstration of the autoregressive model with some exercises

### The demonstration

You can run the main, and it will generate some schematic graphs that show the current form of the noise (noise.jpg), the autocorrelations for various lags (corrvector.jpg), the coefficients for the Yule-Walker method (ar.jpg), and the resulting form of the noise if these coefficients are used to create a new noise (next_noise.jpg).

You can change the value of the noise color (it is set to BROWN by default) in order to see the results for different noise colors.

You can check the graphs' validity by the graphs provided in the solutions_jpgs/ folder.

[Currently the noise "color" SINE is giving exponentially growing solutions, which is wrong]