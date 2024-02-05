#Program name: Ferrari Prices
#Program Author: Britney Malone
#Program Objective: Give the prices of Ferrari
#----------------------------------------------------------------------
#Psuedocode:
#1. Define the variable.
#a. request the year
#b. define the limits of the year
#1. Define the price.
#a. Define the price based on the input
#-------------------------------------------------------------------------
#Inout: Year of Ferrari make
#Output: Price
#----------------------------------------------------------------------------
year= 0
int(input('Year: '))
if year <= 1964:
    print ("$18,500")
elif year <= 1968:
    print ("$6,000")
elif year <= 1971:
    print ("$12,000")
elif year <= 1980:
    print ("$200,000")
elif year <= 1985:
    print ("$650,000")
elif year <= 2012:
    print ("$35,000,000")
elif year <= 2014:
    print ("$52,000,000")
else:
    print ("The Price data is not available yet!")
