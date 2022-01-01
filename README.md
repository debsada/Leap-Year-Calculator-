# Leap-Year-Calculator-
Programme that works out whether a given year is a leap year 
year = int(input("Which year do you want to check? "))



if year % 4 == 0:                      #If a year is divisible by 4 then it is a leap year except it is divisible by 100 unless it is divisible by 400
    if year % 100 == 0:
        if year % 400 == 0:
            print("Leap year.")
    else:
        print("Leap year.")
else:
    print("Not leap year.")

