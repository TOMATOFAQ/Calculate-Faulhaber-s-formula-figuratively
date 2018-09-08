<<<<<<< Updated upstream
# Calculate_sum_in_a_new_way
=======
# Calculate Faulhaber's formula figuratively

## Background   
The following message is picked up from the wikipedia:
> ## Faulhaber's formula
>In mathematics, Faulhaber's formula, named after Johann Faulhaber, expresses the sum of the p-th powers of the first n positive integers.https://en.wikipedia.org/wiki/Faulhaber%27s_formula

>![](https://wikimedia.org/api/rest_v1/media/math/render/svg/cdfa28bc350e73f808fc51da16d427df1a45fd28)

> ## Figurate number
>The term figurate number is used by different writers for members of different sets of numbers, generalizing from triangular numbers to different shapes (polygonal numbers) and different dimensions (polyhedral numbers). https://en.wikipedia.org/wiki/Figurate_number

>![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Nicomachus_theorem_3D.svg/220px-Nicomachus_theorem_3D.svg.png)

## My method
My English is poor,but it's luckily what I am going to explain are mostly shown by pictures.

## Express regcursively
> S3(n) means the sum of the p-th powers which p equals -3

S3(n) = [(1+3*n)*S2(n)]/(4) + 0.125*S1 + 0.125*S2

S4(n) = [(1+4*n)*S3(n)]/(5) + 0.200*S1 + 0.400*S2 + 0.200*S3

S5(n) = [(1+5*n)*S4(n)]/(6) + 0.194*S1 + 0.667*S2 + 0.722*S3 + 0.250*S4

S6(n) = [(1+6*n)*S5(n)]/(7) + 0.143*S1 + 0.786*S2 + 1.429*S3 + 1.071*S4 + 0.286*S5

S7(n) = [(1+7*n)*S6(n)]/(8) + 0.104*S1 + 0.750*S2 + 2.021*S3 + 2.500*S4 + 1.438*S5 + 0.312*S6

S8(n) = [(1+8*n)*S7(n)]/(9) + 0.111*S1 + 0.704*S2 + 2.333*S3 + 4.148*S4 + 3.889*S5 + 1.815*S6 + 0.333*S7

S9(n) = [(1+9*n)*S8(n)]/(10) + 0.130*S1 + 0.800*S2 + 2.600*S3 + 5.600*S4 + 7.420*S5 + 5.600*S6 + 2.200*S7 + 0.350*S8

S10(n) = [(1+10*n)*S9(n)]/(11) + 0.091*S1 + 0.955*S2 + 3.273*S3 + 7.182*S4 + 11.455*S5 + 12.091*S6 + 7.636*S7 + 2.591*S8 + 0.364*S9

S11(n) = [(1+11*n)*S10(n)]/(12) + 0.014*S1 + 0.833*S2 + 4.208*S3 + 10.000*S4 + 16.583*S5 + 21.000*S6 + 18.417*S7 + 10.000*S8 + 2.986*S9 + 0.375*S10

S12(n) = [(1+12*n)*S11(n)]/(13) + 0.084*S1 + 0.441*S2 + 4.256*S3 + 13.945*S4 + 25.391*S5 + 33.845*S6 + 35.539*S7 + 26.654*S8 + 12.692*S9 + 3.385*S10 + 0.385*S11

S13(n) = [(1+13*n)*S12(n)]/(14) + 0.412*S1 + 0.533*S2 + 3.583*S3 + 15.414*S4 + 38.558*S5 + 56.530*S6 + 63.090*S7 + 56.570*S8 + 37.060*S9 + 15.714*S10 + 3.786*S11 + 0.393*S12

S14(n) = [(1+14*n)*S13(n)]/(15) + 25.251*S1 + -74.235*S2 + 102.343*S3 + -55.081*S4 + 78.775*S5 + 83.043*S6 + 116.388*S7 + 109.338*S8 + 85.831*S9 + 49.889*S10 + 19.067*S11 + 4.189*S12 + 0.400*S13

S15(n) = [(1+15*n)*S14(n)]/(16) + 1498.172*S1 + -4758.971*S2 + 6390.418*S3 + -4832.312*S4 + 2418.210*S5 + -664.706*S6 + 387.195*S7 + 182.951*S8 + 184.104*S9 + 124.786*S10 + 65.427*S11 + 22.749*S12 + 4.594*S13 + 0.406*S14

>>>>>>> Stashed changes
