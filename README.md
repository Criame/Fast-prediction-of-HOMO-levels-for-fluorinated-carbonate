# Fast-prediction-of-HOMO-levels-for-fluorinated-carbonate
 The model of multiple linear regression (MLR) was well trained with counting descriptors , generating a concise formula , providing the platform for fast predicting the HOMO levels of linear fluorinated carbonates.


Descriptors:




![image](https://github.com/Criame/Picture/blob/main/1.png)





In purpose of observing influence of fluorine atoms on each other, we divided the carbonate into left (more fluorine atoms) and right (less fluorine atoms) sides. If both sides have the same number of fluorine atoms, the side with longer alkyl will be set as the left. Correspondingly, the number of fluorine atoms in different positions is described by α-F, β-F, γ-F, and α’-F, β’-F, γ’-F, respectively. the number of alkyl groups on α-C/α’-C also has a vital effect on HOMO levels, thus, a brand new descriptor Sum-Cβ/β’ was defined. These seven descriptors apply to 7pred-HOMO.exe. 


Finally, for the sake of brevity, α-F and α'-F were combined to form Sum-Fα/α’, β-F and β'-F were combined to form Sum-Fβ/β’, and γ-F and γ'-F were combined to form Sum-Fγ/γ’. These descriptors with Sum-Cβ/β’ apply to 4pred-HOMO.exe. 
                      ![image](https://github.com/Criame/Picture/blob/main/2.png)


For 4pred-HOMO.exe, you need to type in four descriptors like “0 0 0 2” and then it will give you a predicted HOMO level; for 7pred-HOMO.exe, you need to type in seven descriptors like “0 0 0 0 0 0 2”. For some complex fluorinated carbonates, we would recommend the 7pred-HOMO model to obtain more accurate predictions. Or you can make predictions on both models and take it an average.
