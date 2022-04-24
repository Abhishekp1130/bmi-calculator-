# leapyear
#this code includes to check wether a given year is leap year or not
year=int(input("which year do you want to check"))
if (year%4)==0:
 if(year%100)==0: 
  if(year%400)==0:
    print("its a leap year")
  else:
        print("its not a leap year")
 else:
      print(" leap year")
else:
    print("non leap year")      
