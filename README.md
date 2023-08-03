# Aadhar-Card-Validator
num = input("Please enter a 12 digit aadhar number: ")
if len(num) > 12 or len(num) < 12:

    print("Aadhar number is not valid (Enter a 12 digit number)")
elif num[0] == '0' or num[0] == '1':
        print("Aadhar number is not valid (Aadhar card number cannot start with 0 or 1)")
elif num.isalpha():
     print("invalid Please Enter Correct Number")      
else:
    print("Aadhar number is valid")
