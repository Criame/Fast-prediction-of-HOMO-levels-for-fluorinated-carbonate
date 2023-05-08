# Fast-prediction-of-HOMO-levels-for-fluorinated-carbonate
 The model of multiple linear regression (MLR) was well trained with counting descriptors , generating a concise formula , providing the platform for fast predicting the HOMO levels of linear fluorinated carbonates.


Descriptors:


![image](https://github.com/Criame/Picture/blob/main/1.png)





In purpose of observing influence of fluorine atoms on each other, we divided the carbonate into left (more fluorine atoms) and right (less fluorine atoms) sides. If both sides have the same number of fluorine atoms, the side with longer alkyl will be set as the left. Correspondingly, the number of fluorine atoms in different positions is described by α-F, β-F, γ-F, and α’-F, β’-F, γ’-F, respectively. the number of alkyl groups on α-C/α’-C also has a vital effect on HOMO levels, thus, a brand new descriptor β-C was defined. These seven descriptors apply to 7pred-HOMO.exe. 


Finally, for the sake of brevity, α-F and α'-F were combined to form Alpha-F, β-F and β'-F were combined to form Beta-F, and γ-F and γ'-F were combined to form Gama-F. These descriptors with β-C apply to 4pred-HOMO.exe. 
