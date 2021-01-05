# Write a Python program to find whether a given number (accept from the user) is even or odd, print out an appropriate message to the user.

def even_odd():
    
    number="wrong"
    while number.isdigit()==False:
        number=input("Please enter your number: ")
        
        if number.isdigit()==False:
            print("You did not enter a valid number.")
        if number.isdigit()==True:
            
            if int(number)%2==0:
                print (f"The number you entered, which is {number} is even.")
            else:
                print (f"The number you entered, which is {number} is odd.")
       

# Write a Python program to count the number 4 in a given list.

lst=[1,2,3,4,5,6,7,8,4,5,4,3]

count=0
for num in lst:
    if num==4:
        count+=1

print (f"The number 4 is in the list {count} times")

# Write a Python program to test whether a passed letter is a vowel or not.

def if_vowel():

    letter="wrong"
    while letter not in ["a","e","i","o","u"]:
        letter=input("Please enter yout letter: ")
        if letter not in ["a","e","i","o","u"]:
            print ("That is not a vowel, try again: ")
            
        if letter in ["a","e","i","o","u"]:
            print (f"Congratulations, '{letter}' is a vowel.")


# Write a Python program to check whether a specified value is contained in a group of values.

values= [1,2,3,4,5]

def value_present():
    
    choice= "wrong"
    
    while choice.isdigit()==False:
        choice= input("Please enter your desired number: ")
        
        if choice.isdigit()==False:
            print ("That is not a number. Try again: ")
            
        if choice.isdigit()==True:
            if int(choice) in values:
                return True
            else:
                return False
                        
# Write a Python program to concatenate all elements in a list into a string and return it.

lst=["my","student","number","is",111448]

def conct_lst():
    
    conlist=""
    
    for items in lst:
        conlist+=str(items)+" "
    print (conlist)


# Write a Python program to print all even numbers from a given numbers list in the same order and stop the printing if any numbers that come after 237 in the sequence.



# Write a Python program to print out a set containing all the colors from color_list_1 which are not present in color_list_2.

color_list_1= ["white","black","red"]
color_list_2= ["red","green"]

list3=[]

for items in color_list_1:
    
    if items not in color_list_2:
        list3+=[items]
    else:
        pass
print (list3)
            
