# Forward_Design

Main paper has result_V.csv file with 8 columns representing wavelength(1000-1800),6 parameters and lastly transmission respectively. Basically, 147,456 unique examples generated through FDTD simulations in the "result_V.csv" file. which has 5.8gb for that it took all night for just train the model.

I have used the model weights and architecture for performance analysis in Forward_ana file later. 

Similar anaylsis is done for inverse model, but the results were not good. 
I have attached a small sample of result_H file where last 6 columns are parameters and previous columns are transmission spectrum data.

It becomes tough with this result_V and result_H big files, besides if I take sample of that maybe that doesnot represent the whole simulation which may be the cause behind results are not good
