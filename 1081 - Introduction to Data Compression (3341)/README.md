# 1081 - Introduction to Data Compression (3341)

## Homework 1

(a) Write a program to compute the first-order entropy of some of the image and speech files.

(b) Pick one of the image files and compute its second-order entropy. Comment on the difference between the first- and second-order entropies.

(c) Compute the entropy of the differences between neighboring pixels for the image you used in part (b). Comment on what you discover.

## Homework 3

Generate a binary sequence of length $L$ with $P(0) = 0.8$, and use the arithmetic coding algorithm to encode it. Plot the difference of the rate in bits/symbol and the entropy as a function of $L$. Comment on the effect of $L$ on the rate.

## Homework 4

1. For the companding quantizer of Example 9.6.1, what are the outputs for the following inputs: -0.8, 1.2, 0.5, 0.6, 3.2, -0.3? Compare your results with the case when the input is directly quantized with a uniform quantizer with the same number of levels. Comment on your results.
2. Generalize the Jayant quantizer to the nonuniform case. Assume that the input is from a known distribution with unknown variance. Simulate the performace of this quantizer over the same range of ratio of variances as we have done for the uniform case. Compare your results to the fixed nonuniform quantizer and the adaptive uniform quantizer. To get a start on your program, you may wish to use `misnuq.c` and `juquan.c`.

## Homework 5

Use 1-bit DPCM to encode a graylevel image.