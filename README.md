This directory contains the files mentioned in the article "Analyzing the function z^^(1/2)", by William Paulsen

README.md
DataSet1.txt
DataSet2.txt
MathDagger.zip
SageDagger.zip

The raw data, giving the tetration values to 100 places for two circles (200 points each) are in DataSet1.txt and DataSet2.txt.  
These files are designed to be read in either Mathematica or SageMath.

DataSet1.txt gives the fractional iterates F(a) = b^^a for the base b = 3 + cos(pi n/100) + i sin(pi n/100):  (A circle of radius 1 centered at 3)

J[n] = F(i), P[n] = F(1/12), Q[n] = F(1/6), R[n] = F(1/4), S[n] = F(1/3), T[n] = F(5/12), U[n] = F(1/2), V[n] = F(7/12), W[n] = F(2/3), X[n] = F(3/4), Y[n] = F(5/6), Z[n] = F(11/12)

DataSet2.txt gives the fractional iterates F(a) = b^^a for the base b = (1+i) + 3 cos(pi n/100)/4 + 3 i sin(pi n/100)/4: (A circle of radius 3/4 centered at 1+i) 

J[n] = F(i), K[n] = F(-i), P[n] = F(1/12), Q[n] = F(1/6), R[n] = F(1/4), S[n] = F(1/3), T[n] = F(5/12), U[n] = F(1/2), V[n] = F(7/12), W[n] = F(2/3), X[n] = F(3/4), Y[n] = F(5/6), Z[n] = F(11/12) 

The zip file MathDagger.zip contains the Mathematica notebook DaggerTrack.nb, which was used to create this data.  It is well documented, and will take you through the steps of calculation any tetration.

The zip file SageDagger.zip contains the SageMath notebook DaggerTrack.ipynb, which is the corresponding notebook for SageMath.  

