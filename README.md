If you surveyed a group of people and asked them if they prefer Pepsi or Coke,
 and you wanted to know whether these proportions differed within this sample,
 you should not use a t-test, standard z-test or chi^2 test, since the 
proportion of Pepsi preferers and Coke preferers were non-indepedently 
sampled (ie, a Coke preferer cannot also prefer Pepsi). 
Rather, a more appropriate test can be derived assuming multinomial sampling.
This function works for any number of proportions from the same survey, 
allows contrasts between arbitrary groupings of proportions, and 
provides confidence intervals and p-values. 

Scott & Seber, Difference of proportions from the same survey,
The American Statistician 37(4): 319-320, 1983.
