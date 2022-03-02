# Romberg-Integration-Example
A small program that I designed and wrote to aid in understanding and visualizing Romberg integration. 

The notation and the equations used within the code are taken from the book "Computational Physics" by Newman. 

Romberg integration is an adapative approach to numerically calculating an integral. In this example the integration is done with trapzoidal slices. The adapative part comes from the number of slices we use to calculate the integral. This involves five steps:

1) Calculate the integral with a set number of slices
2) Double the number of slices
3) Calculate the error between the previous integrations
4) Correct the integration with the calculated error
5) Repeat steps 2-4 until the desired accuracy is reached. 
