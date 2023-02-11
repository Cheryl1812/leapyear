# leapyear
# a challenge from Angela Yu's python course.  Figured it out in the end! 
year = int(input("Which year do you want to check? "))
# 🚨 Don't change the code above 👆

#Write your code below this line 👇
#leapyearby4 = year % 4
#print (leapyearby4)
if year % 4 == 0 and year % 100 != 0:
    if True:
        print ("Leap year.")
    if False:
        if year % 400 ==0:
         print ("Leap year.")
else:
    print ("Not leap year.")
