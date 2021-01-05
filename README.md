# EVENODD-FUNCTION
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
       
