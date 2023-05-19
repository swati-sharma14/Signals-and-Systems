# Signal Convolution and Output

Welcome to the "Signal Convolution" repository! 🔍

This repository contains code to perform signal convolution and compute the resulting output signal for different input signals and system impulse responses.

## System Impulse Response
The system S is characterized by its impulse response, h(t), which is defined as:
h(t) = 1/4 * e^(-2t) - e^(-t) * u(t)

## Part a) Input: x(t) = cos(t) * u(t)
In this part, the response of the system is determined when the input signal x(t) is given by:
x(t) = cos(t) * u(t)

The following signals are plotted for t in the range [0, 20]:
- x(t): The input signal, cosine of t multiplied by the unit step function.
- h(t): The impulse response of the system.
- y(t): The output signal obtained by convolving x(t) and h(t).

## Part b) Input: x(t) = e^(-t) * sin(t) * u(t)
In this part, the response of the system is computed when the input signal x(t) is defined as:
x(t) = e^(-t) * sin(t) * u(t)

The following signals are plotted for t in the range [0, 20]:
- x(t): The input signal, exponential decay multiplied by sine of t and the unit step function.
- h(t): The impulse response of the system.
- y(t): The output signal obtained by convolving x(t) and h(t).

Feel free to explore the code and modify the input signals or the system impulse response. You can plot different signals by adjusting the range of time values.

Enjoy exploring signal convolution and the resulting output! 🔬
