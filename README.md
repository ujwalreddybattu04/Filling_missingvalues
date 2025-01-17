#-------------------------------------------README-----------------------------------------------------------------#
-THIS CODE WILL TELL ABOUT HOW TO HANDLE MISSING VALUES IN A PATICULAR DATASET
There are basically 3-types of imputations 
1.mean imputation
2.median imputation
3.mode imputation
#------------------------------------------MEAN IMPUTATION---------------------------------------------------------#
mean imputation ex dataset: name[ujwal,krish,jain] age[25,-,30]
calculate the mean 25+30/2=27.5
then the dataset will becomes name[ujwal,krish,jain] age[25,27.5,30]
sutable for - normal distribution
#------------------------------------------MEDIAN IMPUTATION---------------------------------------------------------#
median imputation ex dataset: name[alice,bob,charlie,david] age[25,-,30,35]
calculate the median =30
the dataset will become name[alice,bob,charlie,david] age[25,30,30,35]
sutable for skewed distribution
#------------------------------------------MODE IMPUTATION---------------------------------------------------------#
Mode imputation ex dataset name[alice,bob,charlie,david] age[blue,-,red,blue]
calculate the mode= blue
the dataset will become name[alice,bob,charlie,david] age[blue,blue ,red,blue]
sutable for categorial data (colours,cities,etc...)
