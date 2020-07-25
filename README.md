# r_census 
Este projeto visa comparar o desempenho de 3 modelos de algoritmos tradicionais de data science em uma base de dados census. Os resultados de Random Forest, Regressão Logística e SVM estão expostos abaixo e os scripts nesse respectivo projeto (tudo foi feito em R):

Percebemos que neste caso o algoritmo de random forest tem um melhor desenpenho se considerarmos a precisão do mesmo.

Resultados Random Forest

previsoes
       0    1
  0 3458  250
  1  401  775
                                          
               Accuracy : 0.8667          
                 95% CI : (0.8569, 0.8761)
    No Information Rate : 0.7901          
    P-Value [Acc > NIR] : < 2.2e-16       
                                          
                  Kappa : 0.6187          
                                          
 Mcnemar's Test P-Value : 4.128e-09       
                                          
            Sensitivity : 0.8961          
            Specificity : 0.7561          
         Pos Pred Value : 0.9326          
         Neg Pred Value : 0.6590          
             Prevalence : 0.7901          
         Detection Rate : 0.7080          
   Detection Prevalence : 0.7592          
      Balanced Accuracy : 0.8261







Resultados Regressão logística

previsoes
       0    1
  0 3457  251
  1  451  725
                                         
               Accuracy : 0.8563         
                 95% CI : (0.8461, 0.866)
    No Information Rate : 0.8002         
    P-Value [Acc > NIR] : < 2.2e-16      
                                         
                  Kappa : 0.5826         
                                         
 Mcnemar's Test P-Value : 5.878e-14      
                                         
            Sensitivity : 0.8846         
            Specificity : 0.7428         
         Pos Pred Value : 0.9323         
         Neg Pred Value : 0.6165         
             Prevalence : 0.8002         
         Detection Rate : 0.7078         
   Detection Prevalence : 0.7592         
      Balanced Accuracy : 0.8137







SVM

previsoes
       0    1
  0 3491  217
  1  501  675
                                          
               Accuracy : 0.853           
                 95% CI : (0.8427, 0.8628)
    No Information Rate : 0.8174          
    P-Value [Acc > NIR] : 2.061e-11       
                                          
                  Kappa : 0.5618          
                                          
 Mcnemar's Test P-Value : < 2.2e-16       
                                          
            Sensitivity : 0.8745          
            Specificity : 0.7567          
         Pos Pred Value : 0.9415          
         Neg Pred Value : 0.5740          
             Prevalence : 0.8174          
         Detection Rate : 0.7148          
   Detection Prevalence : 0.7592          
      Balanced Accuracy : 0.8156
