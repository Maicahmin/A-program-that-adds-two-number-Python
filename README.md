# A-program-that-adds-two-number-Python


1. The program will ask to enter first and second number

2. The program will display "The sum of n1 and n2 is nTotal"

3. The program will ask if the user wants to try again. The user will inputY/y if Yes and N/n if No

4. If Yes, refer to step 2

6. If No, the program will display "Thank you!".

-----------------------------------------------------------------------------------------------------------

      a = "y"

      while a.lower() == "y":

      word = int(input("Enter first number: "))
      
      word2 = int(input("Enter second number: "))
      
      sum = word + word2
      
      print("Total: " + str(sum))
      
      a = str(input("Do you want to try again? type (y/n)\n"))
      

print("THANK YOU !")
