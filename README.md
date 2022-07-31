# Neural_Network_Charity_Analysis

## Analysis to determine where to make investments with favorable outcomes 
----
### Results:
- I targeted the "Is Successful" column 
- At first I left all as features, then i started removing and testing. Ultimatly I removed the "Status" 
- I ended with 3 layers of 85 25 and 20 on my 4th iteration. My best run was the 2nd run of 2 layers of 25 and 15 at 200 Epoch's with the "Status" column removed.
- I was unable to get over 75% accuracy 

### Summary
I would try using the SVM model next to evaluate effectivness; the setup i had was better than a coinflip, but at 73% effectivness I would not be confident enough in the model to make investment decisions. Using a simpler supervised model may be more appropriate, or as stated before, an attempt using the SVM.   


