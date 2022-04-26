# leapyear
#this code includes to check wether a given year is leap year or not

#enter your year ,year is the input
if (year%4)==0:#conditions to satisfy for a leap year
 if(year%100)==0: 
  if(year%400)==0:
    print("its a leap year") 
   # if part is false
    #else part is executed 
  else:
        print("its not a leap year")
 else:
      print(" leap year")
else:
    print("non leap year")      
