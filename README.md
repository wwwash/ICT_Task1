# ICT_Task1
##This code provides a set of pairs(a,y0).a is the input sequence of complex symols,y0 is the output symbol.a=[a(-N),a(-N+1),...,a(-1),a(0),a(1),...,a(N-1),a(N)], N is the memory size.a0 is in the specified constellation M. For example, a(0)=sqrt(2)*[1+1j,-1+1j,-1-1j,1-1j] in QPSK format. 

##Implement Version:Python 3.5

##Packages need to be installed: Numpty,scipy, matplotlib, intertools. Please notice that there is a function named "Product" in the "intertools" package, which can achieve the "permn" function in Matlab. "Product" is usde to generate the neighboring symbols at left and right side of a(0). Left side symbols:[a(-N),a(-N+1),...,a(-1)], Right side symbols:[a(1),...,a(N-1),a(N)]

##Output Visulization: Please find the PNG picture in the zip file.
