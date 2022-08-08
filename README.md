# Girl Education Spending Tracker | CivicDataLab
Analysis of all the classified schemes to understand the state of girl-child education in Uttar Pradesh, India


# Cleaned_UP_Schemes
In this file we merged and cleaned the datasheets to get a final dataset of all the classified educational expenditure schemes in Uttar Pradesh. 

[haq_unique_schemes](https://docs.google.com/spreadsheets/d/1lB9C6dZIJZErvjn4wwSXCK_qtyAOP9JY/edit?usp=sharing&ouid=107918389837609878151&rtpof=true&sd=true): containing the classification of the types of schemes & mode of benefit of transfer


[haq_data_renamed](https://docs.google.com/spreadsheets/d/1NxPfBjU9QD2y8f-EEAX9TMgOuK1T3err/edit?usp=sharing&ouid=107918389837609878151&rtpof=true&sd=true): containing all the schemes including the unclassified ones. 


# EDA_UP_Schemes

In this file, we did an exploratory data analysis of the dataset obtained from [Cleaned_UP_Schemes](https://github.com/CivicDataLab/UPFiscalData_SchemeAnalysis/blob/f47de51326652a959001966393582dd42a19ed1c/Cleaned_UP_Schemes.Rmd), i.e, [haq_final](https://github.com/CivicDataLab/UPFiscalData_SchemeAnalysis/blob/f47de51326652a959001966393582dd42a19ed1c/haq_final.xlsx).

Here, you can find interactive datatables and bar charts exploring:

1. Share of each of the classification of the type of scheme in the total expenditure.
2. Compare the expenditure of each district on different types of schemes.
3. Identify schemes with expenditure of zero.
4. Identify the grant type with highest amount of expenditure.
5. Identify the observations(/schemes) with the highest and lowest expenditure.
6. Identify the observations(/schemes) with the highest and lowest allotment.
7. Explore the share of each of the mode of benefit of transfer in the total expenditure.
8. Compare the expenditure of each district on modes of benefit of transfer.


# Interesting Observations!?

1. There were a large number of schemes, whose expenditure amount was zero, but percentage of scheme utilisation was a positive number other than 0 (For example,60%)!
2. There were a number of schemes whose scheme allotment amount was negative !? 

These can be mistakes in data entry, but definitive issues that need to be flagged.
