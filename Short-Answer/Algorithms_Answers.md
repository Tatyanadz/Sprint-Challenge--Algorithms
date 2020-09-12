#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This is logarithmic = O(log n) when input gets bigger, it will take more time to add numbers for 'a' before loop stops



b) This is linearithmic = O(n log n) when input gets bigger, first inner loop will take same amount of time every pass but 2nd inner loop of while will increase in runtime, first loop is linear and second loop depends on n


c) Liner = o(n) This will recurse n times until it hits the base

## Exercise II


Start with finite amount of eggs and finite size building with n - stories

Go through each floor and throw an egg

Check for the following:

if egg is broken - mark the floor as where eggs start breaking, and break out of the loop as we know going pass this floor will result eggs always breaking

else increase count of dropped eggs.

End the loop and see which floor eggs broke and how many eggs were dropped so far

Based on the information, this algorithm have best of case O(1) where it will be same floor no matter N story building otherwise it will linear O(n) as floor needs to be calculated based on height difference of floor based on input and then find the floor